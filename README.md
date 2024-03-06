# Tutorial-10-Embedded-Systems-and-IoT
**การใช้ IoT platform Blynk หรือ Anto.io**


**Objectives**
1. เขียนโปรแกรมเพื่อเชื่อมต่อ IoT platform ได้

**Hardware**
1.	ESP32                 1	        
2.	อุปกรณ์ตามต้องการ        1
3.	Breadboard            1
4.	Computer	            1
5.	microUSB	            1

**Software**
1. Arduino IDE v
--------------------
**Instruction**

**กรณีใช้ Blynk**
1. ติดตั้ง library ของ Blynk platform โดยพิมพ์คำว่า Blynk ในช่องค้นหา library แล้วเลือกติดตั้ง "Blynk by Volodymyr ShymanSkyy" เวอร์ชันล่าสุด แต่หากพบ error ให้ใช้เวอร์ชัน 1.2.0
2. สมัครใช้งาน Blynk ที่ https://blynk.io
3. หลังจากเข้าสู่ระบบ สามารถศึกษาการใช้งานระบบจาก Quickstart ได้ทันที ซึ่งจะสอนการเพิ่ม device ให้ด้วย แต่หากไม่ได้ทำตาม Quickstart สามารถคลิกปุ่ม "+ New Device" สีเขียวด้านบนขวาในหน้าต่าง Devices ได้ <br> ![image](https://github.com/keeratiburt/Tutorial-10-Embedded-Systems-and-IoT/assets/125423996/b2f6f36c-a4ce-4375-a21f-2227ada4fe82)
4. เลือก "From Template" จากนั้นกรอกดังรูป <br> ![image](https://github.com/keeratiburt/Tutorial-10-Embedded-Systems-and-IoT/assets/125423996/947af05f-9730-4592-aaf6-afa54cb0cc8e)
5. คลิกเข้าไปที่ device ที่สร้างขึ้นเพื่อเข้าไปยังหน้ารายละเอียด ดังรูป ![image](https://github.com/keeratiburt/Tutorial-10-Embedded-Systems-and-IoT/assets/125423996/84fbfad8-d916-49a9-bae5-ac5c2322a60e)
6. คลิกที่จุด 3 จุดด้านหลังชื่อ device และเลือก "Edit Dashboard"
7. ในหน้านี้ สามารถออกแบบเลือก widget ได้ตามที่ต้องการให้สอดคล้องกับค่าที่ได้จาก ESP32 สามารถกำหนดค่าได้โดยกดที่รูปเฟืองในแต่ละ widget <br> ![image](https://github.com/keeratiburt/Tutorial-10-Embedded-Systems-and-IoT/assets/125423996/72ea8aec-f022-47e2-8669-34ab2d30bd77)
8. ออกแบบระบบด้วยตนเองโดยให้ทำงานได้ 1 อย่าง เช่น ควบคุมการเปิด/ปิด LED จาก Blynk หรือส่งค่าอุณหภูมิขึ้น Blynk
9. ส่งงานโดยแสดงผลหน้า Dashboard ผ่าน Blynk Application (iOS/Android) บนโทรศัพท์มือถือ
<br> <br>
**กรณีใช้ Anto.io**
Anto.io เป็น IoT platform ของคนไทย มีคู่มือ วิธีทำและเอกสารต่างๆเป็นภาษาไทยให้สามารถทำตามได้บนเว็บไซต์ สามารถใช้บอร์ด ESP32 และ ESP8266 ได้
1. สมัครสมาชิกได้ที่ https://www.anto.io
2. เข้าลิงค์ Document และทำตามขั้นตอน
3. ออกแบบระบบด้วยตนเองโดยให้ทำงานได้ 1 อย่าง เช่น ควบคุมการเปิด/ปิด LED จาก Anto หรือส่งค่าอุณหภูมิขึ้น Anto
4. ส่งงานโดยแสดงผลหน้า Dashboard ผ่าน web browser บนโทรศัพท์มือถือ
