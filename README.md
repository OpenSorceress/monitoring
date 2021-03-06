monitoring
==========

A [node.js](http://nodejs.org/) system performance monitoring demo.

This code is just a demo of the StreamAssembler pattern for dealing
with real-time streams processing.

Installation
------------

`npm install`

Dependencies
------------

* node-stat (0.0.4)
* express (3.0.3)
* redis (0.8.2)
* redis-sync (0.1.4)
* socket.io" (0.9.11)

Usage
-----

* Starting the redis database service (if needed)

* Starting the node.js HTTP server.

$ ./server.js

* Browser to localhost:8080

* Starting the retriever

$ ./retriever.js


License
-------

(The MIT License)

Copyright (C) 2012 Igalia S.L, [igalia.com](http://www.igalia.com)

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
