---
layout: post
author: Rob Samoraj
tags: [data structures, c++, bitmap, cmake, algorithms]
---

This was a really cool project from _Mazes for Programmers_ by Jamis Buck. I made this over winter break after finishing CSCI 340 (Data Structures and Algorithms) and my discrete math course. And this is just a great project for the things I learned in there. 

So the project started with making a maze in the terminal, using Binary Tree and Sidewinder algorithms to generate mazes of different sizes based on input. You can see the ASCII version of this below.

![ascii maze](assets/images/mazes_project/mazes_terminal.png)

This was great, but I had put a lot (a LOT!) of time and effort into structuring this project to use Google Test and CMake, which I had only used a few times before. And I wanted to include an external library to create something more visually interesting than terminal ASCII art, though I personally would be more than happy if everything was just a terminal screen.

Anyway I found this really header-only bitmapy library that was simple to use and easy to incorporate into the project even though I hadn't thought about it ahead of time (thanks CMake). This developer has some other [really cool programs](https://www.partow.net/programming/index.html) on his site, check them out.

It didn't take that long to link the library and have it do my bidding to make a very basic bitmap of the same maze in the terminal. You can compare them.

![maze bitmap](assets/images/mazes_project/mazes_bitmap.png)

The next part I would make on this would be the maze solving algorithm which would probably use Djikstra's. You can look at this project on Github [here](https://github.com/Yarpirates20/mazes)