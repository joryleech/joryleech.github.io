---
layout: project
type: project
image: images/pathfinding/pathfindingLogo.png
title: Unity 2D: Pathfinding
permalink: projects/twonker
date: 2016
labels:
  - Unity
  - C#
  - A*
  - Game Development
summary: Integration of Pathfinding for Unity 2d:
---

## Project Goal
This project was developed to fill a gap that existed in Unity 2D's capabilities. Unity 3D has options that allow the user to easily place NavMesh in the game that allows entities to navigate it. This fills the same capabilities but in the 2D setting.

The problem for implementing this through unity assets was that all of unity's 2D assets act on a different plane than what the 3D navmensh moves on.

## Skills Used
  The main resources used were:
  * C#
  * Unity
  * A* pathfinding algorithm
  * Coroutines
  
## Personal Involvement
I was the sole developer and resource creator of this project.
  
## End Product
  The end product was a pathfiniding script that returns a list of vector positions for where the object should go.
 
 <h3> Features </h3>
  
  **Pathfinding** This algorithm uses A* to find the shortest path to get to the destination. 
  
  **NavMesh** (Optional) This allows users to create custom materials that the object can pathfind through. These are not required to function, but act as both a restriction for the algortithm, and also a way to restrict where the entity will move. 

  **Coroutines** (Optional). This allows the user to run the algorithm in a limited way, such that it may take longer than one frame to create the path, without expending aditional frame time. This cuts down on the effect of the algorithm to frame rate and is making it almost unnoticable asside from creating the coroutines.

  
## Video

<iframe  title="YouTube video player" width="960" height="600" src="https://www.youtube.com/embed/UiU5jrE6dew" frameborder="0" allowfullscreen></iframe>

## Screenshots
<img class="ui large rounded image center floated" src="../images/twonker1.png">


