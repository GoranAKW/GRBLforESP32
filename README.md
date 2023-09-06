# GRBLforESP32
How i implement GRBL for ESP32

1. Download VScode from https://code.visualstudio.com/download and install

2. Download or clone Bart Drings wonderful port of GRBL for the ESP32 from https://github.com/bdring/Grbl_Esp32
   git clone https://github.com/bdring/Grbl_Esp32.git

3. Then add my ESP32 boards Machines/GCan_Cnc_Shield_xxxx.h file to the code and edit the Machines file to point at it.
   #  include "Machines/GCan_Cnc_Shield_V1.3.h" // was  include "Machines/test_drive.h"

4. Select the board and upload

5. When you restart the board a new WI-FI Access Point is automatically set up with the password 12345678

6. IF you don´t see the web interface enter the /data folder and upload both files: favicon.ico and index.html.gz

7. Restart and you'll se the interface

8. Start play around and have fun ;-)
