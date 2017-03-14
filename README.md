# LEDTable
the code that controls a LED enabled table. This table will do everything!!!

Current idea:
Program the BBB to control the leds on the table. Create PCB to connect BBB to table. Create power supply for the entire system. Enable the BBB to connect to WIFI

BBB Details:
Power is broken out to the the header pins no need for barrel connector
BBB IO pins are 3.3 needed line shifter
Power requirements 
Min: 5V @ .5A
Recommend 5V @ 1.2A
Max if using USB 5V @ 2A

Helpful links:
http://elinux.org/Beagleboard:BeagleBoneBlack 
https://learn.adafruit.com/search?q=BeagleBone%20Black&



Table details 

LEDS:
https://www.adafruit.com/products/1461#technical-details-anchor

Maximum 5V @ 60mA draw per 0.65" strip segment (all LEDs on full brightness)
Table dimensions 24”X4X2 = 192”
Current draw (worst case)
192” / .65 = 295.38 *  0.060A = 17.723
Total power = 17.75A * 5 = 88.75W 

Power supply requirements
LEDS
5V @ 18A 
