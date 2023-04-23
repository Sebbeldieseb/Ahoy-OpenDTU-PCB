# Ahoy-OpenDTU-PCB
PCB's Reference Board 3.1 for AHOY and OpenDTU

![grundplatine](https://user-images.githubusercontent.com/128978195/233839727-f152b595-b036-460b-bcde-d29d8a39294e.jpg)


## **- PCB**

The board is designed for AHOY & OPEN DTU software.
You will find the project here:
- [Ahoy](https://github.com/lumapu/ahoy) 
- [OpenDTU](https://github.com/tbnobody/OpenDTU)

This board is designed for 230V or 5V.
The nRF has a theoretical range of 2Km.
If there is good W-LAN reception in the vicinity, an ESP32-WROOM-32D is sufficient.
If this is not the case, an ESP32-WROOM-32U should be used.
Properly assembled with a DK-0400, the DTU is min. IP64


## **- Spec**

### **Connections:**
- I2C for an Oled Display (0.96" or 1,3") 
- HSPI for an Epaper (1.54") from Waveshare
- UART
- ESP32-WROOM-32U or ESP32-WROOM-32D
- nRF24L01+ for E01-ML01DP5
- Status LED's 2pcs
- Voltage LED's 2pcs
- Terminal 5V RM5mm
- Terminal 230V RM5mm
- Power supply 230V for MeanWell IRM-03-5
- Fuse holder for STV PTF/45

### **Board Info:**
- Base Material FR4
- Layers 2
- Color Green
- Surface Finish EING Gold 1U
- Voltage transformer incl. capacitor
- 2x female connector 1x19 Gold plated 
- 1x female connector 2x8 Gold plated
- 2x male header 1x4 Gold plated

### **NRF Assignment:**
- CSN = IO5
- MOSI = IO23
- IRQ = IO16
- MISO = IO19
- SCK = IO18
- CE = IO4

### **I2C Assignment:**
- SCL = IO22
- SDA = IO21

### **HSPI Assignment:**
- MOSI = IO13
- CLK = IO14
- CS = IO15
- DC = IO27
- RST = IO26
- MISO = IO12

### **LED Assignment:**
- IO34 & IO35



## **- Material list:**

- #1.0 Housing Hensel DK-0400
- #1.1 2x device screws

### **ESP32:**
- #2.0 ESP32-WROOM-32D
- or
- #3.0 ESP32-WROOM-32U
- #3.1 Antenna 3DBi Female
- #3.2 cable IPEX to SMA male
- #3.3 cable gland M20

### **nRF24L01+:**
- #4.0 E01-ML01DP5
- #4.1 Antenna 3DBi Female
- #4.2 Cable gland M20

### **Power supply connection:**
- #5.0 USB cable for ESP (5V)
- or
- #6.0 USB cable for terminal (5V)
- #6.1 Terminal RM5.0 (2 ports)
- #6.2 Cable gland
- or
- #7.1 Terminal RM5.0
- #7.2 Power supply IRM-03-5 Meanwell
- #7.3 Fuse STV PTF/45
- #7.4 Cable gland M25
- #7.5 Fuse 0.1A carrier
- #7.6 H07RN-F 3G 1,5mm
- #7.7 6x 1,5mm ferrules
- #7.8 Betteri BC01

### **Voltage LEDs:**
- #8.0 LED Nichia NSPG500DS-G Green 
- #8.1 Resistance min. 91OHm

### **Status LED's:**
- #9.0 LED 5034Y1C-BUB-E Yellow
- #9.1 Resistance min. 194Ohm
- #10.0 LED 5034G3C-BUA-B Green
- #10.1 Resistance min. 120Ohm

### **Oled Display:**
- #11.0 Oled Display 0.96"
- #11.1 4x Jumper wire Female-Female
- #12.0 Oled Display 1,3"
- #12.1 4x Jumper wire Female-Female

### **Epaper Dispaly:**
- #13.0 Epaper 1.54" by Waveshare

 ![5VUSB](https://user-images.githubusercontent.com/128978195/233839863-2da0a462-f2bb-4c8b-a733-295cf00c2d24.jpg)
 ![5Vextern](https://user-images.githubusercontent.com/128978195/233839870-f2748273-152f-439c-8eb7-daa69d06c2ab.jpg)
 ![230V](https://user-images.githubusercontent.com/128978195/233839874-fc1e40e9-9f51-4bfe-b1ef-1f40ffc6fa0d.jpg)


## **the finished DTU 3.0:**
The DTU can be look like this:

![finshed3 0](https://user-images.githubusercontent.com/128978195/233840594-1e035af2-6614-4f36-8047-13cd7dd13ef5.jpg)


## **- Software:**

[- Ahoy](https://github.com/lumapu/ahoy) 
[- OpenDTU](https://github.com/tbnobody/OpenDTU)
