#### Background

- Create a catch game web application
- You are required to develop a catch game and display the top players score on the leaderboard web application.
- You are also required to set up a mechanism to store the user data and score.

#### Getting started

- `cd` into [`catch-game-web`](./catch-game-web/) directory and run `yarn start` to run the catch game frontend locally on port 3000.
- Open another terminal, `cd` into [`catch-game-service`](./catch-game-service/) directory, run `docker-compose up -d` to run a redis locally on port 6379 and run `yarn start:dev` to run the node.js server on port 8080.
- Proceed to http://localhost:3000 on browser to use this application.
- Refer to `README` of [`catch-game-web`](./catch-game-web//README.md) or [`catch-game-service`](./catch-game-service/README.md) for more details.

#### Requirement

##### Catch game web application

- The game displays the start menu. There will be 2 options: Start Game and Leaderboard.
- The game only lasts for 60 seconds.
- The user is able to move the catcher left or right to catch the items.
- The items drop from top to bottom.
- Catching the image (p1-p4) in the assets pack add 50 points.
- Catching the image (e1-e2) in the assets pack minus 100 points.
- Once the game is finished, the user can input the name and see the ranking.

##### Leaderboard web application

- The application will display the top 100 players in real time.
- Each rank shows the player’s score and name.

##### What we are looking for?

- The completed frontend and backend application source code.
- List out the APIs with the detailed description.
- The application setup guide and documentation.
- The application is able to support multiple screen sizes.
