# Problem based learning 

## Project theme (IOT):globe_with_meridians:

## Hardware Requirements

> 3.3V and 5V Power Supply Module for MB102 Bread Board

> NODEMCU-ESP8266 Wifi Development Board

> 4 Channel 5V 10A Relay Module

>Jumpers

>Buzzers(9V)(for testing the circuit)

## Connections
![connections](https://github.com/Preetam2114/Chemistry-PBL/blob/master/project/connections.png?raw=true)




## Software part
## Tools used:
1.Arduino ide 
  - Installation:
  ```
  Download the latest arduino ide form [here](https://www.arduino.cc/en/Main/Software)
  ```
  - Code:
  The .ino file is already provided in the repository just make sure to edit ****** part the following code based on your requiremnts
  ```
  #define FIREBASE_HOST "*****************************" 
  #define FIREBASE_AUTH "*****************************"
  #define WIFI_SSID "*****"
  #define WIFI_PASSWORD "************"
  :
  :
  String chipId = "IOT";
  ```
  


###### _dont forget to make changes while using for your projects as per the comments provided in .ino file in project folder_
###### Note: Don't share your Database Secret or else anyone can alter your database
