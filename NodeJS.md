![NodeJS Language](images/NodeJS.png)


#### About NodeJS: 
Node.js is an **open-source, cross-platform JavaScript runtime environment and library** for running web applications outside the client's browser.

#### Primary Use:
Developers use Node.js to create server-side web applications, and it is perfect for data-intensive applications since **it uses an asynchronous, event-driven model**.

#### Possible Limitations:
Node.js is unable to handle heavy CPU bound tasks, it lacks library support, it has many nested callbacks, and unstable API.

#### Sample Code:
```cpp
var http = require('http');

http.createServer(function (req, res) {
  res.writeHead(200, {'Content-Type': 'text/plain'});
  res.end('Hello World!');
}).listen(8080);
```
|  Language Feature      | Yes _or_ No |
|------------------------|------------|
| Is it Imperative?      | Yes        |
| Is it Functional?      | Yes        |
| Is it Object-Oriented? | Yes        |
| Is it Interpreted?     | No         |
| Is it Concurrent?      | Yes        |
| Is it Standardized?    | Yes        |