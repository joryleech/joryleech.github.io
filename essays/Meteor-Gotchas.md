---
layout: essay
type: essay
title: "Meteor Gotchas"
date: 2017-03-09
labels:
  - Software Engineering
  - Meteor
---


## Preface

Anyone who has used a framework to build a website knows exactly how easy it is, anyone who has ever used two frameworks to build two seperate websites knows how difficult it is. Frameworks are essential in our web 2.0 world as static websites are often not able to function in the way we want them to. However, much like program languages these frameworks can't be perfect. Certain features have to be left in the dust due to development time, or conflict with other requirements of the program. This is okay but when someone works with more than one framework they can often become dissatisfied with the lacking of features from from either one.

Meteor was not my first framework, sadly, rather JPages was. To compound on this, I think I have a better understanding of Java than I do of javascript. Now it's important to note that the entire structure of meteor is far different from JPages. Because of this there are a few parts of meteor that i have yet to become aquainted with. 

##My First Problem

Coming out of a java based framework I had some expectations for the way meteor was going to work. I was quickly able to shatter these expectations but one thing never quite sat right with me. I had the hardest time trying to figure out how to fix errors. Meteor does its best to try and stack trace a little bit to the part of code that the problem originated in, but there are a few distinct problems with its approach. 


## Euler Problems

In order to truly understand the usefulness of Javascript I took on the first couple of Euler problems. 

### Euler Problem 1

 This first Euler problem is adding all of the numbers between 0 and 1000 that are divisible by 3 or 5. This was particularly easy to implement in Javascript. The syntax was very similar to c, set asside the function and and distince lack of a main function. While it wasn't strictly necessary I decided to use the === operator. 
 
 In total this took only 1 Minute and 26 seconds to perform and was correct on the first attempt. My solution can be found [Here on JSFiddle](https://jsfiddle.net/jleech/7akb1hue/)

### Euler Problem 2

The second Euler problem is to add all of the Fibonacci numbers up that are even. This problem showed one of Javascripts biggest weaknesses. My initial solution was to try and perform the problem recursibely, this quickly showed to be too slow and require to much memory. This solution was created in 4 minutes and proved to be correct using a faster programming language.

The second attempt of this problem used an interative step which could be almost indistinguishable from any other language. This worked speedily, and the solution was found in 2 minutes and 10 seconds.

The final solution to this problem can be found [Here on JSFiddle](https://jsfiddle.net/jleech/ytbwu25L/)


