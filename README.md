# Project-Nitro 🏎️💨
### FVP RC Racing car with game effects

---
Have you ever wondered having a **RC FVP Racing Car** with game effects such as :
* Boost
* Gun
* Health
* Drift ` Bad effects and more`

well i have made with the help of **NFC TAGS**, How it work is simple when each car have a NFC reader under, and when it pass over a NFC tage it will detect the code and look for what power or bad effect it is and then i will pull that effect and we can use any time we want.And beat the oppont and win with the supwer power and using our own strategy to win the game 
# Zine
[zine](/doc/zine.pdf)
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

# Motivation
>I have always wondered to play **RC car** like in games with boost,power, win, health etc.. bcz that all make more fun to the world and playing with friends make it more fun so i build this car, and it will give you a game vibe with rc fvp car irl, bring more fun and joy to the world

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
# Game Effects ⚡
### Good power
- Boost `Speed boost to move faster`
- Health ` get more health `
- Sheld `protection from enemy bullets`
- Buttels` to shoot`
### Bad Effects
- Drift` the car get drift randomly`
- Random controll `  the controll get switch randomly forward will be backward`
- Slowness`car goes slowly`
- Damagae ` low health`

### Bonues
- all bad effect can be  clear by going to your own pit lane.
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

## BOM
[BOM](/doc/BOM.csv.csv)

# BOM 🛒

### Car
---
|**Item**|Number|Approx. Price|Link|
|--------|-------------|-------------|---|
|5mm 940nm IR Emitter Transmitter|2|₹140|https://amzn.in/d/03gj3whx|
|MPU6050 IMU|1|₹174|https://amzn.in/d/0gS9H64g|
|PN532 NFC RFID Module|1|₹425|https://robokits.co.in/wireless-solutions/rfid/pn532-nfc-rfid-module-v3-kit-reader-writer-breakout-board?srsltid=AfmBOooBJS2DFnuWBIGC9mB0mO7za8Ql3MFEb6kDh34OEwg5jFQdKodmrjA|
|ESP32S3-Sense|1|₹1800|https://www.seeedstudio.com/XIAO-ESP32S3-Sense-p-5639.html?srsltid=AfmBOooVpv6VY6S8HZ8RSQHJR3o-OCpF9PW-xqElodKlTDqwqZxqCzhl|
|ESP32 WiFi Bluetooth|1|₹299|https://amzn.in/d/0fkaqaUV|
|6V N20 600 RPM Motor|1|₹149|https://robocraze.com/products/6v-n20-600-rpm-miniature-gear-motor|
|3.7v 2500mah 18650 Li-Ion Battery|2|₹500|https://robocraze.com/products/3-7v-2500mah-18650-li-ion-battery|
|TP4056 Type-C Mini|1|₹49|https://robocraze.com/products/tp4056-battery-charger-c-type-module-with-protection-1|
|LM2596 DC-DC Buck Converter|1|₹79|https://robocraze.com/products/lm2596-dc-dc-buck-module|
|SG90 Micro Servo Motor|1|₹99|https://robocraze.com/products/sg90-micro-servo-motor|
|DRV8833 2|1|₹99|https://robocraze.com/products/drv8833-2-channel-dc-motor-driver|
|TSOP38238 IR Receiver Diode|2|₹50|https://quartzcomponents.com/products/tsop38238-ir-receiver-diode-38khz|
|m3x4mm heat set inserts|20|||
|M3 x 6mm screw|20|||

#### Approximate Car Cost
**₹3963**

### Remote
---
|**Item**|Number|Approx. Price|Link|
|--------|-----|-------------|---|
|ESP32 WiFi Bluetooth|1|₹299|https://amzn.in/d/03HUoLg3|
|Tactile momentary push button|12|₹36|https://amzn.in/d/093r9Vyk|
|3.7V 1500mAH LiPo Rechargeable Battery Model|1|₹350|https://robocraze.com/products/3-7v-1500mah-lipo-rechargeable-battery-model-uk-523450p?_pos=1&_sid=d113ab62b&_ss=r|
|TP4056 Type-C Mini|1|₹49|https://robocraze.com/products/tp4056-battery-charger-c-type-module-with-protection-1|
|3.3V Small Piezo Buzzer|1|₹30|https://robocraze.com/products/3-volts-buzzer-small|
|5mm Common Anode RGB LED 4Pin Through Hole White Diffused LED|1|₹15|https://robocraze.com/products/5mm-common-anode-rgb-led-4pin-pack-of-10|
|2.8 Inch TFT LCD Display|1|₹780|https://robocraze.com/products/smartelex-2-8-inch-tft-lcd-display-240x320-color-lcd-screen-for-diy-electronics|
|m3x4mm heat set inserts|5|₹30||
|M3 x 6mm screw|12|₹30||

#### Approximate Remote Cost
**₹1619**

### Total Approximate Cost
---
|Part|Cost|
|-----|-----|
|Car|₹3963|
|Remote|₹1619|

# Future Upgrade ⏫
* Leader Board 
* Anti-Cheat
* challacnge etc

Thats it for now.
> **NOTE:** you need to place a black transperent plastic thin sheat or ssomething on the front window where the camera is placed and in the remote for the switch you can either use this ![pcb](/image/image.png) or you can custom print a pcb board everything on car and remote is either snap fit or screwable and only the led , ir and batter need glue-gun/tap