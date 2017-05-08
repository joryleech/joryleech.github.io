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
  
## Personal Involvement
I was the sole developer and resource creator of this project.
  
## End Product
  The end product was a functional website, which implemented many of the features prevelant in twitter. 
 
  #### Features
  **Log In**. The log in system worked primarily by creating and reading entries in a single user table. The schema of the table was set up to contain only two elements: UserID and Password. The UserID was a unique integer that was generated randomly during the entries creation. This was to ensure there would be fewer collisions in the database. If the number was taken, it would be re-generated. The number was randomized, because if it wasn't collisions could reoccur in sequence. 
  
  **"Twonks" (I.E. Tweets).** Twonks were implmented as another seperate table. These twonks were stored with the content of their message, the date the message was created a unique id generated in the same way as the user id, and the user who created it. 

  **Hashtags**. These hashtags were created by parsing the string entered for any word that starts with the '#' character. One creation if one or more of these words was found, an entry would be created in a hashtag table. These entries contained the name of the hashtag, and the unique post ID to link them. This table was indexed by the hashtag. While this took more space, this was important to allow fast searching by these hashtags.
  
  **Feed.** A feed, in which all messages made are shown, these messages are seperated into pages, and are sorted by date made. This was considered important to allow the user to see the latest messages.
  
  **Search By Hashtag and User.** By clicking on any of the hashtags, the user could view all of the messages that have a certain hashtag. By clicking any of the users names you could accomplish the same thing but by that user. 
  
  
#### Video

<iframe  title="YouTube video player" width="960" height="600" src="https://www.youtube.com/embed/UiU5jrE6dew" frameborder="0" allowfullscreen></iframe>

#### Screenshots
<img class="ui large rounded image center floated" src="../images/twonker1.png">


