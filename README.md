# proposal
Click and Shoot Game
# Title
Shoot the Targets
## Repository
https://github.com/Chrischoi982/Final-Project

## Description
This is a click and shoot game where targets randomly appear on screen and players will have 60 seconds to shoot as many targets to score the highest possible points they can achieve. It’s relevant to media and digital arts because it allows people to interact with the game using mouse clicks and uses shapes, colors, and text to create the visual design. 

## Features
- Targets randomly spawning in different locations
	- Using the random import to generate random x and y coordinates of the targets
- Game ends when timer reaches 0
	- using if statements and booleans to end the game when the timer is less than or equal to 0.
- use a score system that gives 1 point every time a target is hit 
	- using if statements to increase the score by 1 and remove the target if the target gets.

## Challenges
- Going through the pygame library and learning how to make targets and make the game detect mouse clicks.
- Going through the random library to learn more about how to position the targets randomly.
- Learn how to make the targets disappear as soon as the target gets clicked on 

## Outcomes
Ideal Outcome:
- A click and shoot game that lasts for 1 minute with a countdown that displays the timer. Targets spawn randomly in different locations and disappear after 2 seconds or after it’s clicked by the player and grants 1 point if the target is hit and displays the current player score to keep track of the player score. The game ends after 1 minute and displays a game over screen, the player score, and the play again button.

Minimal Viable Outcome:
- Briefly describe the bare essential for a good working outcome?
The game window opens with targets spawning in different locations and will disappear after 2 seconds or the player clicks on it and grants 1 point if it’s clicked. The game ends after 60 seconds with the player score.


## Milestones

- Week 1
  1. Open the pygame window
  2. Create the targets and have them spawn randomly in random locations

- Week 2
  1. Make the targets disappear after 2 seconds or after it’s clicked on and grant 1 point if it’s clicked on
  2. Make the game end after 1 minute

- Week N (Final)
  1. Create a display that shows the countdown timer and the current player score
  2. Create the game over screen with the player score and the play again button.
