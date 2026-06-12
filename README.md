# Project-Nitro 🏎️💨
### FVP RC Racing car with game effects

---
Have you ever wondered having a **RC FVP Racing Car** with game effects such as :
* Boost
* Gun
* Health
* Drift ` Bad effects and more`

well i have made with the help of **NFC TAGS**, How it work is simple when each car have a NFC reader under, and when it pass over a NFC tage it will detect the code and look for what power or bad effect it is and then i will pull that effect and we can use any time we want.

# Photos of car and remote 📸

### Car pics
---
![car](/image/C1.png)

![car1](/image/C2.png)

![car2](/image/C3.png)


### Remote
---
![remote](/image/R1.png)

![remote1](/image/R2.png)

![remote2](/image/R3.png)

# Circuit Diagram

### Car
---
![car pcb](/image/CAR.png)

### Remote
---
![remote pcb](/image/RC.png)

# How to Play 🎮
```
When you turn one the remote and car it will connect (if its first time you may need to pair it)
and you will get a web in phone or laptop for fpv
and when it connect you will have two mode 
* Free ride
    you can drive it as normal RC car with out any things 
* Race mode
    In this mode you need to an opponet to play with you one of you will host the game 
    and that persons car will be the controller of the game also.
    and the remote will look for players.
    and when find a player user need to flip the car and re-register all nfc tag again.
    accept the win gate tag and the pit lane.
    and place everything in place as you want every where you can make your own
    track with anythiung you have 
    and play and win the game.

```

# How It Work. ⚙️


this all work with by ESP-NOW protocol 
the one who host the car will be the one  maintain the rules and everything 
and 

`car <->remote`

`car(host) <-> car(clint)`

`camera -> wifi web -> phone,laptop...`

# Folder 📁
## Car
---
### Car Cad
[car cad](/cad/car/)

### Car Firmware
[car cad](/firmware/car/)

### Fpv Camera
[camera](/firmware/car_cam/)

### car Circuit
[Circuit](/circuit/car/)

## Remote
---
### remote Cad
[remote cad](/cad/remote/)
### Remote Firmware
[remote firmware](/firmware/remote/)
### remote Circuit
[Circuit](/circuit/remote/)

# BOM (bill of material) 🛒
### Car
---
|**Item**|Number|Link|
|--------|-------------|---|
|5mm 940nm IR Emitter Transmitter|2|https://amzn.in/d/03gj3whx|
|MPU6050 IMU|1|https://amzn.in/d/0gS9H64g|
|PN532 NFC RFID Module|1|https://robokits.co.in/wireless-solutions/rfid/pn532-nfc-rfid-module-v3-kit-reader-writer-breakout-board?srsltid=AfmBOooBJS2DFnuWBIGC9mB0mO7za8Ql3MFEb6kDh34OEwg5jFQdKodmrjA|
|ESP32S3-Sense|1|https://www.seeedstudio.com/XIAO-ESP32S3-Sense-p-5639.html?srsltid=AfmBOooVpv6VY6S8HZ8RSQHJR3o-OCpF9PW-xqElodKlTDqwqZxqCzhl|
|ESP32 WiFi Bluetooth |1|https://amzn.in/d/0fkaqaUV|
|6V N20 600 RPM Motor|1|https://robocraze.com/products/6v-n20-600-rpm-miniature-gear-motor|
|3.7v 2500mah 18650 Li-Ion Battery|2|https://robocraze.com/products/3-7v-2500mah-18650-li-ion-battery|
|TP4056 Battery Charger|1|https://robocraze.com/products/tp4056-battery-charger-c-type-module-with-protection-1|
|LM2596 DC-DC Buck Converter|1|https://robocraze.com/products/lm2596-dc-dc-buck-module|
|SG90 Micro Servo Motor|1|https://robocraze.com/products/sg90-micro-servo-motor|
|DRV8833 2|1|https://robocraze.com/products/drv8833-2-channel-dc-motor-driver|
|TSOP38238 IR Receiver Diode|2|https://quartzcomponents.com/products/tsop38238-ir-receiver-diode-38khz|
|m3x4mm heat set inserts|8||
|M3 x 6mm screw|8||

### Remote
---
|**Item**|Number|Link|
|--------|-----|---|
|ESP32 WiFi Bluetooth|1|https://amzn.in/d/03HUoLg3|
|Tactile momentary push button|12|https://amzn.in/d/093r9Vyk|
|3.7V 1500mAH LiPo Rechargeable Battery Model |1|https://robocraze.com/products/3-7v-1500mah-lipo-rechargeable-battery-model-uk-523450p?_pos=1&_sid=d113ab62b&_ss=r|
|TP4056 Battery Charger |1|https://robocraze.com/products/tp4056-battery-charger-c-type-module-with-protection-1|
|3.3V Small Piezo Buzzer|1|https://robocraze.com/products/3-volts-buzzer-small|
|5mm Common Anode RGB LED 4Pin Through Hole White Diffused LED|1|https://robocraze.com/products/5mm-common-anode-rgb-led-4pin-pack-of-10|
|2.8 Inch TFT LCD Display|1|https://robocraze.com/products/smartelex-2-8-inch-tft-lcd-display-240x320-color-lcd-screen-for-diy-electronics|
|m3x4mm heat set inserts|5||
|M3 x 6mm screw|5||

# Future Upgrade ⏫
* Leader Board 
* Anti-Cheat
* challacnge etc

Thats it for now.
