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

##Example Output
Handling request Request 1 on server Server 1
Handling request Request 2 on server Server 2
Handling request Request 3 on server Server 3
Updated server loads: {Server 1=20, Server 2=21, Server 3=31}
