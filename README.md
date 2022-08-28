# Session-management in Express

# Intro 

A website is based on the HTTP protocol. HTTP is a stateless protocol which means at the end of every request and response cycle, the client and the server forget about each other. 

This is where the cookie comes in. but it has some security issues. Since cookies are stored on a user's computer it is possible for an attacker to easily modify cookie content to insert potentially harmful data in your application that might break your application.

Also every time the browser requests a URL to the server, all the cookie data for a website is automatically sent to the server within the request. 
It means if you have stored 5 cookies on the user's system, each having 4KB in size, the browser needs to upload 20KB of data each time the user views a page, which can affect your site's performance.

# Solution: Use Sessions.

 A session will contain some unique data about that client to allow the server to keep track of the user’s state. In session-based authentication, the user’s state is stored in the server’s memory or a database.

# How does the session work? 



## User Journey
User will start his/her journey from the landing page 📃 which show some information about our app 
and it has a Get-Started 🚀 button to move for home page.Once the page is opend, he/she will see a suggested books.
Also he/she can search about any books he/she is looking for.In addition to, Once he/she start type in the search bar,
he/she will get a suggestions for what he is looking for.


## How To clone Our App 👍: 
- if you are a git user:
    - In Your terminal write `git clone https://github.com/CA-G12/Books-Station-Moh-Saif.git`
    - Then `cd Books-Station-Moh-Saif`


## How Test Our App  👍: 
- Open gitBash where project path is.
- Type -> `node install`
- then Type -> `npm test`


## Technologies ⚙: 
- HTML5
- CSS3
- Javascript
- Node.js
- Npm pakages [Jest - Supertest - Mimetypes - Eslint ] 
- Git & Github
- Heroku
- JSON Files
- Google book api [https://www.googleapis.com/books/v1/volumes?q=BookName]
- Figma


## Our Team 👩‍💻👨‍💻
- [Mohammad Balousha](https://github.com/MohammedOmar123).
- [Saif Al-Hayek](https://github.com/SaifHayek).
