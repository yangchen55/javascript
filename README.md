# javascript
this is about transforming json to javascript and displaying it on html API table. you will get json file at this url(https://jsonplaceholder.typicode.com/users)

What is JSON?

JSON stands for JavaScript Object Notation. It's a standard for transforming nearly any object into a string representation that is human readable. It became a standard for exchanging data to/from a remote HTTP server, and is available for many other languages in addition to JavaScript.

A JavaScript object o in JSON looks a lot like what o.toString() returns.


There are two main methods to know:

Transform any JavaScript object in JSON:           
var jsonStr = JSON.stringify(obj);
Transform any JSON string into a JavaScript object:
var jsObj  = JSON.parse(jsonStr);



Example: consuming remote data
JSON data from a REST WebService
Most "big sites" provide what we call a REST API. This means "they propose to send/receive data to/from programs over HTTP", and most of the time the JSON format is one of the possible transport formats for the data. Google APIs, Facebook and Amazon APIs are like this.

JSONPlaceholder is a free online REST service that you can use whenever you need some fake data in JSON. Faking a server is great for tutorials, and this is exactly what the next example does. It will consume data from this URL.

Please click on it - you will see some JSON data coming from the server and being displayed in your browser:
