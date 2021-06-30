# Challenge

Every football supporter wants to know what's happening with their favorite players.
In this challenge you'll be able to do just that!

## Considerations:

### There should be two different frotend applications consuming the api endpoints
- An admin one, responsible for managing players and trigger notifications
- An user one, responsible for listing all the players and subscribing to notifications regarding some of them

### The endpoints should enable
- crud endpoints for players
- crud endpoints for notifications
- subscribing notifications

### The models to implement are the following

> feel free to implement all the othe models that you feel are missing

- players:
  - name
  - number
  - nationality
  - age
  - position

- notifications:
  - player_id
  - message


### there should be a task that is responsible for fetching information regarding players and updating them on DB
- take into consideration this APIs response simulation: (Players) [https://tbem.github.io/players-json/data/players.json]
  
### there should be a task responsible for deleting notifications older then one week


## Bonus
- Sorting on player's listing based on position, nationality or age
- Players listing pagination 
- Endpoints documentation


## Expectations:

- Good testing coverage
- Well documented code
- Good design options
- How to install and run the code

Ideally the stack on the challenge should be similar to the one used on Realfevr ou feel morebut some other options are also going to be accepted (feel free to use what you feel more comfortable with).
- Ruby
- React
- Sidekiq / Resque
- JSON    

> pro tips: 
>- Don't waste to much time on the layout and on the testing part of the frontend
>- The notifications could be sent with some mock emailer









