# Mixed messages!

# What is this!?

this is a small JS project I've been tasked with on Codecademy. The project instructions are quite vauge it just asks you to create a random message generator so I will interperate that as a madlib sort of thing.

# Idea

so my idea is this, Its a webapp that is just online with two pages. one where you can input sentence structures with placeholders to send to a JSON file on the server. Then on another page a random message is generated every time you enter.

# Execution

Since this is for JS practice this entire thing will be built in JS, and Node.js. My plan is the following, I will set up a node app that can read and write to JSON files. Then I create a connection between this app and a local server that can send information to the file and also retrieve it. From there I can begin structuring my "sentence objects" which I will use to create flexible outputs and then I will create a way for the program to parse these objects, and create sentences from them. I will also create a way to send sentences to the JSON file. Both to find suitable words for filling blanks and to prevent bad input I will likely use web apis though it's somewhat unclear to me what will the best approach here and personally I see it as one of the projects biggest challenges given it's fun and it would be sad if someone ruined it by spamming a bunch of negative or hateful things.

# To do

+ ~Set up GitHub repo~
+ Figure out how to read and write to files using node
+ Figure out how to make a front end for the node read write thing
+ Figure out how best to structure the sentence objects to be as flexible as possible
