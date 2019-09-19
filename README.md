## Pythagorean Theorem Calculator

https://glitch.com/~a3-cenright71925 

### Requirements

I had alot of trouble with this assignment and was unable to complete it. Below I will talk about what parts I was able to do.
- a `Server`, created using Express 
    - I completed this 
- a `Results` functionality which shows the entire dataset residing in the server's memory
    - I completed this with the table on the right side of the screen
- a `Form/Entry` functionality which allows users to add, modify, and delete data items (must be all three!) associated with their user name / account.
    - I can add entries but I cannot edit or remove them from the database
    - I was unable to implement user accounts so there is only one set of data
    username: root password: root
- Use of at least five [Express middleware packages]
    - Passport
    - body-parser
    - connect-timer
    - compression
    - rid
- Basic authentication using the [Passport middleware]
    - I used passport to login to the calculator page
- Persistent data storage in between server sessions. 
    - I implemented lowdb
- Use of a [CSS framework or template]
    - I used milligram

### Summary

A video of my application can be found here: https://www.youtube.com/watch?v=zLav_1eXk7o&feature=youtu.be (incase it will not load due to the problem described below)

- The goal of this appliation was to allow the user to calculate the hypotenuse of a right triangle
- I faced many challenges when making this application. At somepoints I had errors that would only appear on glitch and not locally. Then when I switched to local, I had different errors that were not found on glitch. This made it very hard to make progress in the assignment. I also had an error that would only leave if I would comment out the whole file and then uncommented it line by line until it worked. This error seemingly randomly popped up a couple of times which was frustrating. I went to Tariq's office hours and then spoke to the professor who solved my issue. Unfortunately, when I fixed this problem, the rest of my app would not work. It was some discrepency between strings and json objects on the server side of the request. Because of this I was unable to make much progress so I am turning what I was able to do.
- I chose to use the local strategy because it was the most simple to implement
- I chose lowdb for the database as suggested in class. However, If i were to do this again I would see if there is a database that integrates better with glitch
- I used milligram as suggested for my css framework
- Express middleware:
    - Passport was used to aid with the authentication process 
    - Compression compressed the requests and responses
    - Connect-timer records the time of each response
    - Body parser parses the json for each request
    - Rid assignd a uniqie ID to each request

## Technical Achievements
- none

### Design/Evaluation Achievements
- Accesibility - Image has alt tags and page can be easily tabbed through (this is the same as last assignment I am unsure the rules for duplicating accesiblity achievements)
