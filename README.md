This is an example of building an HTTP server using
Node.js, Express, MongodDB, WebSockets and the cluster module.

This was created for a talk I gave on Node.js given at CAIT,
a division of Washington University in St. Louis, on June 4, 2013.

It is built in a series of steps.
* server1.js only uses Express.
* server2.js adds MongoDB.
* server3.js adds WebSockets.
* server4.js adds the Node.js cluster module.

To test one of the servers,
* node server#.js
* browse http://localhost:3000/addressbook from multiple browser windows
