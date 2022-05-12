# Basic http server in go

A server that makes several types of HTTP requests to an HTTP server. 
First a GET request using the default Go HTTP client. 
Then a POST request with a body. 
Finally a customized POST request that includes HTTP headers 
Also tested to add a timeout that will trigger if your request takes too long with graceful exit


