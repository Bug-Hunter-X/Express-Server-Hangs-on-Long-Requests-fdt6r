# Node.js Express Server Hanging Issue

This repository demonstrates a common issue in Node.js Express servers where long-running requests can cause the server to hang and become unresponsive. The example uses a `setTimeout` function to simulate a request that takes 5 seconds to process, leading to potential issues under higher loads. The solution showcases how to handle such requests efficiently.

## Bug Description:
The `server.js` file shows an Express server with a route that uses `setTimeout` to simulate a 5-second delay before responding. This delay, under high traffic, would lead to the server becoming unresponsive.

## Solution:
The `serverSolution.js` file demonstrates a solution for handling such long-running tasks asynchronously, preventing blocking issues.