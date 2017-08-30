---
layout: project
type: project
image: images/minesweeper.png
title: Minesweeper Game
permalink: projects/minesweeper
date: 2017
labels:
  - GUI
  - Java
summary: My team developed a Mine Sweeper game for a class project
---

<img class="ui medium right floated rounded image" src="/images/micromouse-robot.png">

For the final project for ICS 211 class, me and two classmates have to form a group to create a minesweeper game using java language. The minesweeper game is a computer game where you are given a grid of boxes where the goal is to "sweep" the entire grid for mines. When you left click on a box on the grid it will either give you a blank, a number corresponding to how many mines the box is touching, and or a mine. If you click on a box with a mine it means game over. The point of this game is correctly guess where the mines are and flagging them given the clues from the previously revealed boxes which have either blanks or numbers.

For this project, I was the lead programmer who was responsible for programming how the game operates. I was essentially responsible for the gameplay. I started with how create a grid of boxes by using buttons in java's api. After that I started to create the buttons themselves.Since I had to randomize where the mines were and how many mines were touching a particular box, this was rather hard because I had to check which boxes were touching which. Then I came up with using a 2D array to create the grid in which each boxes had a row and column number corresponding to it. This made it easier to check which boxes were touching. This also made it easy to check the boxes that were located diagonally of a particular box. My teammate had to do most of the GUI's since I particular had a hard grasping with using Java GUI. That is one thing that I want to improve on next time.

You can learn more at the [UH Micromouse Website](http://www-ee.eng.hawaii.edu/~mmouse/about.html).



