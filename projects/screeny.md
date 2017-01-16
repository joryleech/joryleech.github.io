---
layout: project
type: project
image: images/screenyicon.bmp
title: Screeny
permalink: projects/Screeny
date: 2014
labels:
  - Utility
  - Java
summary: Developed a utility/replacement for the Windows screenshot feature. 
---

<div class="ui large rounded images">
  <img class="ui image" src="../images/screeny2.png">
</div>
<img class="ui medium image" style="float:right;" src="../images/Screeny1.png">
Screeny is a utility designed to replace the Windows screenshot feature. This application was inspired by the macintosh screenshot utility, however it was desired to be less obtrusive. The utility performs its function by hooking itself to the key events in the operating system. This was necessary due to javas restriction on acknowledging key events if the window is not focused. Upon recieving a key notification from the print screen key, the program saves a picture of the current screen to a user determined file.

For this project, I was the sole developer and programmer. I was responsible for programming the entirety of the functionality, except for the keyboard hook. The keyboard hook was implemented as a library and developed by khwat on github. I personally developed the UI and screenshot capabilities of the application. The end product is an unobturusive utility that performs its function quickly.

More information on JNativeHook can be found: [Here](https://github.com/kwhat/jnativehook).


