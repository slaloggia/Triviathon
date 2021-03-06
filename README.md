# Triviathon
## Run a Trivia Marathon!
- Log in with your username to create an account or continue playing.
- Choose a category to start your race. Default length is Half-Marathon (13 questions)
- Answer questions of varying difficulty to earn points:
    - Easy = 1 point 
    - Medium = 3 points
    - Hard = 5 points
- Submit your score and rise up the leaderboard!

![image](https://user-images.githubusercontent.com/54509406/76034600-fb5e7180-5f04-11ea-858d-32b3ff7f3dcd.png)

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

## Tools
Built with Javascript and styled with [Bootstrap](https://getbootstrap.com/)

Questions fetched from [Open Trivia Database](https://opentdb.com/)

## Future Build Features
- User authentication with secure passwords
- Answers render in collapsible component
- Option for user to view all questions answered

Created by Valeriia Hutsuliak, Naveed Ganjani, and Sarah Laloggia for Flatiron School's Software Engineering Bootcamp, Module 3 (Rails) Project 2019
