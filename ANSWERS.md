<!-- Answers to the Short Answer Essay Questions go here -->

1.  Describe Middleware, Sessions (as we know them in express), bcrypt and JWT.
    a.Middleware is a function that intercepts data before it the res side of a server and allows you to check the data before you send a request
    b. Sessions are stored on the data base and can be used to track a client when interacting with a server.
    c. bcrypt is a library that allows for easy hashing of passwords and long with rechecking those hashed passwords against themselves

2.  What does bcrypt do in order to prevent attacks?
    it hashing the password many times making it hard for an attacker by extending the time it would take to create a rainbow table with a possible password

3.  What are the three parts of the JSON Web Token?
    header, payload, and signature
