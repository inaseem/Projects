# Offline JouleTrack
**Note: Source code is available as a private repo due to company policy.**

Design and develop the UI and Rest APIs of the application to run locally without the need of internet. The application should be capable of displaying data as well as send commands to 
respective devices. The whole application resides in the frontend directory and uses very light frameworks for development.

The data of the HVAC Component displayed is fetched and commands are sent to the component via a MQTT broker. The frontend has its own MQTT client for the same.

## Screenshots

![alt text](project.png?raw=true "Final Product Screenshot")

## Routing

Application uses minimal routing and is served by **Nginx webserver** at the hostname `smartjoules.local`.

