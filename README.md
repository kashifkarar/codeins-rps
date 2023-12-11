# codeins-rps
This Readme file is for conde-institute project2

The game of Rock Paper Scissors is a timeless classic that has been enjoyed by people of all ages for generations. Despite its simplicity, the game can be incredibly challenging and entertaining, making it a perfect starting point for those who are interested in game development.


## Features 

This game includes media queries for devices with a maximum screen width of 600px. In this case, the choices section is wrapped when there is not enough space, and the margin of the choice box is reduced. Fun to play with Computer as your opponent!

### Existing Features
The computerPlay function generates a random weapon choice for the computer.


The updateScore function takes two arguments, the player's and computer's weapons. It compares the weapons, determines the winner, updates the scores, and displays the result on the web page. The function also handles the cases where the player has not made a choice or one player reaches a score of 5.


The selectWeapon function is called when the player clicks on one of the weapon choices. It retrieves the player's choice and calls the updateScore function with the player's and computer's weapons as arguments.


The startTimer function is called after the player makes a choice. It starts a countdown timer and updates the remaining time on the web page. If the timer reaches zero, the function calls the updateScore function with null for the player's weapon to indicate that the player did not make a choice in time.


The stopTimer function is called when the game is over. It clears the countdown timer and resets the countdown value.


The resetGame function is called when the player clicks on the "Play Again" button. It resets the game state, updates the web page, and starts a new countdown timer.


The disableOptions and enableOptions functions are called to disable and enable the weapon choices respectively.


The choices and playAgainBtn DOM elements have event listeners attached to them. When the player clicks on a weapon choice, the selectWeapon function is called. When the player clicks on the "Play Again" button, the resetGame function is called.


Finally, the code sets the initial value of the countdown on the web page and starts the countdown timer when the page loads.

## Testing 

 live test in teh local repository and at public URL had no lag or issues with the results again the players.


### Validator Testing 

- HTML
    - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fkashifkarar.github.io%2codeins-rps%2F)
- CSS
    - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fkashifkarar.github.io%2codeins-rps%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)
- JavaScript
    - No errors were found when passing through the official [Jshint validator](https://jshint.com/)
      - The following metrics were returned: 
      - There are 11 functions in this file.
      - Function with the largest signature takes 2 arguments, while the median is 0.
      - Largest function has 10 statements in it, while the median is 3.
      - The most complex function has a cyclomatic complexity value of 4 while the median is 2.

### Unfixed Bugs

You will need to mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a big variable to consider, paucity of time and difficulty understanding implementation is not a valid reason to leave bugs unfixed. 

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub) 

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://kashifkarar.github.io/codeins-rps/


## Credits 

Thanks to jshint | css validator free tools which helped to validate the code in quicker and effecient way!

### Content 

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/watch?v=8dWL3wF_OMw)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used on the home and sign up page are from This Open Source site
- The images used for the gallery page were taken from this other open source site


