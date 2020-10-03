# Kaggle Halite Submission
 Top 1% Game-AI submission for Kaggle's Halite contest powered by Two Sigma.

## About the Contest:
Halite by Two Sigma ("Halite") is a resource management game where you build and control a small armada of ships. Your algorithms determine their movements to collect halite, a luminous energy source. The most halite at the end of the match wins, but it's up to you to figure out how to make effective and efficient moves. You control your fleet, build new ships, create shipyards, and mine the regenerating halite on the game board. 

<p align="center">
  <img  src="https://www.googleapis.com/download/storage/v1/b/kaggle-user-content/o/inbox%2F3258%2F73a73a0b4a807a7a9e674a40c55f7396%2Fhalite.gif?generation=1594994852379393&alt=media">
</p> 

<p style='text-align: justify;'>
 Created by Two Sigma in 2016, more than 15,000 people around the world have participated in a Halite challenge. Players apply advanced algorithms in a dynamic, open source game setting. The strategic depth and immersive, interactive nature of Halite games make each challenge a unique learning environment. Halite IV builds on the core game design of Halite III with a number of key changes that shift the focus of the game towards tighter competition on a smaller board. New game features include regenerating halite, shipyard creation, no more ship movement costs, and stealing halite from other players!
 </p> 
 
## Basic Strategies:
The most straightforward way to get started with Halite is to write a bot that can convert your starting ship into a shipyard, spawn a new ship, and then travel out to collect nearby halite and return it. From there the next step is to control a group of ships (and prevent them colliding into each other). 

After you get the basics down you should think about what other creative ideas you want to program. Some ideas to get you started:

* An aggressive bot that steals from other players or tries to eliminate them from the game
* Defensive strategies to hold off enemy attacks
* Efficiently controlling the board with shipyards
* Protect high yield halite patches near your shipyard from enemies and mine them efficiently to maximize halite regeneration over the course of the game
* Ganging up on whoever is in the lead


## Final Standings:
![Contest standings](https://github.com/manncodes/Kaggle-Halite-Submission/blob/main/leaderboard.JPG?raw=true)

## References:
* https://arxiv.org/abs/1905.11946 (EfficientNet)
* https://arxiv.org/abs/1905.02244 (MobileNet v3)
* https://github.com/lukemelas/EfficientNet-PyTorch (Implementation of EfficentNet in PyTorch Library)
