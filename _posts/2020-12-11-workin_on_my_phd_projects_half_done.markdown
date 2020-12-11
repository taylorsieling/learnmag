---
layout: post
title:      "Workin' on my PhD... Projects Half Done"
date:       2020-12-11 21:40:07 +0000
permalink:  workin_on_my_phd_projects_half_done
---


I consider myself to be somewhat of a serial hobbyist. On the top of that list is knitting. However, I always find myself only half completing projects or buying yarn with no project in mind. Which leads me to my Sinatra Project. 

I was incredibly excited to start the Sinatra module. I was finally getting the hang of things and felt confident after my last project review. When I read the project requirements, I immediately knew I wanted to incorporate my love of knitting (and my habit of not finishing what I started). And so, Projects Half Done was born.

I started building my project with the [Corneal Gem](https://thebrianemory.github.io/corneal/). Running Corneal will essentially set up the entire file structure for a Sinatra Application. I also used the Corneal Scaffold feature, which generates your models along with their associated controllers and views. The Corneal Gem was really handy; It saved me time and eased me into the coding itself. The Model syntax and Controller CRUD routes were all set up for me, so I could dive right into the code.

My application has three models - Users, Projects, and Yarns. Users can have many Projects and many Yarns. Projects can belong to a User and have many Yarns. And Yarns can belong to a User and a Project. Essentially, Users can create Projects with details such as name, category, knit time, and status. They can then add Yarn to their account with details such as brand, name, weight, color, and quantity of hanks. The Yarn can be associated to a Project, or saved to be assigned later. 

The project did take me much longer than anticipated. I wanted to finish within the first project week, however, I found myself caught up in the design of the application. Instead of focusing on making the program work and be fully functional, I would get distraced in building out the CSS. It is definitely something that I need to keep in mind for future projects. Functionality should come first. The design needs to come after. Otherwise, I will get too involved in the many design aspects and will run out of time to code the programming. 

A tool that helped me immensely with this problem was [Bulma.io](https://bulma.io/). Bulma is a CSS framework that has easy-to-use classes ready to assign to your HTML elements. A fellow student recommended the framework and it helped to quickly and easily make my project look like a professional application. 

All in all, I loved working on this project. There is something incredibly satisfying about changing something in your code and being able to immediately see the change in your browser. I hope to continue building on the application in the future to make in something I can really use to help track my knitting projects and alllll my hanks of yarn. 

Now, my projects half done can turn into projects completed.






