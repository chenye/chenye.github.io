---
layout: post
title:  "Conway's game of life"
excerpt: "A javascript + D3.js implementation of conway's game of life"
date:   2016-06-06 00:00:02
categories: projects
tags: [projects, conway, game of life]
---
This is a small project for the purpose of learning d3.js. Conway's game of life is a simple simulation on a 2D grid which can demonstrate a rich dynamics. Each grid point (or cell) has a status of live or dead. There are four intuitive rules to update the status of each cell:

* Lonely cells will die. (Fewer than two live neighboring cells.)
* Crowded cells will die. (More than three live neighbors.)
* Other cells will live on to the next generation.
* Dead cell will become alive if there are exactly three neighbors.

The following is a simulation starting from a random initial state. I did not find a good way to include d3.js into Jekyll blog after spending a few hours. So please go to [this link](http://www.sugarscape.net/game-of-life-web/) if the following does not work smoothly.
<iframe src="http://www.sugarscape.net/game-of-life-web/index.html" width="100%" height = "600px" frameborder="0">

