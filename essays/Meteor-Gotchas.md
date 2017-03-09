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

Anyone who has used a framework to build a website knows exactly how easy it is, anyone who has ever used two frameworks to build two seperate websites knows how difficult it is. Frameworks are essential in our web 2.0 world.
## First Impressions

I began my foray into Javascript by brushing up on the basics using [FreeCodeCamp](https://www.freecodecamp.com/), a website that teaches Javascript in tiny little bite size lessons. After completing several hundred lessons, I feel as if my assessment of Javascript has come to a steady state. 

Javascript is incredibly versatile to a fault. The most notable feature is the ability to change what data type each variable corresponds to. I, as well as many others, would consider this to be neat but ultimately detrimental, thats why I intend to keep data types static for the rest of my time using Javascript. This translates over to arrays which strike me closer to JSON or some data storage language rather than an actual programming language. While the lack of restriction can be a benefit, it personally makes it hard to tell the function of an array just by looking at it. 

I wasn't fond of the way object oriented programming was implemented into javascript at first but the more i played with it the more it felt reminiscent of C. I don't want to say it is limited, as structs are in C, but rather the array like structure has a similiar feel. One thing I found dissapointing was a distinct lack of inheritance. I also question the usefulness of private variables in a setting like this. 

One small feature I truly enjoyed, although I question its usability and speed, is the ability to use words or strings as variable names which are interchangable with array positions. This made it incredibly easy to find properties. This could also situationally be used to translate into certain programs almost as spoken, like contacts. It is a shame that largr datasets are probably not usable in Javascript.

## Euler Problems

In order to truly understand the usefulness of Javascript I took on the first couple of Euler problems. 

### Euler Problem 1

 This first Euler problem is adding all of the numbers between 0 and 1000 that are divisible by 3 or 5. This was particularly easy to implement in Javascript. The syntax was very similar to c, set asside the function and and distince lack of a main function. While it wasn't strictly necessary I decided to use the === operator. 
 
 In total this took only 1 Minute and 26 seconds to perform and was correct on the first attempt. My solution can be found [Here on JSFiddle](https://jsfiddle.net/jleech/7akb1hue/)

### Euler Problem 2

The second Euler problem is to add all of the Fibonacci numbers up that are even. This problem showed one of Javascripts biggest weaknesses. My initial solution was to try and perform the problem recursibely, this quickly showed to be too slow and require to much memory. This solution was created in 4 minutes and proved to be correct using a faster programming language.

The second attempt of this problem used an interative step which could be almost indistinguishable from any other language. This worked speedily, and the solution was found in 2 minutes and 10 seconds.

The final solution to this problem can be found [Here on JSFiddle](https://jsfiddle.net/jleech/ytbwu25L/)


