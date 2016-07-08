# About RideOn
RideOn, a web application built with a MVC framework is similar to Uber, Lyft or any other car pooling application. It was aimed at university level to ease car pooling among students. 


## Technologies Used

Front-end : HTML5, CSS3, Bootstrap3, JQuery, Javascript  
Back-end  : Node.js, Express.js, Javascript  
Database  : MongoDB  

## Model

RideOn has two schemas and we have used MongoDB a NoSQL database.

**rideSchema**
This Schema is designed to hold the information about the rides posted.
It has fields for destination,source, seats, stops, if the price is negotiable, car type and other personal details to contact the person who is offering the ride. 

**userSchema**
userSchema has information about the registered users.
It was hold the user infomrtion like registered email id, username and the password.


##View

We have used **ejs** templating engine to generate HTML markup.

Home page has link to static pages about us, contact, team, testimonials and options to sign up and login.

The application has two pages to post the ride and request ride by querying.


##Controller

This part of the application uses **passport local** to authenticate users or sign them up.

It also controls the pert of posting the ride information into the database and querying them.


##Hosting

The application is deployed in heroku and it is available in the folowing link

 https://dry-mountain-13366.herokuapp.com/













