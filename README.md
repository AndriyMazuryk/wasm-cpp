To compile it:
$ em++ hello.cpp -s WASM=1 -o hello.html

To compile without overriding hello.html file:
(compiles only hello.wasm and hello.js)
$ em++ hello.cpp -s WASM=1 -o hello.js

To run the code:
$ emrun --port 8080 .
