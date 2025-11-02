---
layout: post
title:  "Brinkmanship"
summary: "Audio Pipeline Engineer"
date:   2024-05-06 15:39:40
preview: /assets/brinkmanshipkeyart.png
---

<center>
<iframe
    width="800"
    height="450"
    src="https://www.youtube.com/embed/BGSEGfEPpyY?si=rOgC-EhINqu5gbA5"
    frameborder="0"
    allow="autoplay; encrypted-media"
    allowfullscreen
    referrerpolicy="strict-origin-when-cross-origin"
>
</iframe>
</center>

[Brinkmanship](https://store.steampowered.com/app/2858410/Brinkmanship/) is a first person sci-fi mystery about greed, manipulation, and trust. As a spaceborne colonist 20 years into your voyage you’ve just discovered that your ship has secretly altered its heading. Your parents give you a gun. The ship goes into lockdown. What do you do? Who will you trust?

***

### For this project I created custom tools to:
* Turn our YarnSpinner database into a spreadsheet to track voice over recording and implementation process
* Generate tab-delimited files to facilitate easy importing of voice over into Wwise
* Automate implementation of 1900+ lines of voice over into the game

***

## The Process

As each script was locked, the YarnSpinner file was turned into a spreadsheet. This allowed for easier recording and tracking of the voice over.

![Spreadsheet tracking the status of voice lines](/assets/brinkspreadsheet.png)

After recording was completed and final voice over was delivered, tab-delimited files were generated for each act of the game. These files allowed the voice to be automatically imported into the project with proper naming conventions to allow a script run by YarnSpinner to play the correct voice over. As soon as voice over was importing into Wwise using the tab-delimited files, it was available to be heard in game. This process took about one hour total for the about 1100 lines of voice over included in the game in its initial launch.

![Tab-Delimited File](/assets/brinktlv.png)

With the voice over imported into Wwise, mixing and adjustments were made, helped by the predefined structure the tab-delimited files created, automatically creating busses for individual characters and mixer groups for each conversation. This process also allowed for an additional 900 to be easily added after launch.

![View of the Wwise project](/assets/brinkwwise.png)