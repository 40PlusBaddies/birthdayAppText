# birthdayApp  
## Tech stack  
JavaScript  
NodeJS  
Express  
MongoDB  

  
#### Bree.js  
The app uses Bree to schedule birthday notification emails. Bree is a job scheduler for Node.js that uses worker threads instead of the main thread.   

#### 
For parsing.  

#### Day.js  

One of the major challenges when building the app was to make calculations with date, so to determine whether a birthday was coming up within one day, a week, or a month. 
We decided to use Day.js, a JavaScript library that parses, validates, manipulates, and displays dates and times. It’s an alternative to Moment.js.
By default, Day.js parses and displays the date in local time. We opted to use the UTC plugin [because it makes it easier to calculate the birthday when someone lives in a different time zone???]. We also use the DayOfYear plugin, that converts the YYYY-MM-DD format into an integer between 1 to 365, making it easier to calculate.  
Another plugin used is duration [why?]  


#### EJS  
Template engine to render the web pages.   

#### Express-session  
Express-session is a cookie-based session middleware.   

#### Flash  

#### Mongoose  
Mongoose is an object data mapper (ODM) used to integrate MongoDB with NodeJS.  

#### Passport  
Passport.js is an Express middleware that handles user authentication.  

#### Transporter  

#### Nodemailer  
