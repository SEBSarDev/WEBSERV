# WEBSERV
A web server in cpp

This is a group project, we had to create a web server in cpp, using EPOLL. This project help us to understand how web requests work, and how the server processes informations to return a response.
We also learn about the configuration file of a webserv that allow or not the access of some pages.
Finally, we learn how CGI work and implement it.

The pages of our sites are in website irectory, you can add pages as you want.
You can run webserv with
```
$ make
$ ./webserv ./conf/default.conf
```
You can add your own configuration file. The default one launch on port 8000, 8080, 8001, 8002. The port 8080 offers more possibilities.
You can communicate withe the server using curl command.
Or you can see the website by launch localhost:8080 for instance and navigate through files.
Have fun !
