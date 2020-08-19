---
layout: post
title:      "Sinatra Project"
date:       2020-08-19 14:49:15 +0000
permalink:  sinatra_project
---


“By failing to prepare, you are preparing to fail.”― Benjamin Franklin
Before project week, I glanced at the project requirements and decided on what I wanted to work on, but then my idea changed. I think I was overthinking this project, and it took me longer to complete than I wanted it to.

Initially, at the beginning of this new content, I enjoyed writing the SQL queries ex: SELECT * FROM fruits WHERE fruit_name = 'Pear' OR fruit_name = 'Apple';, but with Active Record I do not need to write the queries out myself. It took me a little while to grasp the Active Record concept, but now I have a better understanding of its role.

Active Record is a useful Ruby Gem which creates a link between Ruby and databases. For this project, Active Record was helpful for working with associated objects, and the associations allowed me to associate models without having to write multiple lines of code. Active Record makes it easier to implement relationships such as belongs_to or has_many. I utilized these relationships in my Sinatra Project. To implement these relationships, I needed to write migrations to create tables with the associations. Each Active Record object has built-in methods for accessing the database to create, read, update, and delete. In building out this Sinatra application, users can implement these actions through the interface of the web.

