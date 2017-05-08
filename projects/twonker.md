---
layout: project
type: project
image: images/twonkericon.png
title: Twonker
permalink: projects/twonker
date: 2016
labels:
  - Java
  - Derby
  - SQL
  - JPages
summary: A recreation of Twitter, using the Derby database and JPages.
---

<img class="ui large rounded image center floated" src="../images/twonker1.png">

# Twonker

## Project Goal
The goal of the "Twonker" project was to emulate some of the functionality of the website <a href="http://www.twitter.com/">Twitter.com</a>. 
The project was back end focussed, with front end acting as a high fidelity prototype. The main goal of this project was to gain a functional understanding of SQL based databases, with a side goal to gain a better understanding of real life website development and management. Some emphasis was also put on utalizing the database to it's greatest extent. This includes using its atomic properties. 


## Skills Used
  The main resources used were:
  * Java
  * JPages 
  * Derby (An SQL based database)
  * NetBeans
  
## End Product
  The end product was a functional website, which implemented many of the features prevelant in twitter. 
 
  #### Features
  **Log In**. The log in system worked primarily by creating and reading entries in a single user table. The schema of the table was set up to contain only two elements: UserID and Password. The UserID was a unique integer that was generated randomly during the entries creation. This was to ensure there would be fewer collisions in the database. If the number was taken, it would be re-generated. The number was randomized, because if it wasn't collisions could reoccur in sequence. 
  
  **Tweets**




  

Twonker is a web application that I created in ICS 321, Fall 2016. The project helped me learn how to design web pages with a database structured back end. 

Twonker is implemented using JPages and Derby, a SQL database. The project took a week of work, and includes tweeting, hashtags search and creation, account creation, and logins.

In this project I gained experience with SQL and database backed web programming. This includes: JPages to design Web2.0 pages and Derby for data storage.
