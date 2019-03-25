# Config-Server

This project help us to modify the properties from config-client without restart its server.

Steps:
1.- Start config-client and config-server project
2.- Change the value of message in config-client.properties
3.- Make git add config-client.properties
4.- Make git commit -m config-client.properties
5.- Ping the rest services http://localhost:8981/refresh (Post) 
6.- Refresh http://localhost:8981/rest/message/ and see the changes.


