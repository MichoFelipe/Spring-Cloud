# Config-Server

This project help us to modify the properties from config-client without restart its server.

Steps:
- Start config-client and config-server project
- Change the value of message in config-client.properties
- Make git add config-client.properties
- Make git commit -m config-client.properties
- Ping the rest services http://localhost:8981/refresh (Post) 
- Refresh http://localhost:8981/rest/message/ and see the changes.


