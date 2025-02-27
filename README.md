# Unity Web Build Tutorial

## By: Cole Dorman

### Designed for Unity version 2022.3.31f1


# Table of Contents

1. [Summary](#summary)
2. [Building your game](#building-your-game)  
   1. [Outcome](#build-outcome)
3. [Embedding your game into a webpage](#embedding-your-game-into-a-webpage)  
   1. [Outcome](#embed-outcome)
4. [Faq](#faq)


## Summary

This repository provides a step-by-step guide to building, configuring, and deploying Unity projects as web builds.
This guide will assume you have basic unity knowledge and a game built and will include detailed instructions, with images to guide you through delivering Unity
games or applications to a web platforms.

# Building your game

## Build Outcome

By the end of this guide you will have a html build locally of your game in web assembly.

## Part 1 - Environment Setup

Firstly ensure the correct Unity modules are installed. You can install the needed packages from Unity
hub, as shown with the red arrow below. Just click on the settings icon.

![img.png](Images/img.png)

Select add modules.

![img_1.png](Images/img_1.png)

Scroll down until you find WebGL. In this image it is installed, but you will have a little
checkbox to the left as shown in the image below.

## Part 2 - Changing Platforms

![img_2.png](Images/img_2.png)

Launch your project, once your project opens go to file and then build settings

![img_3.png](Images/img_3.png)

Switch platforms with the highlighted option WebGL, then click the bottom right "switch
platform" button

![img_5.png](Images/img_5.png)

## Part 3 Building the game

Go to player settings.

![img_4.png](Images/img_4.png)

Once in player settings go to the Player category then put in the canvas width and height you designed your viewport
around

![img_6.png](Images/img_6.png)

Once this is set then we can go ahead and go back to the project settings window. But before we do anything else,
make SURE all the scenes that are part of your game are added to the list. As shown below you can use Add open
scenes, also ensure the checkboxes are checked before building.

![img_8.png](Images/img_7.png)

Then click build and run. Shortly once it builds you will have a web build that will pop up once it compiles!

![img_7.png](Images/img_8.png)

---

# Embedding your game into a webpage

## Embed Outcome

By the end of this section of the guide you will have a working embedded game on your webpage that can is handled in an Iframe.

# Part 1

# Part 2


# Faq
