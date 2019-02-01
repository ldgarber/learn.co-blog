---
layout: post
title:  "Becoming an MVC MVP"
date:   2017-03-09 22:17:56 +0000
---


If you couldn't tell already, I like bad jokes. 

Anyway, what is MVC, and how can you remember what it is? 

MVC stands for Model, View, Controller, and it's a structuring method for Ruby on Rails projects. It's useful to have a standard way of formatting and organizing file structure, or large apps can easily become a mess. 

```
Model, View, Controller - what do they do? 
```

What do they do? 

Let's imagine that instead of building an app, we are forensic artists, making a police sketch of a perpetrator. The first thing that's going to happen is the Chief will say, we need a sketch! The Chief is like the controller. She tells us what kind of sketch we need, when we need to make it, and often we give the sketch back to the chief when it's done. 

So, say a witness comes in to give details on the perp. The witness is like someone filling in a form on your web page. The witness gives us details, which go through the Chief, who tells us, Make a sketch with this type of eyes, nose, face, etc. 

We, the artist, are like the model. We can take in a series of details about a person, and output a drawing of a face. 

Then, the completed sketch is shown to the witness, and maybe it gets run through the FBI database. This completed sketch is like the view, what people SEE when they access our app. 

Models are Ruby objects, which can be re-used to create different instances of that object. 

Views are html files and templates, which display the objects to the user. 

Controllers are Ruby files that parse routes from the user, send information to models, and receive information and determine which routes to display. 
