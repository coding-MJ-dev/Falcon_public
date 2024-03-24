# Project Falcon

![falcon](https://github.com/coding-MJ-dev/Falcon_public/assets/47417320/8187ea44-0721-47c2-96ad-7cc275363521)

: Rocket flight computer (Avionics)

: C++ / C project


**: Part of the UTS Rocketry Team project; code is not open to the public**


## GPS tracking##
: Rocket GPS tracking system 

: Real-time data transmission to the ground station


## LoRa radio Connection with Ground Station ##
Provides real-time data, including: 
   - state(on pad> ascending> apogee...) 
   - pressure
   - raw Altitude
   - Altitude 
   - vertical velocity
   - GPS


## State Machine ##
: Based on collected flight data

: Uses Kalman Filter to refine the data

: Consists of 5 states:

0. idle
1. ascending
2. apogee
3. descending
4. landed

  
## Components ##
1. microcontroller(MCU) - [ATtiny3217](https://www.snapeda.com/parts/ATTINY3217-MFR/Microchip/view-part/?ref=dk&t=ATtiny3217&con_ref=None)

2. LoRa radio - [LoRa](https://www.snapeda.com/parts/RFM95W-915S2/RF%20Solutions/view-part/?ref=search&t=Lora%20module)

3. GPS - [l80-m39](https://www.snapeda.com/parts/L80-M39/Quectel/view-part/?ref=quectel_in&t=l80-m39&con_ref=N)

4. Altimeter(barometer) - [BMP280](https://www.snapeda.com/parts/BMP280/Bosch/view-part/?ref=search&t=bmp280)



## Tool ##
1. VS code
3. Platform IO



