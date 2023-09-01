# Domoticz-dzVents-Omnik
Domoticz DzVents script to connect to some local Omnik inverters

this script supports local Omnik inverter with line beginning with myDeviceArray[0] or webdata=
in contents from link http://IP-Inverter/js/status.js

Instructions: 
- Copy/Paste this script into a new dzvents script through events editor (menu Setup-More options-Events)

- Create a dummy electricity instant and counter device And fill IDX in line 21 

- Fill IP address of your local Omnik Inverter in line 20

- comment/uncomment for myDeviceArray[0] or webdata= in line 38/39


Based on Omink plugin https://github.com/sincze/Domoticz-Omnik-Local-Web-Plugin
