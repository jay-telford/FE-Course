# Status Codes

I will not look a bit deeper into the client-server model, by exploring a part of HTTP that I have seen before - *HTTP status codes*

When a server responds to a client, the server specifies a status code as part of the response.  Status codes indicate whether or not the HTTP request was successfully completed and if there was an error, they contain some informatio nabout the type of error that happened.  The status code helps the browser to know how to handle the data that was sent back with the response.

## Possible Status Codes

There are a number of status codes.  In the table below I have laid out the status codes, along with what they mean.  

|  **Code**                    |  **Explanation**                         |
|----------------------------  |----------------------------------------  |
|  200 (OK)                    |  The request has succeeded               |
|  301 (perma moved)           |  The resource has been perma moved       |
|  302 (temp moved)            |  The resource has been temp moved        |
|  404 (not found)             |  The requested resource was not found    |
|  500 (internal server error  |  The server encounted an internal error  |