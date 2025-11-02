# Hexapod-v1
Its a hexapod with an auto aiming turret on its head. At first it will just be an RC hexapod, but my final goal is to make it somewhat autonomus with the rassberypie. (being able to follow smth and shoot it while avoiding obsticles) 

At first i was going to make an auto aiming trashcan after seing a youtube video but then i realized i dont have enough space in my house. if i make that the trashcan cant move around enough and it wont work. Then i though of building an auto aiming gun which is basically an auto aiming turret. Later I saw a short by @MakeYourPet showing a hexapod which looked really cool. So i decided to combine the two ideas and mount the auto aiming turret on a hexapod. 

Im taking the 3d model for the hexapod from an open sourced project by @MakeYourPet. I'm not designing my own 3D model because its too complex for me and I dont have a 3d printer to test prototypes and make small tweaks instantly. So im taking the design from an open source project, but everything else I will do it myself. The programing the auto aiming turret (ill use a gel blaster for the turret. Ill make a prototype with cardboard and popsticle sticks and then try to model a clean shell for it) I wont be using @MakeYourPet's app to power  my hexapod cause thats bascially just a full cheatcode since all the Inverse kinematics and everything else is already done. Im just using the 3d model and everything else will be my own work. Hope thats alright. Here is a picture of how the hexapod looks: <img width="1071" height="1204" alt="Pink" src="https://github.com/user-attachments/assets/151383d2-13c5-4b16-93c1-6cba74c23fbd" />

Im not using a custom PCB for this project. I have a rough wiring diagram though: <img width="1920" height="1080" alt="Final Wiring for hexapod" src="https://github.com/user-attachments/assets/02d9bc55-4f6e-4de0-8ca1-58850187e2ae" />

And here is my BOM: https://docs.google.com/spreadsheets/d/1QqpDV4mF5TNlVFBX8wkorOzyv_0cyz_nEEIMEz1E2uM/edit?usp=sharing  
| Name | Amount | Link | Price (CAD, Discount ends Nov 8) |
|------|-------:|------|--------------------------------:|
| DS3235 35KG Servos | 21 | [AliExpress](https://www.aliexpress.com/item/1005007556657180.html) | 483 |
| Ultrasonic Sensor HCSR04 | 6 | [AliExpress](https://www.aliexpress.com/item/1005005467178145.html) | 10 |
| 2S 5000mAh 50C XT60 Lipo Battery | 1 | [AliExpress](https://www.aliexpress.com/item/4000389770504.html) | 29 |
| Pololu Mini Maestro 24-Channel USB Servo Controller | 1 | [CanadaRobotix](https://www.canadarobotix.com/products/104?variant=14423512711217) | 71 |
| Waveshare IMX219 Camera Module | 1 | [Amazon](https://www.amazon.ca/Waveshare-IMX219-Camera-Official-Raspberry/dp/B07H2D4WYR) | 22 |
| 200cm Portable Mini USB Mic | 1 | [AliExpress](https://www.aliexpress.com/item/1005005732034743.html) | 3 |
| Mini Portable Travel Loud Speaker | 1 | [AliExpress](https://www.aliexpress.com/item/1005007091728840.html) | 2 |
| Logitech G F310s | 1 | [Logitech](https://www.logitechg.com/en-ca/shop/p/f310-gamepad) | 30 |
| HTRC iMAX B6 80W Battery Charger | 1 | [AliExpress](https://www.aliexpress.com/item/32814573731.html) | 27 |
| 9-DOF Absolute Orientation IMU | 1 | [AliExpress](https://www.aliexpress.com/item/1005006770124726.html) | 10 |
| Gel Blaster | 1 | [AliExpress](https://www.aliexpress.com/item/1005006560659642.html) | 18 |
| XT60 Inline Fuse | 1 | [AliExpress](https://www.aliexpress.com/ssr/300000512/BundleDeals2?productIds=1005006982312712:12000038933774573) | 7 |
| 30A 12V 24V Battery Main Switch | 1 | [AliExpress](https://www.aliexpress.com/item/1005002306337951.html) | 2 |

**Total:** 714 CAD  
**Grant Coverage:** 400 USD ≈ 560 CAD  
**Personal Contribution:** 154 CAD

