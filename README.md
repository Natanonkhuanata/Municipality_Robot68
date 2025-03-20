## การเเข่งขันหุ่นยนต์ องค์กรปกครองส่วนท้องถิ่น พ.ศ.2568

เป็นการเเข่งขันหุ่นยนต์ Logistics ภารกิจคือการนำกระป๋องที่เก็บได้ไปวางเข้าหลุมวงกลมที่สร้างไว้ใน box ที่มีความสูงต่างกันเเละต้องเเยกสีกระป๋อง เพื่อวางให้ตรงตำเเหน่งของสีกระป๋องนั้น
โดยผมได้ใช้ Arduino ที่เป็น ภาษา C  เป็น software ในการเขียนโปรเเกรมเพื่อควบคุมการทำงานของ Robot


# ส่วนๆต่างๆใน Robot

 - Microcontroller  is  POP-32i
 - MPU6050
 - Ultrasonic
 - Sensor 
 - Arm Robot
 - TCS34752
 - Battery Lithium-ion  11000  mAh
 - Motor

## GitHub สำหรับติดตั้ง POP-32i

>https://github.com/INEXdev/ArduinoSTM32/raw/main/package_inex_stm32_index.json



## Library ต่างๆสำหรับ Robot

 - Adafruit_TCS34725.h
 - POP-32i
 
 ## Code ที่สำคัญ
 
 - การจูน  Robot กับเส้น
 - การ Reset  MPU6050 ก่อนทำการปล่อย Robot
 - Function สำหรับการเลี้ยว MPU60550
 - Technical  การวางกระป๋อง

