# HTTP Baiscs Refresher

### HTTP BASICS

GET /robots.txt HTTP/1.1
Host: nahmsec.com
User-Agent: Mozilla/5.0 (X11; Linux aarch64; rv:91.0) Gecko/20100101 Firefox/91.0
Accept: */*
Accept-Language: en-US,en;q=0.5
Accept-Encoding: gzip, deflate
Connection: close

### COmmonly Used HTTP METHODS
* GET to fetch data
* HEAD does the same thing as get but does not show full response
* POST to create or change data
* PUT to rfemplace or modify data
* DELETE to delete data
* OPTIONS to see communications options (GET,HEAD,POST,PUT,DELETE,ETC)

### MOST COMMON RESPONSE STATUS CODES

 * 200 rage - Successful response
 * 300 range - Redirects
 * 400 range 
  * 401 - Unauthorized or unauthenticated
  * 402 - Forbidden or no access to resources
  * 404 - not found or file does not exist 
  * 405 - http method not allowed
 * 500 - Internal error where the server does not lnow how to hanlde the request
 * [Tons more!!](https://developer.mozilla.org/es/docs/Web/HTTP/Status)
