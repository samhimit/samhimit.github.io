---
layout: post
title:  "Cocktail Fusion"
summary: "Alt Ctrl Project"
date:   2024-04-02 15:39:40
preview: /assets/CocktailFusionSquare.png
---

<center>
<iframe
    width="800"
    height="450"
    src="https://www.youtube.com/embed/EVyPcJhkxUs?si=rkSscyibZqg409CR"
    frameborder="0"
    allow="autoplay; encrypted-media"
    allowfullscreen
>
</iframe>
</center>




Cocktail Fusion is an Alt Ctrl Mixology game! Fill a physical shaker with virtual liquids from a real tap to make a variety of colorful drinks. It's Tapper mixed with elementary school art!

***

![CF](/assets/cocktail.JPG)

I developed Cocktail Fusion as a capstone project at USC Games. The project combines Arduinos, 3D printing, and Unity to create a unique experience.

### The Build
I modeled, printed, and assemble the various parts of Cocktail Fusion in USC's Baum Family Makerspace. The full tap is 16 inches tall taking a total of 36 hours to print. The entire project is 3D printed except for the three real taps that are used for the player's input. Three Arduinos make up the core systems of Cocktail Fusion, one inside the tap controlling the NFC sensor and LEDs based off Hall sensors reading the state of the handles. Another Arduino within the "dispenser" which connects to the computer that runs the Unity game, and an Arduino Nano inside of the canister that tracks the state of the canister and controls the LEDs. The canister also includes a vibration sensor to track the player shaking the canister to mix the drink inside.

![CF](/assets/finaldemococktail.JPG)

![CF](/assets/shakercocktail.JPG)

![CF](/assets/cocktailold.JPG)

![CF](/assets/partscocktail.JPG)

### The Game
In Cocktail Fusion players are able to fill a canister with different colored virtual liquids. They can then shake the canister to mix the colors together to try to match a given order. To facilitate the communication between the tap, canister, and computer I utilized NFC sensors. These sensors allow wireless communication so that the canister is fully wireless object. Since Cocktail Fusion's use case of these sensors was unique needing to send and recieve information I created a simple protocol utilizing FeliCa IDs to allow the canister to pass data to the computer running the game and recieve a notification that the data was recieved. Quite comedically whenever I use my phone to check the status of the canister my phone attempts to pay with my metro card. 

![CF](/assets/nfccocktail.JPG)

![CF](/assets/outdoorcocktail.jpeg)
