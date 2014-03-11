RoutesAndPromises
=================
This assumes you have Node already installed. Lots of resources for installing Node if you don't.

First, clone this repository.

Optionally install the live reload extension for Chrome

https://chrome.google.com/webstore/detail/livereload/jnihajbhpnppcggbcgedagnkighmdlei

Install gulp (used for the client code)

    npm install -g gulp
  
Install express (used for the server code)

    npm install -g express

In the RoutesAndPromies/server directory, run the following to setup the REST server (first time only)

    npm install
  
Then, start the REST server

    node rest_api.js
  
In a separate terminal, in the RoutesAndPromies/client directory, run the following to setup the Angular app

    npm install
  
Then, start serving the app

    gulp
  
Finally, visit http://localhost:3000 in your web browser
  
# References
* http://docs.angularjs.org/api/ngResource/service/$resource
* http://docs.angularjs.org/api/ng/service/$q
* http://docs.angularjs.org/api/ngRoute/provider/$routeProvider

  
