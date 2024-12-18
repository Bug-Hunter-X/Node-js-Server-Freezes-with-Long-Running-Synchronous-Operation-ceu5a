# Node.js Server Freeze

This repository demonstrates a common issue in Node.js where a long-running synchronous operation in a request handler can freeze the entire server, making it unresponsive. The `server.js` file contains the buggy code, while `serverSolution.js` provides a corrected version using asynchronous operations.