# HTTP Request-Response Cycle

HTTP operates on a request-response model, meaning that for each request sent by the client, the server sends a corresponding response. Here's the process:

1. **Client Sends HTTP Request**: The client (e.g., a browser) sends an HTTP request to the server. It includes:
   - HTTP method (e.g., GET, POST)
   - URI (e.g., a URL)
   - Headers (additional metadata)
   - Body (optional, for methods like POST or PUT)
   
2. **Server Processes the Request**: The server processes the request based on the method and resource, which might involve:
   - Querying a database
   - Executing server-side scripts
   - Retrieving a file
   
3. **Server Sends HTTP Response**: The server sends back an HTTP response, including:
   - Status code (e.g., 200 OK, 404 Not Found)
   - Headers (indicating content type, caching instructions, etc.)
   - Body (optional, containing the requested data)
   
4. **Client Processes the Response**: The client processes the server's response and renders the content (e.g., displays a webpage).

The flow is summarized in the diagram below:

