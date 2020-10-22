---
layout: post
title:      "Ruby on Rails"
date:       2020-10-22 14:34:49 +0000
permalink:  ruby_on_rails
---


For this project, I decided to focus on the concept of a user wanting to book a massage. I only included the functionality, so the user is the only one who is able to sign up, sign in, etc. If I built in an admin view, I would allow the admin to view all of the booked appointments.  The name of my application is called Relaxation Parlor. Completing the Sinatra project previously provided me with some of the necessary information regarding RESTful conventions. Utilizing rake routes was helpful for me with identifying all of the RESTful actions. The seven routes include index, create, new, edit, show, update, and destroy. With the use of RESTful routes, there is a clear mapping between the URL resource and the correspondending controller actions. In regards to this project, for a user, the index route displays all of the user's appointments. The create route allows the user to create a new appointment. The new route renders a new form for creating a new appointment. The edit route renders the form for editing an appointment. The show route displays a single appointment. The update route allows the user to update an appointment. Finally, the destroy route allows an appointment to be deleted. Throughout the development of the project, the error messages were much clearer when a template, method, or view was missing. I followed the two major guiding principles: Don't Repeat Yourself (DRY)  and Convention over Configuration. By utilizing these, I did not have to write the same information over and over and there were default conventions that saved time.


