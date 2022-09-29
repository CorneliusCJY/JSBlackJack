# Blackjack
A command line blackjack game, with all features from classic blackjack for the whole family!

![cards](img/cards.jpg?raw=true)

Photo by <a href="https://freeimages.com/photographer/vierdrie-46406">Jean Scheijen</a> from <a href="https://freeimages.com">FreeImages</a>

# Instructions:
The rules are simple, the play is thrilling and you can use all the strategies you want! 
It doesn't matter if you've never played before, or if you are here for a mathematical 
challenge. This is a game for everyone.
The most widely played casino banking game in the world, in Blackjack players do not 
compete against each other. 
The game is a comparing card game where each player competes against the dealer.

It is a card deck object and shuffle it and store it at global state
It will ask how many players are playing (max. 4) and initilize the number of player object
and ask each player name and betting amount and store in the player object
Once all players are initialize, can begin to play. Deal 2 cards to each players and the dealer.
    a. one of dealer card is not shown
And the beginning from player 1 adds up the sum at hand and store it
    a. use global states to control which player is playing at the moment (for DOM control)
    b. jack/queen/king is 10 and aces is 1 or 11.
In the begining from player 1, display hand and score
    a. if player has blackjack and dealer is not a blackjack, player win automatically, 
    get paid 3:2 and player will reset and wait for next round.
    b. else, allow the player to choose hit or stand or /split (if in pairs)/ 
    or double or quit (lose the bet and stop playing)
      i. if hit and bust, lose the bet and wait for next round
      ii. else hit until player stands and wait for next round
     else save the score and move to next player and repat a-b.
The dealer see if total card score is equal or above 17, if not draw until it is above 17 and stop
    a. if bust, award bet to non busted players
    b. else, compare score and award bet to non busted players with higher score
    c. else,
Restart hand and repeat step 4 - 6 until deck.length is less than 26 and reshuffle and repeat step 4-6.
Also include quit function to restart the whole game

# Technologies
JavaScript, HTML


# Sources
Learn from https://www.thatsoftwaredude.com/content/6417/how-to-code-blackjack-using-javascript ;
https://hackernoon.com/blackjack-application-with-javascript-2c76db51dea7 ;
https://codereview.stackexchange.com/questions/190366/javascript-blackjack-game;
Https://www.w3.org; https://code.google.com/archive/p/vector-playing-cards/downloads (images for the playing cards)



