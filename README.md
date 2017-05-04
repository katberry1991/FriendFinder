# FriendFinder

Description 
This is a compatibility-based "FriendFinder" application -- basically a dating app. This full-stack site will take in results your users' surveys, then compare their answers with those from other users. The app will then display the name and picture of the user with the best overall match.
You will use Express to handle routing. Make sure you deploy your app to Heroku so other users can fill it out.


Requirements
1. Use Express to handle routing. 

2. Survey should have 10 questions of your choosing. Each answer should be on a scale of 1 to 5 based on how much the user agrees or disagrees with a question.

3. Server.js file should require the basic npm packages we've used in class: express, body-parser and path.

4. htmlRoutes.js file should include two routes:

5. A GET Route to /survey which should display the survey page.

6. A default USE route that leads to home.html which displays the home page.

7. apiRoutes.js file should contain two routes:

8. A GET route with the url /api/friends. This will be used to display a JSON of all possible friends.

9. A POST routes /api/friends. This will be used to handle incoming survey results. This route will also be used to handle the compatibility logic.


Technologies Used
JavaScript
Node.js
Express.js 
