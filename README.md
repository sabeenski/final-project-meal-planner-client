# Planet Friendly Meal Planner 
This is a front-end part of our full stack team project that plans planet friendly meals.
  
## Description 
The website offers a weekly calendar with healthy meal plans that is randomly taken from the database. Ingredients are calculated based on the number of households. Users can choose or change a displayed meal plan and add it to their shopping list, which can be printed out.

## Features
* Sign in/Log in page: helps the user create a secured user account that offers access to a personal weekly meal planner and a personalized shopping list.
* Meal Planner Page: displays a personal planner that starts with seven random recipes (retrieved from a PosgreSQL database run on Heroku's servers).
* Each recipe presents the ingredients calculated for the entire household (for children only half of the adult amount is calculated).
* Change recipe button: gives the user the option to change a recipe from the planner with another one from the recipes list.
* Add to (shopping) list button: creates a shopping list by either adding the ingredients for all recipes at once or for one recipe at a time.
* Shopping cart button: displays the shopping list.
* Print / Clear buttons: help the user to print or clear the shopping list.
* Log out button: redirects the user to the Log in page.

## Tech Stack
* JavaScript
* React
* Redux
* HTML5
* CSS3

[View Demo](https://loized.com/img/meal/video_meal.gif) 

**You can visit the actual website here** https://planet-friendly-meal-planner.netlify.com and use the following credentials:

   *Username*: sabi@test.com 
   
   *Password* : abcd1234
  
### Team & Tasks
* We were a team of four developers and one designer who worked together in this project for about two weeks time. An MVP was created with the features listed above. 
* 2 developers handled back-end and the other two handled front-end. I was responsible for the frontend application, working closely with another developer and the UX designer. 
* You may see my *some* of mycodes here: 
[RecipeDetails](https://github.com/sabeenski/final-project-meal-planner-client/blob/master/src/components/recipes/RecipeDetails.js)
[NavBar](https://github.com/sabeenski/final-project-meal-planner-client/blob/master/src/components/navbar/Navbar.js)

### Project Management
* We followed agile development methodology, a daily Scrum meeting to discuss, plan and share new ideas. Trello was used to track our daily tasks and Slack was used as a communication channel. 

**The back-end repo can be found here**: https://github.com/sabeenski/final-project-meal-planner-server

