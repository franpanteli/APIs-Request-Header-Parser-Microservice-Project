# APIs-Request-Header-Parser-Microservice-Project
This repository contains my independent problem-solving work, used to produce a full-stack JavaScript application with Node.js and Express.js. This service handles HTTP GET requests by parsing and extracting information from  client request headers. This includes their IP address, language preferences and software details. This was my [second project](https://github.com/franpanteli/APIs-Request-Header-Parser-Microservice-Project/blob/main/project-task-notes.txt) as part of freeCodeCamp's [Back End Development and APIs](https://www.freecodecamp.org/learn/back-end-development-and-apis/) curriculum. The problem-solving approach I used to create this is detailed in depth in its [project server.js file](https://github.com/franpanteli/APIs-Request-Header-Parser-Microservice-Project/blob/main/server.js). Building on [the previous problem I solved](https://github.com/franpanteli/APIs-Timestamp-Microservice-Project)  as part of this course, my solution to this problem uses a middleware function for 404 error handling when serving its static index.html file. The approach I used for this also incorporates Cross-Origin Resource Sharing (CORS) middleware. 

## Microservice Installation & Usage
<img width="791" alt="Screenshot 2024-03-01 at 20 34 28" src="https://github.com/franpanteli/APIs-Request-Header-Parser-Microservice-Project/assets/131474705/44c12cd5-4712-4b36-8d20-62efe8a39624">

[My full notes on how to run the project locally are here](https://github.com/franpanteli/APIs-Request-Header-Parser-Microservice-Project/blob/main/launching-the-app-locally.txt).  First, clone this repository with `git clone https://github.com/franpanteli/APIs-Request-Header-Parser-Microservice-Project.git`.

## API Endpoints
The path for the project's primary API endpoint is /api/whoami. When a client makes an HTTP GET request to this endpoint, the server responds with a JavaScript JSON object. This contains their IP address, language preferences, and software information. Error handling was also implemented to serve the project index.html file.

## Dependencies
This project has two dependencies. The first is [express](https://www.npmjs.com/package/express), which was used to build the web application in its [server.js file](https://github.com/franpanteli/APIs-Request-Header-Parser-Microservice-Project/blob/main/server.js). The second dependency is [cors](https://www.npmjs.com/package/cors), which was used to produce Cross-Origin Resource Sharing middleware.
