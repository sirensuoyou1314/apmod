Apache modules works:

mod\_concatx: the ability to join multiple files together in a single request.

This is a performance optimization. instead of requesting several seperate css or javascript files from your server, you can do it one request.

It is based on mod\_concat but makes ​​improvements.

1. use the browser cache in effect

2. avoid service code leak

3. avoid content stick together

http://code.google.com/p/apmod/source/browse/trunk/mod_concatx/mod_concatx.c