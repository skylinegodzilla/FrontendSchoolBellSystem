# FrontendSchoolBellSystem
This is a frontend web interface I built for a school bell system that is to run of an Arduino web server.

Basicley this is a light weight interface that runs on a ardrino webserver. The webserver uses XMLHttpRequest to comunicate between the Ardrino and the website. 
The website itself reads an xml file to update its contents in realtime. 
When someone intracts with the web interface it sends an XMLHttpRequest to the ardrino server then the server updates the xml file accordingley.

The backend itself (The C++ code running the webserver on the Ardrino) was built by another staff member so I cant upload it.
