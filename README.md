# Sprintr

Welcome to Sprintr!

Sprintr is Chrome browser extension and web app built by [Tim Chew](http://www.github.com/timothyrchew),  [Jeannie Yamakawa](http://www.github.com/JeannieYamakawa), and [Robert Varela](http://www.github.com/rvarela11) in the course of a week. 

Our goal was to incentiveize productivity through creating a Chrome browser extension and web application that allows users to create "sprints," or competitions, that track friends' time spent on productive websites. 

We built Sprintr on Node, Express, Angular, and PostgreSQL, after having taught ourselves Angular the week prior to beginning the project.

*Hard work pays off. Let's sprint together.*


###  Create a Sprint 
Pick a start and end date for your sprint. Designate the productive websites you would like to track during the course of the Sprint. If you would like to up the stakes, designate your Sprint as a cash game. This will require all players to contribute to a cash pot (through Dwolla). The winner of the sprint takes home the pot.



### Installing

A step by step series of examples that tell you have to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```



## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds



## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone who's code was used
* Inspiration
* etc



## SETUP

- Clone this repository to your local machine
- Run `npm install`
- Run `node seed`

## Part One - Angular Views and Directives
# Angular Shopping Cart App

## Click to watch the video:
[![](https://i.gyazo.com/b83c4f06526777f552cb5d817c24e567.png)](https://vimeo.com/135907781)


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
