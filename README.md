# omg_cable_payload

The O.MG Cable is a pentesting tool.  

A wireless keylogger hidden inside a cable that leverages the power of the original O.MG cable so you can grab keystrokes, update payloads, and trigger keystroke injection attacks from anywhere.  

# Payload

#### [WINDOWS](https://github.com/julesbozouklian/omg_cable_payload/blob/main/windows/)

#### [LINUX](https://github.com/julesbozouklian/omg_cable_payload/blob/main/linux/)

#### [OSX](https://github.com/julesbozouklian/omg_cable_payload/blob/main/osx/)


# How to get started

#### 1) Download the last firmware
 - https://github.com/O-MG/O.MG_Cable-Firmware/releases

#### 2) Flash the firmware
 - Plug the O.MG Cable into programmer
 - Plug programmer into computer
 - Run : ``` python3 -m pip install pyserial```
 - Run : ``` python ./flash.py ```
 - Choose network mode (Access Point mode or Station mode)
 - When flash has finished unplug the programmer an plug cable to victim

#### 3) Network mode and access web ui
 - Access Point mode = you can connect to the SSID specified during setup and cable will be accessible at http://192.168.4.1
 - Station mode = the cable connects as a client and will be accessible on your network
