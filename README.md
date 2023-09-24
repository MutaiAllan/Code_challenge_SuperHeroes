## Phase 4 Code Challenge: Superheroes
My codebase for Moringa weekly codechallenge for phase 4 week1.
 ## Topics
 1. Flask routing and Views.
 2. Flask-SQLAlchemy.
 3. Working with APIs. Sending requests; GET, POST, PATCH.
 4. SQLAlchemy validations.
 5. Connecting REact with Flask.

 ## Instructions for setting up the project
 1.cd into code_challenge directory.
 ```sh
 cd code_challenge
 ```
 2.Install the dependencies for frontend and backend:
 ```sh
 pipenv install
 npm install --prefix client
 ```
 3.Run the flask API inside the app directory:
 ```sh
 cd app
 flask run
 ```
 4.On another terminal, inside the code_challenge directory, start the React app:
 ```sh
 npm start --prefix client
 ```