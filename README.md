# Server Load Balancer

## Description
A simple Java-based server load balancing system that assigns requests to the least loaded server.

## Features
- Maintains a cache of server loads.
- Dynamically selects the server with the lowest load.
- Updates server loads after handling requests.

## Project Structure
- **Main.java**: Initializes servers, assigns requests, and prints updated loads.
- **RequestHandler.java**: Handles incoming requests and assigns them to a server.
- **ServerCache.java**: Manages the server load cache.
- **ServerSelector.java**: Selects the least loaded server for request handling.

