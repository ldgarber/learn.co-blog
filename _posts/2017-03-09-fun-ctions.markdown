---
layout: post
title:  "FUN-ctions"
date:   2017-03-09 21:05:42 +0000
---


This blog post will serve as an introduction/recap post of function declarations in javascript, what they mean, and the differences between various ways of declaring a function. 

BASIC: 

Here's a basic function, to express your love for something: 

```
function iLove(word) {
 console.log("I love " + word); 
 return; 
} 
```

You would run this function within your code by writing
```
iLove("you"); //prints "I love you" to the console
```

In this function, the word in between the parentheses, word, is the *argument.* This means that you pass in some value to this function, and then the function takes the thing you passed in, maybe does something to it, and spits out some result. There is no rule that a function has to use the argument, but if you're not going to use them, you shouldn't make them arguments in the declaration. 

For example, you could write this: 
```
function whoNeedsEm(a, b, c) {
console.log("Arguments? Who needs em!"); 
return; 
}
```
..but it doesn't make much sense. 

You can also delare this function in a variable, like this: 

```
var iLove = function(word) {
 console.log("I love " + word); 
 return; 
} 
```

This stores the function in the variable iLove. 

A third way to declare a function is using the "arrows": 
```
var iLove = (word) => {
console.log("I love " + word); 
return; 
}
```

This is the same as the normal way, but more concise! 
