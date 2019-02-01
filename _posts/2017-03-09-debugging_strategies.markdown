---
layout: post
title:  "Debugging strategies"
date:   2017-03-09 20:47:31 +0000
---


Ah, bugs. Aptly named, they sneak into our code unnoticed and, like a fly in the ointment or ants in one's pants, cause GREAT annoyance. 

I've been working in QA in the world of software for a little over a year, and during that time I have grown to have more and more respect, sometimes even fondness, for the debugging process. My progress with the Learn curriculum has also made a big difference here, because sometimes I feel like all I ever do is debug. But I've come to form some overall philosophies on debugging, which I'd like to share here. 

1. Learn first, code second. 

What does that have to do with debugging, you say? Bugs are commonly introduced into the code when you try to write a section of a program/app/whatever without first properly learning how to write that section. The more you change and the more parts of the code you touch, the higher chance that you will introduce bugs, so don't write a line of code if you can't explain exactly what it's doing and why it's there. 

2. Design second, code third. 

An amendment to rule #1 - after you know what you're doing, know what you're building. Sometimes "bugs," especially when they're not crashes but more subtle behavior issues, are not actually mistakes but just an error in alignment between two people's expectations. It's much easier to align expectations at the beginning of a project, before you start building, than to fix it later. (Think of the difficulty of even changing the name of one database column. It's so much easier to check the specs, and make sure you're using the right name in the first place, than to change it later.) 

3. Find the right tools

There are so many testing tools out there that can make life easier. Get familiar with the learn -b command to run jasmine tests in the browser, the node sandbox, Chrome inspector (console and network tabs), and the --fail-fast command to get more immediate feedback. There are so so many more things out there as well, so use them, and get comfortable with your debugging tools. 

4. Read the tests 

Write good tests, and if you have the benefit of having such thorough tests already written for you, read them!! The tests tell you what the program should do, so it's only logical to read them thoroughly. 

5. Iterate on small chunks

Try to add code in small chunks, and if you have a section that is breaking, change small things and test frequently in between changes. Comment out lines if you have to to pinpoint the error. Change one line at a time, and see if the error message changes. This part can seem really tedious, but if you think about what you're doing and really pay attention to the feedback you're getting from your testing tools, it can go pretty smoothly. 

Got any favorite testing tools or tips? Leave them in the comments! 
