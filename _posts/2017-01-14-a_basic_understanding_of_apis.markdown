---
layout: post
title:  "A Basic Understanding of APIs"
date:   2017-01-14 18:40:06 -0500
---


I've recently started working with collecting information from APIs, which has always struck me as one of the least accessible parts of writing an app. How does all this information from one source make its way into a separate app or website? What is an API anyway? 

Basically, an Application Programming Interface, or API, is a website that serves and updates information from a particular source based on HTTP requests (GET, POST, etc) from a user that is interacting with the API. 

When you access a normal webpage, your browser uses http protocol to make a GET request to that page, and then the server somewhere shows you the contents of the webpage - all the html, css, and javascript included in the source code, displayed in the browser window. 

When you access an API, the same thing happens, but you have to explicitly specify the type of request, and then instead of getting back html and css and so forth, you get back data, typically in JSON. 

You can see an example of this at work by just typing into your web browser: 
https://api.github.com/search/repositories?q=unicorn
(You can change the 'unicorn' to whatever you want to search for!) When you hit enter, a page comes up with JSON results, which are hard for us to read, but easy for apps to parse! The JSON response is basically like a hash or dictionary which contains nested information. 

[JSON results](https://api.github.com/search/repositories?q=unicorn)

The most important thing to remember about working with APIs is to make sure to read the documentation and supply the necessary authentications/headers to get the response you are looking for! Without APIs we would be stuck crawling html which is very variable and apt to be derailed by even minor changes on the front-end. APIs are a more stable way of accessing information for a variety of sites including Github, Twitter, Foursquare and many many more, so go forth and try them! 
