Hello reader!

This project was made as part of the Hack Club Macondo hardware event. 
The main idea was that I wanted to familiarize myself with design of RF related applications on PCBs.

The board has the following central components: 
NEO-N9M GPS module 
USB Type-C connector 
MT3608 Boost converter 
ESP32-C3-WROOM 
2 SMA jacks for antennas (LORA and GPS) 
AMS1117-3.3 LDO 
DL-RFM95 LORA transceiver

These components allow the board to recieve its GPS position, do some computation then transmit using built in wifi or bluetooth or even using LORA signal up to 5km!
Useful in scenarios like a missing hiker who needs to tell others where they are, or if you have a rocket thats drifted out of your predicted landing zone and you need to find it.

<img width="1009" height="599" alt="Screenshot 2026-05-27 at 4 51 59 PM" src="https://github.com/user-attachments/assets/36c8acbd-04e1-4ace-8039-e991dc403b70" />
<img width="1009" height="599" alt="Screenshot 2026-05-27 at 4 51 49 PM" src="https://github.com/user-attachments/assets/0a9cd6f0-a0ee-4f62-a9f4-c494b4468152" />
<img width="1009" height="599" alt="Screenshot 2026-05-27 at 4 51 35 PM" src="https://github.com/user-attachments/assets/ed4a13e2-4923-45ea-8cfe-5bc74baaa7d4" />
