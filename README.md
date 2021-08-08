================================================================================
Optimus; Autonomous RC Car Project

"wiki excerpt: Radio/Remote-controlled cars (or RC cars for short) are miniature model cars or trucks that can be controlled from a distance using a specialized transmitter or remote. The term "RC" has been used to mean both "remote controlled" and "radio controlled", where "remote controlled" includes vehicles that are controlled by radio, infrared or a physical wire connection (the latter is now obsolete). "
================================================================================
A self-driving car prototype whose destination is configured over a mobile
application.
We use sensors to detect obstacles; GPS and compass to learn the car's
location and desired direction of movement.
The self driving solution is realised using five controllers each of which
have a dedicated task. The different controllers talk to each other in realtime
using high-speed CAN transceivers.

================================================================================
Platform
================================================================================
SJ One Board (ARM Cortex M3; LPC 1758 based carrier board; 
        more info: http://www.socialledge.com/sjsu/index.php?title=SJ_One_Board)

================================================================================
Modules
================================================================================
1) Master Controller
2) Sensor Controller & I/O
3) Bridge Controller + Mobile Application (Android)
4) Motor Controller (Servo)
5) Geo Controller (GPS, Compass)
