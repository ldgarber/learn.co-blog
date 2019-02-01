---
layout: post
title:  A gem of a different fashion
date:   2017-05-17 18:42:50 +0000
---


When I thought about what kind of gem to build for this lab, my mind went to an online marketplace where a user can search among many different stores at once. When I started to build this gem, I realized how complicated that was. Here are some of the difficulties I found, and how I made an MVP proof-of-concept that can someday be expanded to become the marketplace I imagined. 

First, every online shopping site has its own system of displaying and labeling results. Considering this gem is an html scraper, each store you want to scrape has to be configured with its own labels of what constitues an item, where the item details are found, and where the text is. I decided to limit my MVP to one online store to start with. 

There also are many areas with information about each item. I decided to focus on the main title, which tells you what the item is, with an option to enter an item's number for more information about each item. This 'more info' button would take text from the item description. Ordinarily, one would have to go to a separate page to view these details, so I thought having them directly on the command line at the push of a button would be helpful. 

In the future, I would build out this gem more by supporting more stores, and allowing the user to get more info about each item, such as sizing information, availability, and pictures. 
