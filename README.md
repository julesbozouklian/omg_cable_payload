# omg_cable_payload

The O.MG Cable is a pentesting tool.  

A wireless keylogger hidden inside a cable that leverages the power of the original O.MG cable so you can grab keystrokes, update payloads, and trigger keystorke injection attacks from anywhere.  

# Payload

#### [WINDOWS](https://github.com/julesbozouklian/omg_cable_payload/blob/main/windows/index.md)

#### [LINUX](https://github.com/julesbozouklian/omg_cable_payload/blob/main/linux/index.md)

#### [OSX](https://github.com/julesbozouklian/omg_cable_payload/blob/main/osx/index.md)


# How to get started

#### 1) Download the last firmware
 - https://github.com/O-MG/O.MG_Cable-Firmware/releases

#### 2) Flash the firmware
 - Plug the O.MG Cable into programmer
 - Plug programmer into computer
 - Run : ``` python3 -m pip install pyserial```
 - Run : ``` python ./flash.py ```
 - When flash has finished unplug the programmer an plug cable to victim

#### 3) Choose network mode and access web ui
 - Access Point mode = you can connect to the SSID specified during setup and cable will be accessible at http://192.168.4.1
 - Station mode = the cable connects as a client and will be accessible on your network
