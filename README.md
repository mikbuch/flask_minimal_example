# Flask minimal example

Run this with pycharm. Just run and send a request with the browser, curl or Postman.

## Example request received

Empty request:
```
127.0.0.1 - - [20/Apr/2020 16:38:56] "GET /?some_param=3 HTTP/1.1" 200 -

--------------------
I just got request!
Request:
<Request 'http://127.0.0.1:5000/' [GET]>
Args:
ImmutableMultiDict([])
--------------------
```

Parameters:
```
127.0.0.1 - - [20/Apr/2020 16:38:51] "GET /?some_param=3 HTTP/1.1" 200 -

--------------------
I just got request!
Request:
<Request 'http://127.0.0.1:5000/?some_param=3' [GET]>
Args:
ImmutableMultiDict([('some_param', '3')])
--------------------
```