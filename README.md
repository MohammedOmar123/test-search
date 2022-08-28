# Session-management in Express

# Intro 

A website is based on the HTTP protocol. HTTP is a stateless protocol which means at the end of every request and response cycle, the client and the server forget about each other. 

This is where the cookie comes in. but it has some security issues. Since cookies are stored on a user's computer it is possible for an attacker to easily modify cookie content to insert potentially harmful data in your application that might break your application.

Also every time the browser requests a URL to the server, all the cookie data for a website is automatically sent to the server within the request. 
It means if you have stored 5 cookies on the user's system, each having 4KB in size, the browser needs to upload 20KB of data each time the user views a page, which can affect your site's performance.

# Solution: Use Sessions.

 A session will contain some unique data about that client to allow the server to keep track of the user’s state. In session-based authentication, the user’s state is stored in the server’s memory or a database.

# How does the session work? 
![mohass](https://user-images.githubusercontent.com/94321523/187096087-eda0c685-2371-4061-9b7d-bb04ece2a80e.png)


# Why Use Session ?
-	Sessions are used to store information such as UserID over the server more securely, where it cannot be tempered.
-	It can also transfer the information in the form of value from one web page to another.
-	It can be used as an alternative to cookies for browsers that don't support cookies to store variables in a more secure way.


# Key Differences between Session and Cookies: 
-	Sessions are server-side files that store the user information, whereas Cookies are client-side files that contain user information on a local computer.
-	Sessions are cookies dependent, whereas Cookies are not dependent on Session.
-	The session ends when the user closes the browser or logout from the application, whereas Cookies expire at the set time.
-	A session can store as much data as a user want, whereas Cookies have a limited size of 4KB.
-	Sessions are more secured compared to cookies, as they save data in encrypted form
-	If persistent data must remain when the user closes the browser, use cookies.
-	If persistent data does not have to remain when the user closes the browser, use sessions.




# How to use the session in your express app ?
- npm install express-session.
![Screenshot (364)](https://user-images.githubusercontent.com/94321523/187096466-4d984213-a396-4997-9015-9129fcc4817a.png)
 
