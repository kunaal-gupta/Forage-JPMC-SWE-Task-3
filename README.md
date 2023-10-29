# JPMC Task 3
Starter repo for task 3 of JPMC's Forage program

Being able to access and adjust data feeds is critical to trading analysis and stock price monitoring. With the prior tasks complete, we have the adjusted data set up on your system and piped into Perspective.

For traders to have a complete picture of all the trading strategies being monitored, several screens typically display an assortment of live and historical data at their workstations.

Given that an enormous amount of information and data are produced at once, visualising data in a clear manner with UI/UX considerations accounted for is critical to providing traders with the tools to improve their performance.

# Set Up
Just like in the last task, you need to get your local development environment up and running. Given that you completed task 2, you should already have python and node installed and have at least a marginal familiarity with git

1. First, fork and clone the project repo: https://github.com/theforage/forage-jpmc-swe-task-3
Remember to uncheck the “Copy the main branch only” box in the fork dialog on github. A model answer has been provided in a separate branch from main.
Create a new virtual environment in the project root. Pycharm can do this automatically for you using the “configure python interpreter” option in settings.
Install all project python dependencies. These are listed in the requirements.txt file.
 

2. Install the necessary dependencies by running `npm install` from the project repo
 

3. Recall that you must have node 18.10.0 installed for this step to work correctly
 

4. Start the python server by running server3.py from the project repo like so: python datafeed/server3.py (note it’s important you run it from the root of the project repo) 
 

5. Start the client by running `npm start` from the project repo