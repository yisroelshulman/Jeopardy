# jeopardy

This is a class project of building the jeopardy game from scratch

##### Starting localhost server

**Start localhost** 

From the `src` folder, run `node server.js`

Then in the browser go to http://localhost:8000/app to view the gameboard

### 1. Project goals

The documentation outlining goals for the project can be found in the `design_docs` folder.


### 2. What was done

The frontend is designed to look like the jeopardy game with 5 topics, and 5 value categories for each topic. Each of them is a button that when clicked shows the question and a button to click when the user wants to show the answer. Only after show answer is clicked can the user exit the question screen.

The backend contains the database where there is a 1-1 correspondence between questions to the number of options the user has on the frontend. The server is a local express server run in a node environent and the database is sqlite.

### 3. What was left out

- The list of topics is limited and does not cover all the class work.
- Within each category there is no variation having each topics category have a list of 5+ questions from which 1 is randomly selected would be more comprehensive.
- The query's return the text with quotations escaped, however, this should not be displayed to the user.
- A way to keep score.