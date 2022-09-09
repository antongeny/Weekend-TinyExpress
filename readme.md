Weekend Homework

This weekend, you'll be required to set up a tiny express server from scratch
-Displays information about a topic of your choice.
This can be any set of data that you want, as long as there's a collection of them and the requirements below are hit.
(i.e. have a server that displays info about your 3 favorite movies)

Requirements:
[] In a file called dummyData.js module.exports an array of dummy data representing your topic
[] In a file called index.js
[] Import the data you made in dummyData.js
[] Create a node app that opens a server using express
[] Create 3 GET endpoints:
[] 1- /health = sends back the string "Server is online!"
[] 2- /{your topic} = sends back the entire array from your dummy data file
EX: /movies if your topic is movies
[] 3- /{your topic}/:dataIndex = sends back only a single item from the dummy data array that matches the given index
EX: /movies/:dataIndex if your topic is movies
[] BONUS:
[] Add the HTML file for one of your past projects (either a homework, pixilate, or anything else you worked on) along with any assets into a /public folder
[] Serve those files up using the Express Static middleware
