# Sprintr

Welcome to Sprintr!

Sprintr is Chrome browser extension and web app built by [Tim Chew](http://www.github.com/timothyrchew),  [Jeannie Yamakawa](http://www.github.com/JeannieYamakawa), and [Robert Varela](http://www.github.com/rvarela11) in the course of a week. 

Our goal was to incentiveize productivity through creating a Chrome browser extension and web application that allows users to create "sprints," or competitions, that track friends' time spent on productive websites. 

We taught ourselves [AngularJS](https://angularjs.org/) the week prior to beginning the project, and then built Sprintr on:
* Node.js
* Express
* AngularJS
* PostgreSQL
<hr>

### Challenges we faced:

* This was our very first application built in Angular, and we learned a lot about the digest cycle and rendering dynamically-updated views in the process, as our Chrome extension's time-tracking functionality is working in the background at all times.

* We had lofty aspirations of connecting to players' PayPal accounts to be able to have a cash payout for winning. We applied with PayPal to use its Payouts API twice, but were rejected both times on the basis our app being categorized as "online gaming." PayPal's dev support phone representatives described as a "too risky a category" for PayPal to allow us use of the Payouts API. We then had to find an alternative to allow the transfer of money through our app, which we found and implemented successfully in [Dwolla](https://developers.dwolla.com/).

* The Google Chrome extension development environment was entirely new for all three of us and took some getting used to.

* We wanted to render leaderboard sprint data in charts, but connecting the ChartJS library to Angular was tricky. We ended up having to use a [3rd-party Angular chart library](https://jtblin.github.io/angular-chart.js/).

* We wanted to have the web portal automatically render a user's personalized dashboard when a user clicks "View Web Portal" button on the extension popup, but we discovered that the Chrome extension's local storage is a completely different local storage from the Chrome browser's local storage, thus creating a chasm in the saved data about who is logged in. This was the one challenge we were not able to solve in the week allotted for our project, although the user's data is viewable and current when he/she logs into the web app. We also definitely learned a lot about navigating Google's [JavaScript APIs](https://developer.chrome.com/extensions/api_index).
<hr>
### Other technologies used for this project:

* [Heroku](http://www.heroku.com) - used for deployment
* [Knex.js](http://knexjs.org/) - used as SQL query builder 
* [Semantic-UI](http://semantic-ui.com/) - to help with page styling


<strong>*Hard work pays off. Let's sprint together.*</strong>

# Sprintr Walkthrough

###  Create a Sprint 
<img align="right"  height="400" width="650" src="https://i.gyazo.com/e2f7039b7438447e147089f4ddb1e750.png">
* Name your sprint.
* Pick a start and end date for your sprint. 
* Designate the productive websites you would like to track during the course of the Sprint. 
* If you would like to up the stakes, designate your Sprint as a cash game. This will require all players to contribute to a cash pot (through Dwolla). The winner of the sprint takes home the pot.

<br><br><br><br>

###  Invite Your Friends
<img align="left"  height="400" width="650" src="https://i.gyazo.com/86a0f43d50b78898099bdf34f8c04da1.png">
* Pick a start and end date for your sprint. 
* Designate the productive websites you would like to track during the course of the Sprint. 
* If you would like to up the stakes, designate your Sprint as a cash game. This will require all players to contribute to a cash pot (through Dwolla). The winner of the sprint takes home the pot.

<br><br><br><br>

###  Download the Chrome Extension
<img align="right"  height="500" width="700" src="https://i.gyazo.com/666d37af0d208915f33386ee47e80fb5.png">
* Pick a start and end date for your sprint. 
* Designate the productive websites you would like to track during the course of the Sprint. 
* If you would like to up the stakes, designate your Sprint as a cash game. This will require all players to contribute to a cash pot (through Dwolla). The winner of the sprint takes home the pot.

<br><br><br><br>

###  Compete To Win
<img align="left"  height="500" width="700" src="https://i.gyazo.com/666d37af0d208915f33386ee47e80fb5.png">
* Pick a start and end date for your sprint. 
* Designate the productive websites you would like to track during the course of the Sprint. 
* If you would like to up the stakes, designate your Sprint as a cash game. This will require all players to contribute to a cash pot (through Dwolla). The winner of the sprint takes home the pot.


