# Endterm
Build your first-ever server with Node.js that serves static rеsources such as HTML documents, images, and videos. (DON'T USE EXPRESS FOR THIS PROJECT)

In the zipped folder, you will find all the required files including app.js, which will be your main file. Using knowledge from the previous lessons, build a server that will host:

1. localhost:3000 (index.html)

2. localhost:3000/about (about.html)

3. localhost:3000/img/gallery/{picture name} (NOTE: you have 2 pictures there, make routes to both of the images. Don't make routes to the images that are used in the HTML documents)

4. localhost:3000/video/{video name} (NOTE: look for the content type of the video on the internet)

If the resource exists, but unavailable for some reason, then you must give an error "500 - Internal error with a response code 500

If the resource doesn't exist and a user tries to access it then you must give the "error.html" document with a response code 404

Regardless of the URL letter case or unnecessary symbols, your server must redirect a user to the correct resource
