What is responsible for defining the routes of the games resource?
The const router.

What do you notice about the folder structure? Whats the client responsible for? Whats the server responsible for?
The server is responsible for the database and for the routes(so the back end). The client is responsible for the front end changes, so whatever the client does on the website gets passed to the server.

What are the the responsibilities of server.js?
It is responsible for configuring the server and to connect the database to the server.


What are the responsibilities of the gamesRouter?
To get the data from the database gamesCollection.

What process does the the client (front-end) use to communicate with the server?
It uses GamesServices.js where a baseURL is defined. (a form)

What optional second argument does the fetch method take? And what is it used for in this application? Hint: See Using Fetch on the MDN docs
The Request interface of the Fetch API represents a resource request.

Which of the games API routes does the front-end application consume (i.e. make requests to)?
To http://localhost:3000/api/games/

What are we using the MongoDB Driver for?
So our database and server side application has connection and can syncronise.