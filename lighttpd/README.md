Lighttpd
------------

Alpine based lighttpd server as 6MB in size (the real light...!!)


    docker run -d --name lighttpd \
      -p 8080:8080 \
      -v ${PWD}/html:/var/www/localhost \
      -t arulrajnet/lighttpd:latest
