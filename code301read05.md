
# HEROKU and Node.js

- HEROKU : it is a cloud platform used for deploying, managing, and scaling modern apps. 

- To clone a local version of the sample application to deploy to Heroku, the following commands  is used in the terminal:
`git clone https://github.com/heroku/node-js-getting-started.git` # or clone your own fork 
`cd node-js-getting-started`

-  Procfile is a text file in the root directory of the application, to explicitly declare what command should be executed to start the app.

-  dyno is a lightweight container that runs the command specified in the Procfile.

- Scaling an application on Heroku is equivalent to changing the number of dynos that are running.
`heroku ps:scale web=0`
`heroku ps:scale web=1`

- Heroku recognizes an app as Node.js by the existence of a package.json file in the root directory.


- Node.js is a platform built on Chrome's JavaScript runtime for easily building fast and scalable network applications. Node.js uses an event-driven, non-blocking I/O model that makes it lightweight and efficient, perfect for data-intensive real-time applications that run across distributed devices.

- Features of Node.js:

 + Asynchronous and Event Driven

 + Very Fast 

 + Single Threaded but Highly Scalable. 

 + No Buffering 

 * License − Node.js is released under the MIT license.