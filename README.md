# GeneralNote
TOPICS
1.  JWT
JWT = securely transmitting info as JSON object. The following the needed dependency for using JWT
<dependency>
    <groupId>com.auth0</groupId>
    <artifactId>java-jwt</artifactId>
    <version>4.0.0</version>
</dependency>
JWT official = https://jwt.io/introduction
helpful article to implement JWT = https://medium.com/geekculture/implementing-json-web-token-jwt-authentication-using-spring-security-detailed-walkthrough-1ac480a8d970
2.  SOME KEY CONCEPTS IN JPA IMPLEMENTATION
3.  helpful article on JPA = https://www.baeldung.com/learn-jpa-hibernate
4.  STANDARD WAY OF INTEGRATING BACK-END WITH REACT APPLICATION
5.  STANDARD WAY OF DEVELOPING ABYSS APPLICATION WITH BACK-END AND FRONT-END INTEGRATED
for any javascript(react/Abyss) application development understanding node and express which is Node web framework is very important
To create Node app:
    1. we need the Latest Node and npm installed on our machine Then the following is example of pure Node app:-
    // Load HTTP module
const http = require("http");
const hostname = "localhost";
const port = 8000;
const server1 = http.createServer(function(req, res) {

    // Set the response HTTP header with HTTP status and Content type
    res.writeHead(200, {'Content-Type': 'text/plain'});
 
    // Send the response body "Hello World"
    res.end('Hello World\n This is pure node application without using any web framework.');
 });
 // Prints a log once the server starts listening
 server1.listen(port, hostname, function() {
    console.log(`Server running at http://${hostname}:${port}/`);
 })
 node fileName.js to run node js app.
 To create express App
 1. Node and npm
 2. npm init to create package.json for dependencies
 3. npm install express to install express.
 
 Below is express app:
 //express web framework usage
const express = require('express')
const app = express();
const expressport = 3000;

app.get('/', (req, res) => {
  res.send('Hello World! This is express app')
});

app.listen(expressport, () => {
  console.log(`Example app listening on port ${expressport}!`)
});
6.  GRAPHQL WITH ANY DATABASE AND BACK-END AND FRONT-END TECHS
7.  REACT AND ABYSS TEST AND JAVA ADVANCED UNIT AND INTEGRATION TEST(MOCKING, PARAMETERIZED TEST,ETC)
    react test is done by jest
8.  YAML FILE
9.  AWS(LAMBDA FUNCTION, S3, DYNAMODB ETC)
