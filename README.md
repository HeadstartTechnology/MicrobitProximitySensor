# MicrobitProximitySensor
Code and files for the Microbit Proximity Sensor board 

The motivation for this project was to provide a fun and easy to use social distancing tool, for use in any environment where people need to gather but still need to maintain proper distancing (such as gyms, schools, offices, etc). The system works by sending out radio bursts at regular intervals using the built-in Bluetooth radio, and sounding an alarm if it detects the signal strength from another Microbit as being below a preset value (which is indicative of distance between the devices).

Microbits can be configured to use separate radio channels, so it is possible to configure 'bubbles' where individual Microbits only react to Microbits from a different bubble. Example code for these configurations will be uploaded shortly.

The Microbit is ideally suited as for this project as it incorporates all required sensors in an affordable and flexible package. The PCB in this project adds a buzzer for sound and batteries for power. Both V1 and V2 are supported.

Please see WIKI for code pictures or download hex files for makecode editor. 

The required electronic components and mechanical parts to build the Proximity Monitoring Board
 
| Component             |  PCB ID       |  Kitronik Stock Code   | Quantity |
| --------------------- | :-----------: | :--------------------: | :------: |
| Printed Circuit Board |               | 56108                  | 1        |
| AA Battery Holder     | BH1, BH2      | 2263                   | 2        |
| Piezo Buzzer          | BZ1           | 3308                   | 1        |
| JST Wire              | CN2           | 4159                   | 1        |		
| Slide Switch          | SW1           | 3422                   | 1        |
| M3 x 12mm Bolt        |               | 2314                   | 2        |
| M3 nut                |               | 2315                   | 2        |
| 6mm M3 nylon Spacer   |               | 2335                   | 2        |

Parts can be ordered from [Kitronik.co.uk](https://www.kitronik.co.uk)

A big Thank You to Phil, Kevin and the entire team at Kitronik for supporting this project!
