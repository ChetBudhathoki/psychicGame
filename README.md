# psychicGame
Psychic Game Assignment

computer randomly chooses letter
computer stores the letter
user presses a key
if user key matches computer letter, user wins
if user key does not match computer letter, user loses a chance
we need to set number of user chances
if user runs out of chances, user loses

VARIABLES
* letters that user can pick/type
* wins
* losses
* chances
* computer choice
* user guesses (user letters)

FUNCTIONS
* generate computer guess (random letter)
  * pick from letters the user can pick
* onkeyup function
* check user guess
  * user key vs computer guess
  * if/else statement

* "win scenario"
  * user guess === computer guess
  * increase win count
  * display the win

* user doesn't guess correctly
  * user guess !== computer guess
  * decrease chances

* "lose scenario"
  * chances = 0
  * display the loss
  
* reset the game
  * reset the chances
  * clear user guesses
  * generate new letter to guess
