# node-static-change-detect-server
node js static web server with file change detection that effects a browser refresh.  Refresh
notice is sent to the injected code in your web page from the server using HTML web sockets.

Requirements.
=============
node

npm install websocket

To use.
=======
Place in head of your html files `<meta detection-change="true">` so that it will auto 
refresh if any served files change.  

To run server.
==============
node static_serve.js
