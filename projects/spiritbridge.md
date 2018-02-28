---
layout: project
type: project
image: images/SpiritBridgeIcon.png
title: Spirit Bridge
permalink: projects/SpiritBridge
date: 20171212
labels:
  - Game
  - Unity
  - Blender
  - C++
summary: A Platformer/Friendship-Sim about a Child Stuck in the Spirit World
---

[This project has an Official Page Here](http://hibernationstudios.x10host.com/)

<center> <iframe width="560" height="315" src="https://www.youtube.com/embed/-0131KbrKWc?rel=0" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe></center>
  
## Project Goal

The goal of this project was to iterate on the previous version of JEngine, while also reaping the benefits of controlled memory system.

The first version of JEngine was performed using Java and AWT. Because of this it became very difficult to control the memory being used in the program. This meant it was fine for smaller projects, but larger projects had issues running. Furthermore, as far as I could tell there was no hardware acceleration. 
These two issues forced the entity cap to hover around 14000 on my current hardware. The new system boosts this to almost 10x that amount. 

## Skills Used

The main resources used were:
* Unity 
* C#
* Audacity
* Blender

## Personal Involvement

I was the lead programmer in charge of a team of one other programmer, and 3 artists. As a team lead I was responsible for scheduling members, maintaining expectations, and bridging the gap of understanding between artists and programmers.

As a developer I was in charge of: The character controller, the dialog system, converting stories from the artists to the program, and maintaining our source code control. 

I also create the 3d Mesh for the town using blender, and it was textured by the art students. 

## Dialog System. 

  The dialog system was designed to be modular, and can be seperated into three seperate segments. 
  
  1. The UI.
  2. The Sentance Structure
  3. The Background and Bridge Code
  
  ### The UI
  
  The UI was structured by hand to try and follow the conventions of normal dating sim conversation areas. This part is mostly trial and error to get everything right, but the heirchy used can give you an idea of the aspects that were needed. 
  The main conversation object holds all of the scripts that are necessary to run the conversation. The eventsystem is required for input to work. In our game the left character and the right character were two separate object, but I would recommend another empty object with ~5 characters to fit each situation. These can be moved and manipulated by the scripting later on. 
The conversation holding area holds each sentence which will be described in the sentence structure segment.

Each object that ends in the name area {conversationArea, 2QuestionArea, etc...} are the different types of inputs or outputs that are available for the conversation. The "conversationArea" is used for normal sentences where the objects inside are a text object, and an image for a moving arrow. The question areas work similarly with Unity UI buttons instead of just text.
Most of the other objects mentioned are just images, that should be anchored around the entirety of the screen so that they stretch correctly, or to the bottom of the screen if you would like them to not stretch.

  ### The Sentance Structure

I decided to go for a node based system for the conversations, if you are familiar with linked lists it is similar to that. Each time text appears on the screen it is referred to as a "Sentance", with a sentance class that exists and several other classes that extend it. This includes different sentence types for regular sentences and each type of question.

Each sentence connects to another sentence, normal sentences connect to one, while questions connect to multiple. This allows the user to create scripts in trees, that can be easily converted to this system. 

 The scripts should be so that anything that can be different in any screen should be changeable through these sentence scripts. 

**Entity Based**. All images, rectangles, text, or other things that might need to be rendered are considered Entities. This entity class gives each object a position, scale, and several other functions that can be used across any of the subclasses.

  <img class="" style="float:right;max-width:75px;" src="../images/jengine2/rectprim.png">

  **Geometry Rendering**. This allows the user to render simple geometry. The back end of this is actually 3D OpenGl. This allows the application to take full control of Hardware accelerated floating point calculations offered by any GPU.
  
  <img class="" style="float:right;max-width:200px;" src="../images/jengine2/spriterender.png">
  
  **Image Rendering**. This allows the developer to render images to the any render surface. This should take care of importing any images, and rendering them to the screen. This is handled as an OpenGL texture and a 3d plane, to once again take advantage of Hardware acceleration.

  
  
<img class="" style="float:right;max-width:300px;" src="../images/jengine2/multiplerendersurf.png">
  
  **Multiple Render Surfaces**. This function allows the user to render onto another surface, besides the generic window surface. This function can be used to: 
  * Clip Images
  * Create a  layered effect for images
  * Offer the user multiple distinct windows.
  
  **Input Manager**. This input manager gives the user access to any of the inputs from the user that they requrst during any part of the application. This was designed to solve a common problem in input managment, that causes information to be lost once it is collected, or that restricts input dependant actions to take place in a single function.
   
## Screenshots


## Art
