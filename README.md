# Rock Paper Scissors Game (by Luke Hickson)
<hr>

Rock Paper Scissors , Traditionally a Hand Game which is played by 2 people. This Game is often used by 2 persons to make a decision when there are confilcating opinions.
Similar to flipping to coin , a decision can easily and quickly be decided. This website was created to allow user to have online access to the Rock Paper Scissors game.
Access to the game You can viewed the [Live Website Here](https://hluke93.github.io/ms2/).

![Homepage Demostration on Desktop devices](./assets/images/desktopview.png)

# Rules of the Game (Historically)


The players count aloud to three, or speak the name of the game (e.g. "Rock! Paper! Scissors!"), either raising one hand in a fist and swinging it down with each syllable or holding it behind their back. They then "throw" by extending it towards their opponent. Variations include a version where players throw immediately on the third count (thus throwing on the count of "Scissors!"), or a version where they shake their hands three times before "throwing".

# Features


## Existing Features

* **Logo**

The Logo is Located in the top left of the page. The Logo states the name of the game "Rock Paper Scissors".<br>
The 2 main colors used in the logo are #24C6DC, #514A9D.<br>
This also indicates to the user what the game being played is.<br>

![Main Logo](./assets/images/logo.png)

* **The Main Game Area**

The main game area consists of the User and Computer Score and the 3 game options (Rock, Paper, Scissors). <br>
The 2 main colors #24C6DC, #514A9D are used in the user and computer score , and buttons. <br>

![Score Area and Buttons](./assets/images/choice.png)


* **Game Rules**

The Game Rules are displayed below the main game area. This explains how rock paper scissors is played and the objective which is first to score 5. <br>

![Game Rules](./assets/images/gamerules.png)


# How the game works and is played

* The user starts be selecting one of the 3 options (Rock, Paper or Scissors).
* Once the user selection is made, the javascript code generates a random  option for the computer choice , compares the user and computer choice , and incremenets the score by 1 , depending on the winner.
* A message appears under the buttons after each score which clearly states the user choice and computer choice , and a result messages <br>

![User Win](./assets/images/usercorrectchoice.png) 

* Once the user or computer reachs a score of 5 , the game is over , a winning or loosing message is displayed onscreen, and there is an option to play again by selecting the play again button <br>

![Play again win](./assets/images/playagain.png) ![Play again lose](./assets/images/playagainlose.png)


# Testing

* Testing was completed on the following browsers.<br>
Google Chrome <br>
Microsfot Eddge <br>
Firefox <br>
Safari

* Testing on all 4 brownsers yielded the same results.

* Lighthouse in Dev Tools was run on this webpage to check accessibility and performace. <br>

![Lighthouse results](./assets/images/lighthouse.png)

