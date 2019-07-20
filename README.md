# psychicGame
Psychic Game Assignment

Computer randomly chooses letter
Computer stores the letter
User presses a key at a time
If user key matches computer letter, user wins
If user key does not match with computer letter, user chance decriment
Set number of user chances
When user runs out of chances, user loses
Game will reset

VARIABLES
* letters that user can pick/type
* wins
* losses
* chances
* computer choice
* user guesses (user letters)

FUNCTIONS
* generate computer guess (random letter)
* pick from letters that user can pick
* onkeyup function
* check user guess
  * compare user guess vs computer choice
  * if/else statement

* "win scenario"
  * user guess === computer guess
  * increase win count
  * display the win
  * reset the game

* user doesn't guess correctly
  * user guess !== computer guess
  * decrease chances

* "lose scenario"
  * chances = 0
  * display the loss
  * reset the game
  
* reset the game
  * reset the chances
  * clear user guesses
  * generate new letter to guess
