# AutoPlant
Code for an Automatic Plant Watering System, designed using an Arduino MKR Wifi 1010. Harnesses the power of IoT and the Cloud to perform its task anywhere, anytime.

Implemented with a waterproof pump, soil sensor, LDR (light capacitor), and Arduino Cloud. Checks to see if the soil is saturated enough for the plant (aka is it watered?); if so, keep reading until the plant needs it, else water the plant for a set time until the plant has adequate water. Also returns the temperature, humidity, and light readings for the user, along with a helpful message in the IoT Dashboard indicating if the water has been dispensed to the plant or not (No water needed: not watered, Water needed: watered). A red / green light will appear depending on whether the plant requires water or not. These readings will serve useful for when the user is away from home and wishes to know the conditions around the plant as well as whether it is properly being watered or not. 

The system's dependence on soil moisture to water the plant was also designed in part to address the recent wave of droughts that California is under, for it waters only when needed, and not in excessive - thus saving overall water costs for the user and also maintaining a sustainable solution for watering plants during time of droughts by conserving the excess water.

All readings are saved to the Arduino IoT Dashboard in which the user can access through mobile or computer. Coded using Arduino C.

IoT Dashboard Example:
![Screen Shot 2023-03-17 at 7 19 50 PM](https://user-images.githubusercontent.com/94002108/226078130-f902af45-1394-4635-bcec-b6c0adabd847.png)

Demonstration Video:
https://drive.google.com/file/d/12o2zM-1WTmAWngMMZ_62iI6WTVzGmSHP/view?usp=sharing

Materials Used:
1. Arduino MKR Wifi 1010
2. Arduino IoT Cloud
3. Jumper Wires, Breadboard Type (Male & Female wires)
4. Capacitative Soil Moisture Sensor
5. BME280 Sensor
6. Mosfet Board
7. RGB Sensor
