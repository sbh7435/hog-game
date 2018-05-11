# hog-game
Hog is a game of 2 players. On each turn, current player chooses the number of dice (upto 10) to roll. The player who reaches the goal score (can be decided) first, wins the game.



## There are 3 rules for playing this game

1- If the outcome on any number (atleast 1 dice) of dice is 1, then the score for that turn is 1.

2- If the person chooses to roll 0 dice, then the outcome of that turn is 2 more than than absulute difference between the digits of the opponent's current score.

3- After the score of turn has been added to the total score of the player, if opponent's score is divisible by current score or vice-versa, then the scores are swapped (i.e. opponent's score = current player score and current player score = opponent score).
