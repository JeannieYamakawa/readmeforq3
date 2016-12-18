# Sprintr

Welcome to Sprintr!

Sprintr is Chrome browser extension and web app built by [Tim Chew](http://www.github.com/timothyrchew),  [Jeannie Yamakawa](http://www.github.com/JeannieYamakawa), and [Robert Varela](http://www.github.com/rvarela11) in the course of a week. 

Our goal was to incentiveize productivity through creating a Chrome browser extension and web application that allows users to create "sprints," or competitions, that track friends' time spent on productive websites. 

We taught ourselves AngularJS the week prior to beginning the project, and then built Sprintr on:
* Node.js
* Express
* AngularJS
* PostgreSQL

*Hard work pays off. Let's sprint together.*


##  Create a Sprint 
<img align="right"  height="300" width="500" src="https://i.gyazo.com/666d37af0d208915f33386ee47e80fb5.png">
* Pick a start and end date for your sprint. 
* Designate the productive websites you would like to track during the course of the Sprint. 
* If you would like to up the stakes, designate your Sprint as a cash game. This will require all players to contribute to a cash pot (through Dwolla). The winner of the sprint takes home the pot.

##  Invite Your Friends
<img align="left"  height="300" width="500" src="https://i.gyazo.com/666d37af0d208915f33386ee47e80fb5.png">
* Pick a start and end date for your sprint. 
* Designate the productive websites you would like to track during the course of the Sprint. 
* If you would like to up the stakes, designate your Sprint as a cash game. This will require all players to contribute to a cash pot (through Dwolla). The winner of the sprint takes home the pot.

##  Download the Chrome Extension
<img align="right"  height="300" width="500" src="https://i.gyazo.com/666d37af0d208915f33386ee47e80fb5.png">
* Pick a start and end date for your sprint. 
* Designate the productive websites you would like to track during the course of the Sprint. 
* If you would like to up the stakes, designate your Sprint as a cash game. This will require all players to contribute to a cash pot (through Dwolla). The winner of the sprint takes home the pot.

##  Compete To Win
<img align="left"  height="300" width="500" src="https://i.gyazo.com/666d37af0d208915f33386ee47e80fb5.png">
* Pick a start and end date for your sprint. 
* Designate the productive websites you would like to track during the course of the Sprint. 
* If you would like to up the stakes, designate your Sprint as a cash game. This will require all players to contribute to a cash pot (through Dwolla). The winner of the sprint takes home the pot.

## Other technologies used for this project:

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds






### Shopping Cart Should Have the Following Specs:
- Search by name
- Search by category with drop down list
- Table with column for image,  and tea information
- Quantity drop down number list
- Add to bag button
- New items added to bag default to qty of 1, if no qty is selected
- Checkout button
- Checkout/bag starts empty, then updates with number of items
- Tea information section has:
  - Price, Caffeine Scale, Ingredients, Rating
 - In Stock? - shows `Yes` or `No` when True/False respectively
 - Categories - goes through categories list and displays each one
- Checkout page
 - Order total
 - Lists each item that was added from the previous page, and includes its quantity
 - Ability to edit quantity
 - Editing quantity updates the sub-total and order total
 - Ability to remove a product, which then updates the order total
 - Items in checkout show the caffeine scale, ingredients, rating, and sub-total

## Part Two - Angular Custom Directive: Caffeine Meter

In this exercise, we're going to revisit the angular tea shopping cart and create a custom directive to graphicaly display the ammount of caffeine in each tea.

# The caffeine display should look something like this:
![](https://i.gyazo.com/666d37af0d208915f33386ee47e80fb5.png)


The code should look someting like this:
```
<caffeine-meter caffeinemg="tea.caffeineScale" id="tea._id"></caffeine-meter>
```

![](https://i.gyazo.com/8c1d4c68b881d8a0431202e3b7469c8e.png)
