---
layout: essay
type: essay
title: Why coding standards are important, and your preferences are bad.
date: 2017-02-09
labels:
  - Standards
  - Organization
  - Programming
---


## Preface

Every programmer knows the struggle of deciding between tabs and spaces despite it not mattering for most languages at a compiler level. However it seems like almost everyone's opinions on the matter are fairly strong. Is it worth it? Furthermore is it a symptom of a larger problem? Of course it is!

The tabs versus spaces argument is a small part of the larger scope of Coding Standards. Coding Standards are a system put in place to keep code standardized to a single format. It's important to note that these are put in place by developers not by the language themselves. Using spaces to denote blocks in Python is a quirk of the language, using spaces in C is an example of Coding Standards. It is also important to note that Coding Standards try to standardize a near infinite combination of coding preferences, not just white space. For an example see <a href="https://github.com/airbnb/javascript">AirBNB coding style</a>

To truly understand the importance of Coding Standards, we will look at a few examples, starting with a world where the tabs versus space debate doesn't exist.

### Example 1: Overlooked Imperfections

Imagine a world where you can show someone your code and the person who looks at it isn't immediately brought aback by one or more of your coding preferences. Whether you use tabs or spaces or never add a new line unless you use a different function, imagine no one cared.

For a personal project this could almost work, most novices code this way before they know someone else who programs and begin to have this debate. Imagine that style of formatting being randomly distributed to every single person you have ever looked at the code of and one last time lets assume that you don't judge them. The time alone it would take to read and try to comprehend the code that was put in front you would double, maybe triple. The amount of time this could steal in a company could cost millions. Productivity drops, there are less products to push, and honestly the bulk of the workload moves from trying to work on the problem to trying to understand what was already done to work on the issue. 


### Example 2 : Perfect People (Robots)
  
Now I would like you too imagine a world where everyone has the same coding standards, no matter what they are everyone's code for a single problem would look identical. Of course there isn't a good solution to all problems using the same coding standards but lets pretend. Imagine the amount of productivity that could be accomplished if everyone intrinsically could at least understand the formatting of a code before reading it. 

Of course people could never actually accomplish this because people are difficult and there is no black and white way to say which format is better. However, given the format of a problem and a limited set of people like what can be found in a company this goal becomes very easy to accomplish. 

## Conclusion

Why does this all matter you might ask yourself? The life of a programmer is to make tools that make life easier, so why not use a little of your own knowledge to make your own and others life easier. At the moment there are only a few ways that these Coding Standards can be implemented and they don't tend to be user friendly. It has been an uphill battle trying to implement nicely organized code, stemming from the mess of packed code in the seventies. But for our sake and the sake of everyone else, it will make our lives better. 
