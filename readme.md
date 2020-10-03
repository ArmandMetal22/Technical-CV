This website consists of 5 html files:
#index.html
#more.html
#game.html
#highscores.html
#end.html

Notes:
*The "Send a Message" box in the contact section is not in a working state, which means that the user will not be able to send an email via the website at this moment.
 This functionality will be updated and in working condition once the website is developed using Vue.js in the future.
*The best way to view this website is on a desktop, as the website generates some scaling issues on a mobile device, or when the window is minimized or resized. (Will be fixed in the updated version.)

When the user arrives at the website, what the user will see is the index.html page,
which consists of information about the site, and the user will be able to choose what to do between 3 buttons:
#"Find out more -->" This will redirect the user to the more.html page where the Technical CV will be displayed.
#"Play Game" This will redirect the user to the game.html page, where there will be a small quiz the user can complete.
This quiz queries random questions from the Open Trivia API. If the user has completed the quiz, he/she can store their highscores.
#"View Scores" This will redirect the user to the highscores.html page where the user can see all the highscores of people who have taken the quiz.

more.html:
This page contains all information about the CV displayed.
The navigation bar at the top of the page will allow the user to scroll through the different sections.
#"Home" - Displays a welcoming message to the CV site and explains its purpose.
#"About" - A short summary is given about the author's education, quotes, and information in a future working environment.
#"Skills" - Displays all the skills the author possess, in table form and percentage.
#"Experience" - Displays information regarding the author's past experiences as a student in the IT industry, as well as a intern.
"Projects" - Displays information regarding the author's past projects.
"Contact" - Displays the author's contact details and social media links. (See notes above.)
"Return" - Returns the user to the index.html page.

