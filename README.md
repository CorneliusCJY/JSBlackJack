# JSBlackJack
A command line blackjack game, with all features from classic blackjack for the whole family!


# Instructions:
The rules are simple, the play is thrilling and you can use all the strategies you want! 
It doesn't matter if you've never played before, or if you are here for a mathematical 
challenge. This is a game for everyone.
The most widely played casino banking game in the world, Blackjack players do not 
compete against each other. 
The game is a comparing card game where each player competes against the dealer.

It is a card deck object and shuffle it and store it at a global state
It will ask how many players are playing (max. 4) and initialize the number of player objects
and ask each player's name and the betting amount and store them in the player object
Once all players are initialized, can begin to play. Deal 2 cards to each player and the dealer.
    a. one of the dealer cards is not shown
And the beginning from player 1 adds up the sum at hand and stores it
    a. use global states to control which player is playing at the moment (for DOM control)
    b. jack/queen/king is 10 and aces is 1 or 11.
At the beginning from player 1, display hand and score
    a. if the player has blackjack and the dealer is not a blackjack, the player wins automatically, 
        get paid 3:2 and the player will reset and wait for the next round.
    b. else, allow the player to choose hit or stand or /split (if in pairs)/ 
    or double or quit (lose the bet and stop playing)
      i. if hit and bust, lose the bet and wait for the next round
      ii. else hit until the player stands and waits for the next round
     else save the score and move to the next player and repeat a-b.
The dealer sees if the total card score is equal to or above 17, if not draw until it is above 17 and stop
    a. if bust, award bet to nonbusted players
    b. else, compare score and award bet to nonbusted players with higher score
    c. else,
Restart hand and repeat steps 4 - 6 until deck. length is less than 26 and reshuffle and repeats step 4-6.
Also, include the quit function to restart the whole game

# Technologies
JavaScript, HTML


# Sources
Learn from https://www.thatsoftwaredude.com/content/6417/how-to-code-blackjack-using-javascript ;
https://hackernoon.com/blackjack-application-with-javascript-2c76db51dea7 ;
https://codereview.stackexchange.com/questions/190366/javascript-blackjack-game;
Https://www.w3.org; https://code.google.com/archive/p/vector-playing-cards/downloads (images for the playing cards)



