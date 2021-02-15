---
layout: post
title:      "Penciled In: Because Coding Means A Lot of Erasing"
date:       2021-02-15 04:46:40 +0000
permalink:  penciled_in_because_coding_means_a_lot_of_erasing
---


Wow. I don't think I have ever done as many Google searches as I did while working on this project. 

Building a Rails web application has a lot of moving parts. Although I understood the concepts while making my way through the lessons and labs, remembering syntax and where to put certain parts of the code was really challenging for me. I found myself on Google constantly, looking up how to write specific bits of code. I also found myself rewatching many of the lectures from throughout the module. All in all, building this project was great at teaching me how to troubleshoot.

One of the biggest challenges for me was the nested routes. Everytime I thought I had something worked out, a new problem would arise. For example, I had coded my nested routes for my Event and Category models. When, I moved on to my nested Events and RSVPs, everything suddenly broke. It ended up being a matter of my routes order.

Originally, I had written the following:

```
Rails.application.routes.draw do

...

resources :categories do
   resources :events, shallow: true
 end

resources :events do 
   resources :rsvps, shallow: true
 end
	
...
	
end

```

When I would attempt to create a new event (localhost:3000/events/new), it would give me an error saying "new" was not an event_id. For the life of me, I couldn't figure out why. After many a Google search, and a wonderful 1:1 with my cohort lead, I finally figured out why. My nested routes were in the wrong order. I had defined my 'events/new' before my 'events/:id' so my program was searching for an event with an id of 'new'. 

The same type of issues popped up when working on my nested forms as well. I would get them working, implement a new piece of code, and break everything. I relied heavily on my rails console and byebugs. And eventually, I made it through. 

This project was challenging and frustrating, but it was also very gratifying. Every time I has to troubleshoot was another chance to read the Rails documentation, view other people's code, and understand *why* things worked the way they did. I have always been the kind of person that learned by doing. During this project, I did *a lot* so I learned *a lot*. Now, I can't wait to move forward into the world of Javascript.

