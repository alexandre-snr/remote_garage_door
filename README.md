# remote_garage_door
![image](https://user-images.githubusercontent.com/8344492/166564127-b232684c-c1e0-4898-9a14-d1aff1b58bef.png)

A simple Arduino script meant to be ran on an ESP32.  
It will connect to Wifi (don't forget to create a `secrets.h` file) and expose a web service on port 80.  
When a request is made on this server out the `/toggle_garage_door` route, it wills trigger a relay plugged on pin 23 for a second.  
Network configuration must be changed in `remote_garage_door.ino`.
