# Triviathon
## Run a Trivia Marathon!
- Log in with your username to create an account or continue playing.
- Choose a category to start your race. Default length is Half-Marathon (13 questions)
- Answer questions of varying difficulty to earn points:
    - Easy = 1 point 
    - Medium = 3 points
    - Hard = 5 points
- Submit your score and rise up the leaderboard!

## Set up
    Navigate to triviathon-backend directory and run the following:
    ```
    bundle install
    rails db:migrate
    rails db:seed
    rails s
    ``` 

    Navigate to triviathon-frontend directory and run the following:
    ```
    npm install
    open index.html
    ```
