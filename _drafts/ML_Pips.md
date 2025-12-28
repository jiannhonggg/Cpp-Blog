---
layout: post 
title: "Solving Pips with Machine Learning"
date: 2025-12-28 10:00:00 +0800
category: [Machine Learning]
tags: [Machine Learning, Fun, Games] 
published: True
toc: true #(Optional: false to hide the Table of Contents)
---
Pips is a New York Times Game. I have been playing it with my girlfriend for the past few weeks. Our average time spent on solving a Hard Puzzle is 10-20 mins. Try it out yourself here: <http://nytimes.com/games/pips>. Which led to her suggesting that I should code up a solver for this game. Below goes through the game in some detail and a detailed approach of how I approached the problem. The code is publicly available on github.

### Description from New York Times Website:
A visual logic puzzle where players arrange a set of dominoes to fill a game board. The goal is to complete the puzzle by ensuring all conditions on the board are met,conditions will be different every game. There’s no losing, only completing the puzzle. Players can continue to try until they solve the puzzle.

Color regions have conditions attached to their bottom right that the dominos must fulfill.  

### Region conditions can include: 
- **\=** : The domino dots in the region are the same number.
- **≠** : The domino dots in the region are not equal.
- **\>** : The domino dots in the region are greater than the number next to the symbol.
- **<** : The domino dots in the region are less than the number next to the symbol.
- A number: The domino dots in the region must add up to that specific number.
- Empty/blank: Some regions have no conditions.

When all conditions are met and all dominoes are placed correctly, the task is completed. 

### Breaking down the problem

### Approaches

### Final thoughts