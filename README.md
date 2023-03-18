# AutoPlant
Code for an Automatic Plant Watering System, designed using an Arduino MKR Wifi 1010. Harnesses the power of IoT and the Cloud to perform its task anywhere, anytime.

Implemented with a waterproof pump, soil sensor, LDR (light capacitor), and Arduino Cloud. Checks to see if the soil is saturated enough for the plant (aka is it watered?); if so, keep reading until the plant needs it, else water the plant for a set time until the soil is back to its normal saturation level. Also returns the temperature, humidity, and light readings for the user, along with a helpful message in the IoT Dashboard indicating if the water has been dispensed to the plant or not (No water needed: not watered, Water needed: watered). These readings will serve useful for when the user is away from home and wishes to know the conditions around the plant as well as whether it is properly being watered or not. All readings are saved to the Arduino IoT Dashboard in which the user can access through mobile or computer. Coded using Arduino C.

Dashboard Example:


Video:
