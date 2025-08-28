## Project by :  Adi Iskandar,Omran janadi, Senial Yassin
  
## Details about the project:
This IoT project uses an ESP32 with a DHT11/DHT22 sensor to measure temperature and humidity.  
The ESP32 runs Micropython, reads sensor values periodically, and sends them with exact timestamps to Firebase Realtime Database.  
A simple web dashboard displays the data in real time and provides alerts when temperature or humidity cross critical thresholds.

 
## Folder description :
* ESP32: source code for the esp side (firmware).
* Documentation: wiring diagram + basic operating instructions
* Unit Tests: tests for individual hardware components (input / output devices)
* flutter_app : dart code for our Flutter app.
* Parameters: contains description of parameters and settings that can be modified IN YOUR CODE
* Assets: link to 3D printed parts, Audio files used in this project, Fritzing file for connection diagram (FZZ format) etc

## ESP32 SDK version used in this project: 

## Arduino/ESP32 libraries used in this project:
* XXXX - version XXXXX
* XXXX - version XXXXX
* XXXX - version XXXXX

## Connection diagram: 

- DHT11/DHT22 VCC → ESP32 3.3V  
- DHT11/DHT22 GND → ESP32 GND  
- DHT11/DHT22 Data → ESP32 GPIO4 (configured in code)  


## Project Poster:
 
This project is part of ICST - The Interdisciplinary Center for Smart Technologies, Taub Faculty of Computer Science, Technion
https://icst.cs.technion.ac.il/
