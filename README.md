# MicrobitProximitySensor
Code and files for the Microbit Proximity Sensor board 

The motivation for this project was to provide a fun and easy to use social distancing tool, for use in any environment where people need to gather but still need to maintain proper distancing (such as gyms, schools, offices, etc). The system works by sending out radio bursts at regular intervals using the built-in Bluetooth radio, and sounding an alarm if it detects the signal strength from another Microbit as being below a preset value (which is indicative of distance between the devices).

Microbits can be configured to use separate radio channels, so it is possible to configure 'bubbles' where individual Microbits only react to Microbits from a different bubble. Example code for these configurations will be uploaded shortly.

The Microbit is ideally suited as for this project as it incorporates all required sensors in an affordable and flexible package. The PCB in this project adds a buzzer for sound and batteries for power. Both V1 and V2 are supported.

Please see WIKI for code pictures or download hex files for makecode editor. 
