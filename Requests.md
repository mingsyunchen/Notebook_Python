## Difference between "data" and "params" in Python requests
* params form the query string in the URL
* data is used to fill the body of a request (together with files). GET and HEAD requests have no body.

params form the query string in the URL, data is used to fill the body of a request (together with files). GET and HEAD requests have no body.
For the majority of servers accepting a POST request, the data is expected to be passed in as the request body.
You need to consult the documentation for the specific API you are calling as to what they expect, but if you have to assume, assume you have to use data.
