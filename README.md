# Sprintr

Welcome to Sprintr!

Sprintr is Chrome browser extension and web app built by [Tim Chew](http://www.github.com/timothyrchew),  [Jeannie Yamakawa](http://www.github.com/JeannieYamakawa), and [Robert Varela](http://www.github.com/rvarela11) in the course of a week. 

Our goal was to incentiveize productivity through creating a Chrome browser extension and web application that allows users to create "sprints," or competitions, that track friends' time spent on productive websites. 

We taught ourselves AngularJS the week prior to beginning the project, and then built Sprintr on:
* Node.js
* Express
* AngularJS
* PostgreSQL

### Challenges we faced:
* This was our very first application built in Angular, and we learned a lot about the digest cycle and rendering dynamically updated views in the process, as our Chrome extension's tracking functionality is working in the background at all times.

* We had lofty aspirations of connecting to players' PayPal accounts to be able to have a cash payout for winning. We applied with PayPal to use its Payouts API twice, but were rejected both times on the basis our app being categorized as "online gaming." PayPal's dev support phone representatives described as a "too risky a category" for PayPal to allow us use of the Payouts API. We then had to find an alternative to allow the transfer of money through our app, which we found and implemented in [Dwolla](https://developers.dwolla.com/).

* The Google Chrome extension development environment was also entirely new for all three of us.
* We wanted to render leaderboard data in charts, but connecting ChartJS to Angular was tricky. We ended up having to use a [3rd-party Angular chart library](https://jtblin.github.io/angular-chart.js/).

what we would do differently


situation
task
action
result


*Hard work pays off. Let's sprint together.*

# Sprintr Walkthrough

##  Create a Sprint 
<img align="right"  height="300" width="500" src="https://i.gyazo.com/666d37af0d208915f33386ee47e80fb5.png">
* Pick a start and end date for your sprint. 
* Designate the productive websites you would like to track during the course of the Sprint. 
* If you would like to up the stakes, designate your Sprint as a cash game. This will require all players to contribute to a cash pot (through Dwolla). The winner of the sprint takes home the pot.

<br><br><br><br>

##  Invite Your Friends
<img align="left"  height="300" width="500" src="https://i.gyazo.com/666d37af0d208915f33386ee47e80fb5.png">
* Pick a start and end date for your sprint. 
* Designate the productive websites you would like to track during the course of the Sprint. 
* If you would like to up the stakes, designate your Sprint as a cash game. This will require all players to contribute to a cash pot (through Dwolla). The winner of the sprint takes home the pot.

<br><br><br><br>

##  Download the Chrome Extension
<img align="right"  height="300" width="500" src="https://i.gyazo.com/666d37af0d208915f33386ee47e80fb5.png">
* Pick a start and end date for your sprint. 
* Designate the productive websites you would like to track during the course of the Sprint. 
* If you would like to up the stakes, designate your Sprint as a cash game. This will require all players to contribute to a cash pot (through Dwolla). The winner of the sprint takes home the pot.

<br><br><br><br>

##  Compete To Win
<img align="left"  height="300" width="500" src="https://i.gyazo.com/666d37af0d208915f33386ee47e80fb5.png">
* Pick a start and end date for your sprint. 
* Designate the productive websites you would like to track during the course of the Sprint. 
* If you would like to up the stakes, designate your Sprint as a cash game. This will require all players to contribute to a cash pot (through Dwolla). The winner of the sprint takes home the pot.

## Other technologies used for this project:

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

