# Dice-Game
A dice game created for a project in an optimization methods in finance class

The objective of the game is to reach 100 points before your opponent. Each player takes turns rolling a die and after each roll, the player may choose to continue rolling or hold. As you are rolling the die you accumulate points for that particular round and you may choose to roll as many times as you wish until you decide to hold or roll a 1. If you roll a 1 you lose all the points you've accumulated for that round except for 1 point (and that point is added to your score) and the die is given to your opponent. When a player chooses to hold, they keep all the points accumulated in the round and then give the die to their opponent. 

The program calculates an optimal way to play the game using a bellman equation. The calculated U matrix is a decision matrix with the value of 1 of holding and 2 of of rolling. Matrix V is the value matrix.

