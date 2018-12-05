# [Problem based learning](#Connections#Tools used)

## Project theme (IOT):globe_with_meridians:

## Hardware Requirements

- [x] 3.3V and 5V Power Supply Module for MB102 Bread Board

- [x] NODEMCU-ESP8266 Wifi Development Board

- [x] 4 Channel 5V 10A Relay Module

- [x] Jumpers

- [x] Buzzers(9V)(for testing the circuit)

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
2.Google firebase
  Go through the link for getting started with google fire base make sure you read the doc file provided with this repository.
  
3.MIT APP inventer
  As google firebase is enabled with the features of supporting native apps thus making it easy for iot based application the building for the application is documented in the word file provided in the repository.
  


###### _dont forget to make changes while using for your projects as per the comments provided in .ino file in project folder_
###### Note: Don't share your Database Secret or else anyone can alter your database
