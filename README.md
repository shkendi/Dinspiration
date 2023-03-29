# Dinspiration ReadMe link 
 A full stack app allowing food-lovers to share inspiration and try out new foods and ingredients
 
 Dinspiration ReadMe



Description

Dinspiration

Project 3 was a full-stack MERN app that we built for all food lovers that in busy times would like to have something quick and healthy on their table when coming back home. An app that everyone could access wherever we are, bus, train or working in our office. Cooking would be a more creative and happier moment if we could share our ideas.

 







Deployment link

Click the project link below to give it a try.

https://dinspiration.netlify.app


Getting Started/Code Installation
Backend
clone repo Dinspiration-Backend
open Dinspiration-Backend in my code editor
cd into the root directory and run 'npm i' in the terminal to install the dependencies
run 'npm run seed' in the terminal to add the seed data for your demo
run 'npm run build' in the terminal to build the JavaScript in the dist folder
run 'npm run dev' in the terminal to run the program
Frontend
clone repo Dinspiration-Frontend
open Dinspiration-Frontend in my code editor
cd into the root directory
run 'npm i' to install the dependencies
run 'npm run build' to build the JavaScript files in the dist
run 'npm run dev' to run the program
Preview the index.ts in the browser






Timeframe & Working Team (Solo/Pair/Group)


Project Members:
Pamela Smith: https://github.com/PamelaOnGit
Jane Adojutelegan: https://github.com/lumpyspayzprincess
Shkendi Naqellari: https://github.com/shkendi
Timeframe: 11 days.






Technologies Used

Technologies used:

React.js
Node.js
Express
MongoDB/Mongoose
SASS
Bulma
Axios
Nodemon
HTTP-proxy-middleware
Bcrypt
JSON web token
Git/GitHub









Brief
Technical Requirements
Work in a team, using git to code collaboratively
Build a full-stack application by making your own backend and your own front-end
Use an Express API to serve your data from a Mongo database
Consume your API with a separate front-end built with React
Be a complete product which most likely means multiple relationships and CRUD functionality for at least a couple of models
Implement thoughtful user stories/wireframes that are significant enough to help you know which features are core MVP and which you can cut
Have a visually impressive design to kick your portfolio up a notch and have something to wow future clients & employers. ALLOW time for this
Be deployed online so it's publicly accessible
Have automated tests for at least one RESTful resource on the back-end Improve your employability by demonstrating a good understanding of testing principles.
Necessary Deliverables
A working app hosted on the internet
A link to your hosted working app in the URL section of your Github repo
A git repository hosted on Github, with a link to your hosted project, and frequent commits dating back to the very beginning of the project
A readme.md file with:
An embedded screenshot of the app
Explanations of the technologies used
A couple of paragraphs about the general approach you took
Installation instructions for any dependencies
Link to your user stories/wireframes – sketches of major views / interfaces in your application
Link to your pitch deck/presentation – documentation of your wireframes, user stories, and proposed architecture
Descriptions of any unsolved problems or major hurdles you had to overcome





Planning

We agreed on a food app; when we are busy with work, family and friends, meals can become a chore and we can end up eating the same things every day. We all liked the idea of an app that allows users to inspire one another with fun and interesting suggestions.

We agreed that Pam would take the lead on the user flow, Jane on the foods, and me on the recipes (which we called “inspirations”). We all contributed to the planning with ideas and logic and agreed that Jane would configure it using Figma. Planning was done mainly on the first day, added a few more details the day after, and then we jumped straight into the coding stage.    
We used Figma to create a mock-up of how the app would function. We worked up a flow, as follows:




Signup and Login
Once logged in, the user is invited to provide some information about the sort of food they might want to try:





My Foods, Food Screen and Recipes
The user is then presented with a selection of slightly unusual ingredients to try out. Clicking on a particular food takes the user to a screen with more information about the chosen food and, below it, a selection of user-generated recipes and serving suggestions:


Add Recipe
The user can share their own recipe or serving suggestion, along with a photo of their creation.




Build/Code Process


We set up a Jira project and divided the project into stages: planning and setup, backend-setup, backend development, frontend-setup, frontend development, and testing.
Pam set up the project called Dinspiration, dinspiration-backend and dinspiration-frontend, and we cloned it. 
I set up two branches and called them Shkendis-Backend and Shkendis-Frontend and pushed all the code to the main repository every time I made changes. I started on the backend by creating a basic API with some dummy user data in a file inside the backend repo.


1- Inspiration schema
I created the InsirationSchema on the backend after working out what data we needed to pass through, how would a screen page connect to another, typeof and whether they were required or not.





Based on the schema, I created the InspirationData file with some data to seed, so I created a db folder with a new file in it which I called inspirationData. Inside it, I created a variable called inspirationData and assigned it an array of inspirations objects based on the inspirationSchema which I had previously created in the models folder. 



Here are the functions for making our requests, get, getById, post, put/patch and delete using json promises.




I created the InspirationsList where we can find all the inspirations posted from any user, get inspired from them and create our own ones with the food we have in the fridge which brings us to the original idea of why we decided to build this app.
I used React Hooks, in this case, .useState() to get inspirations, destructure, and update them later into inspirations cards with values shown in the interface. I did this by first sending a request using React promises, and getting back the data;  I used .map() and .filter() methods to filter through the inspirations array and displayed the cards.


Challenges

This was my first time working with Git as a member of a team so I had some problems with getting used to checking out and merging feature branches. Good communication was key to avoid major merge conflicts, and the encouraging team spirit kept our collective work to a high standard.




Wins

Project 3 for me was a workspace where I could practise the code for building
signup and login pages which we’ve just learned during the course. I also learned to build the “upload Inspiration” form using React Axios library. The logic behind it was difficult but working in a team really helped me in this task. My whole understanding of backend, frontend, terminal and GitHub got much better during the development of this full-stack app.   






Here we are offered the button option to add an inspiration, which if clicked will direct us to the inspiration page






Key Learnings/Takeaways

This project was definitely the most challenging up to date, bringing together everything we'd learnt on the course so far. Having each team member taking ownership of their respective area of responsibility, I came to realise the importance of a managing entity in a development team, i.e. to have someone leading the process and holding all the strings.
I found working as a part of a team very beneficial, collaborative work seemed to amp up my delivery and code quality to a whole other level.





Bugs
There are no bugs so far.
 
Future Improvements

I would like more social features to the app in the future, like adding a chat option in order to make the users communicate with each other and feel more connected within  the community.
I would like to apply some other styling features as well since we ran out of time and couldn’t add everything as planned.

 
 
 
