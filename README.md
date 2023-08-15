# SimpleServer
Simple apache2 server with php5-fpm.

## About
Sometimes I do webcoding. When I do I need a simple webcontainer to try my code in, since I do not want a webserver installed on my laptop.
So, here is a container with Apache 2, php5-fpm and libapache2-mod-php5 installed.

## How to use
I created this for a single html-file. Place index.html in the same folder as the Dockerfile, run
docker run -d -p [localport:containerport] phedman:simpleserver
Done.

## Disclaimer:
I have not tried to pull this myself, so if it breaks during pull, please let me know and I will fix it.
"It works on my machine" i.e, when I wrote the dockerfile and built it.
