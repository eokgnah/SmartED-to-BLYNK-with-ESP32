# SmartED-to-BLYNK-with-ESP32
SmartED CAN-BUS Data Sniffer and Sender to Blynk Server over ESP32 WIFI 

<img src="https://github.com/eokgnah/SmartED-to-BLYNK-with-ESP32/blob/master/SmartED-Blynk.jpg" width="350"><img src="https://github.com/eokgnah/SmartED-to-BLYNK-with-ESP32/blob/master/SmartED-ESP32.jpg" width="350">

Pin Usage

 * MCP2515  = WEMOS ESP32
 * VCC      =       5V
 * GND      =      GND
 * CS       =       P5
 * SO       =      P19
 * SI       =      P23
 * SCK      =      P18
 * INT      =      P22


The Blynk-Server recieves all values as "virtual pins".

You can use them to display all you want in notime on your smartphone or tablet.

They are sent every 10sec over the ESP32 WIFI to the Blynk-Server:

The sniffed values are seperated by "*".

1. Odometer (km)
2. Range (km)
3. Poverlevel as in the middle instrument (33%, 66%, 99%)
4. Amperes coming/going to the traction battery (A) 
5. Volts of the traction battery (V) 
6. Calculated power coming/going to the traction battery (W)
7. Battery state of charge as in the middle gauge (%)
8. Real internal state of charge of the battery (%)
9. ECO Value over all (%)
10. ECO Value breaking (%)
11. ECO Value rolling (%)
12. ECO Value accelerating (%)
