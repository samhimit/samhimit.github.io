---
layout: post
title:  "3D Printed Paintings"
summary: "Personal Project"
date:   2022-10-07 15:39:40
preview: /assets/paintingpreview.png
---

<center>
<iframe
    width="800"
    height="450"
    src="https://www.youtube.com/embed/tWOLfInf2RU"
    frameborder="0"
    allow="autoplay; encrypted-media"
    allowfullscreen
>
</iframe>
</center>



3D Printed Paintings started in USC's chapter of [3D4E](3d4e.org) and continued as a personal project. It's primary goal is to transform 2D images into 3D models that can then printed. The source code can be found [here](https://github.com/samhimit/3d-printed-paintings)

***

## Process

To create a 3D model from a 2D image I employed [numpy-stl](https://pypi.org/project/numpy-stl/). The image is first converted into grayscale, then each pixel's grayscale value is mapped to the height of the point in the 3D model.

## Iteration

The initial program created 3D models that were spiky and difficult to print due to the possible high difference in grayscale values in a picture, along with each pixel only being assigned one point. The first solution to solve this issue was to apply a blur over the image before converting it into a model which made the images easier to print but lost detail and recognizability. The solution that produced the best reults was giving each pixel of the source image a face instead of a point. This makes the art much more recognizable and introduces a pixel art style that works really well with the Pokemon that were printed.

## Results

![3D Printed Pokemon](/assets/paintings.png)

Various Pokemon with pixel variation.

![Van Gogh Self Portrait](/assets/painting2.jpg)

Van Gogh portrait using a blur and other post processing mounted in a frame.

![Mona Lisa](/assets/painting3.jpg)

Initial test print with an early version of the program of the Mona Lisa.