# Node.js Server Unresponsiveness

This repository demonstrates a common issue in Node.js applications where a long-running operation in the request handler blocks the event loop, causing the server to become unresponsive. The `bug.js` file contains the problematic code, while `bugSolution.js` shows how to resolve this using asynchronous operations.