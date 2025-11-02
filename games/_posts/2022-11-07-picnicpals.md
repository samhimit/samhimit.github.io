---
layout: post
title:  "Picnic Pals!"
summary: "Gameplay Engineer"
date:   2023-12-01 15:39:40
preview: /assets/picnicpreview.png
---

<center>
<iframe
    width="800"
    height="450"
    src="https://www.youtube.com/embed/TuSjUX9L3v8?si=dF568wfUr1W2jdRH"
    frameborder="0"
    allow="autoplay; encrypted-media"
    allowfullscreen
    referrerpolicy="strict-origin-when-cross-origin"
>
</iframe>
</center>

[Picnic Pals!](https://samhi.itch.io/picnic-pals) is a 2D puzzle game where you control three bunnies. Utilize the *entire* keyboard to navigate obstacles and position your pals to solve geometric puzzles to collect all the carrots on screen in 39 unique levels.

***

### For this project I implemented:
* Unique controls mapping the keyboard to corresponding locations on the screen
* Various obstacles including worms, bouncers, and walls
* Collection system tracking which carrots and worms are within the collection area
* Level and Cutscene management


***

## A Movement System Using the Whole Keyboard

Picnic Pals! maps the entire keyboard to the screen, when the player presses a key, the selected bunny moves to the corresponding spot on screen. To do this the list of all inputs are stored in an array and based off the index of the array and the size of the screen the location can be calculated. The player manuevers all three bunnies to attempt to get all the carrots (and none of the worms) inside of their net.

<center>
<iframe
    width="800"
    height="450"
    src="https://www.youtube.com/embed/QONUQoeGiEg?si=4KWzb2RS-o3awDYk"
    frameborder="0"
    allow="autoplay; encrypted-media"
    allowfullscreen
    referrerpolicy="strict-origin-when-cross-origin"
>
</iframe>
</center>