# OpenCart 2 Thai Language
This is OpenCart v.2 Thai translation on both admin (back-end) and catalog (front-end).

โครงการแปลไทยเปิดเสรีสำหรับ OpenCart 2 สำหรับคนไทยและผู้ที่อยากนำภาษาไทยไปใช้งานได้อย่างไม่ต้องเสียค่าใช้จ่าย.<br>
คุณสามารถมีส่วนร่วมในการแปลนี้ได้โดยการ Fork โครงการนี้ไปแปล แล้วทำการ Pull request กลับมาเพื่อตรวจสอบก่อนนำมาเผยแพร่ต่อไป.

รุ่นที่แปลล่าสุด: OpenCart 2.0.3.1<br>
สถานะ: 

|              | การแปล | ความสมบูรณ์                | หมายเหตุ                                                                                                                                                             |
|-----------|----------|----------------------------|----------------------------------------------------------------------------------------------------------------------------------------|
| /catalog |   95%+ | ยังไม่ได้ตรวจสอบ?         | บางส่วนเข้าใจว่าเป็นชื่อเฉพาะซึ่งเป็นภาษาอังกฤษ จึงไม่แปล จึงไม่สามารถครบ 100% ได้                                                     |
| /admin   |  80%+  | ยังไม่ได้ตรวจสอบ?         | บางส่วนเป็นชื่อเฉพาะและมีความหมายสำคัญ แปลแล้วอาจมีความหมายทับซ้อนกับคำอื่น จึงไม่แปล จึงไม่สามารถครบ 100% ได้   |

โครงการนี้ดำเนินการโดยผู้จัดทำเว็บไซต์ okvee.net

## การร่วมแปล
ให้คุณผู้ที่สนใจจะมีส่วนร่วม Fork โครงการนี้ไปแปล แล้วทำการ Pull request กลับมาเพื่อตรวจสอบก่อนนำมาเผยแพร่ต่อไป.<br>
**การแปลจะต้องไม่นำส่วนที่ผู้อื่นแปลไว้แล้วมาใส่ในนี้ ยกเว้นแต่จะได้รับอนุญาตเป็นลายลักษณ์อักษร และเจ้าของผู้แปลต้นฉบับนั้นจะต้องทราบว่าเราจะไม่มีการร้องขอเครดิตและส่งเครดิตใดๆให้.**<br>
ผู้มีส่วนร่วมแปลจะถือว่ารับทราบข้อตกลงนี้ และจะต้องรับผิดชอบการกระทำใดๆที่เป็นการละเมิดลิขสิทธิ์หรือผลงานผู้อื่นด้วยตนเอง. เจ้าของโครงการนี้จะไม่มีส่วนร่วมรับผิดชอบใดๆทั้งสิ้น.<br>
ข้อตกลงการร่วมแปลเขียนเมื่อ 1 ต.ค. 2558

## License
โครงการนี้ใช้การอนุญาตแบบ GPL v.3 ซึ่งให้สิทธิ์เสรีในการนำไปแก้ไข ทำซ้ำ เผยแพร่ภายในขอบเขตของ GPL v.3 โดยทั้งในเชิงพาณิชย์และไม่ใช่พาณิชย์.<br>
คุณสามารถนำไปใช้งานได้ฟรี! ไม่ว่าจะใช้ส่วนตัวหรือใช้ในเชิงพาณิชย์. คุณไม่จำเป็นต้องส่งลิ้งค์ใดๆกลับมา แต่ถ้าจะทำเราก็แค่ขอบคุณ.

## การติดตั้ง
เปิดเข้าไปในหน้า admin OpenCart ของคุณ เช่น `http://domain.tld/admin` .<br>
คลิกเข้าไปที่เมนู System > Localisation > Languages<br>
คลิกที่ปุ่ม + (Add New) แล้วเพิ่มรายละเอียดดังต่อไปนี้:<br>

    * Language Name: ไทย
    * Code: th
    * Locale: th
    * Image: th.png
    * Directory: thai
    * Status: Enabled
    * Sort Order: 1 หรือกรอกลำดับตามต้องการ

จากนั้นคลิกที่ปุ่ม Save
### การตั้งเป็นภาษาหลัก
จากหน้า admin OpenCart คลิกเข้าไปที่เมนู System > Settings<br>
คลิกที่ปุ่ม Edit บนบรรทัดของร้านค้าที่คุณต้องการแก้ไข<br>
คลิกที่แท็บ Local<br>
เลือกภาษาไทยเป็นภาษาหลักสำหรับหน้าเว็บ ให้เลือกที่ Langauge<br>
เลือกภาษาไทยเป็นภาษาหลักสำหรับหน้า admin ให้เลือกที่ Administration Langauge<br>
คลิกที่ปุ่ม Save