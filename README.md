# Ready to use Anemometer with alarm (Comming soon)

![Anemometer with alarm](https://www.imiconsystem.com/wp-content/uploads/2022/08/alarm.jpg)

Anemometer with alarm | วัดความเร็วลม เพื่อการแจ้งเตือน หรือควบคุมสั่งการอัตโนมัติ พร้อม Web Monitoring & WiFi management สำหรับ New Micromation Dev Board V.2 Lite with ESP32 ใช้ในการแสดงผลค่าต่างที่วัดได้ และการตั้งค่าต่างๆ ผ่านเว็บบราวเซอร์

## ฟีเจอร์การแสดงผล
- แสดงผลค่าความเร็วลม
- แสดงสถานะการควบคุมสั่งงานผ่าน RELAY
- แสดงสถานะเงื่อนไขสั่งงานที่ได้ตั้งค่าไว้ล่วงหน้า

## ฟีเจอร์การตั้งค่า
- ตั้งค่าการเชื่อมต่อ WiFi
- ตั้งค่าเงื่อนไขสั่งงาน RELAY
- ตั้งค่าชื่อและไอดีอุปกรณ์
- การตั้งค่าผ่าน WiFi AP Mode


## Compatible hardware
1. บอร์ดพัฒนา New Micromation Dev Board V.2 Lite with ESP32 [สั่งซื้อ](https://www.imiconsystem.com/product/new-micromation-dev-board-v-2-lite-with-esp32-and-enclosure/)
![New Micromation Dev Board V.2 Lite with ESP32](https://github.com/imiconsystem/micromation-rs485-weather-station/blob/bdf550019d738539710d173fe2b3f02d10287b3d/images/20220909_152200.jpg)

2. RS-FS-N01 RS485 Modbus เซ็นเซอร์วัดความเร็วลม Wind Speed Sensor [สั่งซื้อ](https://www.imiconsystem.com/product/new-micromation-dev-board-v-2-lite-with-esp32-and-enclosure/)
![RS-FS-N01 RS485 Modbus เซ็นเซอร์วัดความเร็วลม Wind Speed Sensor](https://www.imiconsystem.com/wp-content/uploads/2020/10/RS-FS-N01-3.jpg)

## Hardware setup

ใช้ Micromation – Lite with RS-485 Module ต่อใช้งานร่วมกับ Wind Speed Sensor RS-FS-N01 ผ่าน RTU / RS-485 ด้วยโปรโตคอล Modbus Protocol โดยใช้คอนโทรลเลอร์ ESP32 Dev Kit V1

** โปรดระมัดระวัง! อย่าต่อแหล่งจ่ายไฟ Power in และ usb ในเวลาเดียวกัน เพราะจะส่งผลให้บอร์ดได้รับความเสียหาย ในบางครั้งอาจรวมไปถึงคอมพิวเตอร์

### การต่อแบบปลอดภัย สำหรับใช้ในการทดสอบและพัฒนา

- วีธีการนี้ จะถอดแหล่งจ่ายไฟหลักออก แล้วใช้ micro usb สำหรับการจ่ายไฟบอร์ดและการทดสอบพัฒนา อ่านค่า Debug  , ใช้แหล่งจ่ายไฟภายนอกต่อกับเซ็นเซอร์

![การต่อแบบปลอดภัย สำหรับใช้ในการทดสอบและพัฒนา](https://www.imiconsystem.com/wp-content/uploads/2022/06/how2power-p1.png)



### การต่อแบบปลอดภัย สำหรับการใช้งานจริง
- วีธีการนี้เป็นลักษณะของการพัฒนาที่เสร็จสิ้นแล้ว โดยถอด micro usb ออก แล้วใช้แหล่งจ่าย DC Jack 9-28V ต่อเข้าที่ช่อง Power in โดยระดับแรงดันนี้ จะสัมพันธ์กับ Power out ที่ใช้จ่ายไฟให้กับเซ็นเซอร์

** โปรดสังเกตว่าเซ็นเซอร์ของคุณรองรับแรงดันในย่านนี้หรือไม่
![การต่อแบบปลอดภัย สำหรับการใช้งานจริง](https://www.imiconsystem.com/wp-content/uploads/2022/06/how2power-p2-460x460.png)


## Software setup
(Comming soon)

## การใช้งานตั้งค่า
(Comming soon)
