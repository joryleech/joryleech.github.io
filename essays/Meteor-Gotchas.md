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

## Errors, Or Lack There Of

Coming out of a java based framework I had some expectations for the way meteor was going to work. I was quickly able to shatter these expectations but one thing never quite sat right with me. I had the hardest time trying to figure out how to fix errors. Meteor does its best to try and stack trace a little bit to the part of code that the problem originated in, but there are a few distinct problems with its approach. The first and arguably biggest problem with meteors approach is the multiple levels of abstraction are not shown to the user during development but are shown during error messages. This is not a problem specific to Meteor and I would say it is a problem with Java as well, but most of the time meteor will not actually give an place in the code where the error happened. This puts much burden on the user to attempt to see where the problem occured.

I don't want to give the impression that pulling away the layers of abstraction is a bad thing. There are multiple merits to it including giving a more detailed responce to a problem. This approach can be particularly helpful for those who have a deep understanding of the back end of meteor. Sadly I do not yet and found a wide gap of information between what I was given and what i want to know. 

All that being said, it can be near impossible to find a spelling error within the program. This is a major problem when you have to link nearly every package with eachother hopefully without a single typo in order for it to work.

## More options, Worse Options

Meteor is occasionally awesome, simply put there seems to be a massive ammount of options for nearly anything. This could be the "First time using a new thing" goggles talking but I am always a little giddy when I find something new and neat about meteor. That being said I have a hard time understanding the meaning of ways to get to certain options. To be blunt there are things I often have to look up there doesn't appear to be anyway to do it intuitively. To better display this I'd like to pose a couple of examples. 

### Package / Import / Recode

Say I wanted to my code, a feature of somewebsite that might be necessary. For this instance lets say I want to add a shopping cart. How would I go about that in meteor. The answer to that is... I don't know. There are few options at my disposal and I'm sure one of them could get me there but they all do similiar things but in awful ways. The first way is to check if a package is available, this would be added in the command promt and then programmed in in a line of code somewhere, but alternatively it could already be a package previously imported. There appear to be a lot of different default packages that work in strange way. Perhaps all I need to do is import it through the code like Mongo. Lastly the option is to code up a page to act as a shopping cart for me. All of these are totally viable options and I don't often know which one is the right one.

### Javascript / HTML / Template / HTML Javascript

There are a lot of ways to get code into a page. Should I write it in the java script and call it, should i write a template? I often have no idea what the difference between these methods is, and I can't imagine they are all the same. This compounds with the helpers, the on create, and other function types. Sometimes they are self-explanatory but often they seem like they might do the same thing.


## Final Words

I've had a few problems besides these in meteor but none of them felt like they were that big. A simple bug is a simple bug regardless of language. I 