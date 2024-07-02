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
>
</iframe>
</center>

[Picnic Pals!](https://samhi.itch.io/picnic-pals) is a 2D puzzle game where you control three bunnies. Utilize the *entire* keyboard to navigate obstacles and position your pals to solve geometric puzzles to collect all the carrots on screen in 39 unique levels.

***

### For this project I implemented:
* Piano-like movement sound system to support the use of the entire keyboard.
* Designed and implemented various obstacle interaction sounds (wall,bouncer,worms)
* Created hover and collections sounds


***

## Designing for 39 Inputs

Picnic Pals! utilizes the whole keyboard for its movement system so it was important to ensure that every key felt a little unique and different especially with the large amount of key presses throughout a level. Since playing the game feels a little like playing the piano or creating music I decided to mimic a piano with the controls of the game, each row of keys acts as a scale of notes. Utilizing Wwise's MIDI system I was essentially able to turn the keyboard into a MIDI controller to play a soundfont I created. The final result lets players drag their fingers across the keys and create something musical and responsive.

<center>
<iframe
    width="800"
    height="450"
    src="https://www.youtube.com/embed/CwEL0ppqVts?si=lUAW7q7AQgwsBrWU"
    frameborder="0"
    allow="autoplay; encrypted-media"
    allowfullscreen
>
</iframe>
</center>

## Hovering and Collection

As the player moves bunnies around the screen and objects enter their net carrots and worms have unique hover sounds. There is additional sound design to help communicate to the player when all carrots are inside the net, and the result of trying to collect.

<center>
<iframe
    width="800"
    height="450"
    src="https://www.youtube.com/embed/wXYfbhJKfko?si=DdzrZIniKadwMK7C"
    frameborder="0"
    allow="autoplay; encrypted-media"
    allowfullscreen
>
</iframe>
</center>