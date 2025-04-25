# ExpenseTracker
ชื่อ - นามสกุล (Full Name): Theerawut Khamsuetrong

รหัสนักศึกษา (Student ID): 6631503024

ชื่อแอป (App Name): ExpenseTracker

Framework ที่ใช้ (Framework Used): React Native / อื่น ๆ

ลิงก์ GitHub Repository: [ใส่ลิงก์ที่นี่ | Insert link here]

ลิงก์ไฟล์ติดตั้ง (APK/IPA): [ใส่ลิงก์ที่นี่ | Insert link here]

---

# 1. การออกแบบแอป | App Concept and Design (2 คะแนน / 2 pts)
1.1 ผู้ใช้งานเป้าหมาย | User Personas

Persona 1:  
- ชื่อ: ฟิวส์ 
- อายุ: 20 ปี  
- อาชีพ: นักศึกษาปี 1  
- ความต้องการ: ต้องการที่จะจัดการการใช้เงินสำหรับแต่ละเดือนและแบ่งสัดส่วนเงินของแต่ละเดือน

Persona 2:  
- ชื่อ:   
- อายุ: 22 ปี  
- อาชีพ: นักศึกษาฝึกงาน  
- ความต้องการ: ต้องการวางแผนงานและกำหนดเป้าหมายประจำสัปดาห์
1.2 เป้าหมายของแอป | App Goals
ตัวอย่าง (Example):

- ช่วยนักศึกษาจัดตารางเรียนรายสัปดาห์
- เพิ่มระบบเตือนสอบและงานที่ต้องส่ง
- มีหน้าแดชบอร์ดรวมกิจกรรมประจำวัน
1.3 โครงร่างหน้าจอ / Mockup
ใส่รูปภาพ หรือคำอธิบายแต่ละหน้าหลัก 3 หน้า | Attach image or describe 3 main pages

1.4 การไหลของผู้ใช้งาน | User Flow
ตัวอย่าง (Example):

เปิดแอป > เข้าหน้าแดชบอร์ด > เลือก "เพิ่มงาน" > บันทึก > ตั้งเตือน

---

# 2. การพัฒนาแอป | App Implementation (4 คะแนน / 4 pts)
2.1 รายละเอียดการพัฒนา | Development Details
เครื่องมือที่ใช้ / Tools used:

- Flutter 3.19
- Dart 3.2
- Package: Provider, SharedPreferences
2.2 ฟังก์ชันที่พัฒนา | Features Implemented
Checklist:

- [x] เพิ่ม / แก้ไข / ลบ ตารางเรียน
- [x] ตั้งเตือนกิจกรรม
- [x] บันทึกงานที่ต้องทำ
- [ ] ซิงก์กับ Google Calendar

2.3 ภาพหน้าจอแอป | App Screenshots
แนบภาพหรือ URL (Attach images or image links):

- ![Dashboard](dashboard.png)
- ![Schedule](schedule.png)
- ![Reminder](reminder.png)

---

# 3. การ Build และติดตั้งแอป | Deployment (2 คะแนน / 2 pts)
3.1 ประเภท Build | Build Type
[x] Debug
[ ] Release

3.2 แพลตฟอร์มที่ทดสอบ | Platform Tested
[x] Android
[ ] iOS

3.3 ไฟล์ README และวิธีติดตั้ง | README & Install Guide
แนบไฟล์หรือคำอธิบายการติดตั้งแอป | Insert steps

1. ดาวน์โหลดไฟล์ .apk
2. เปิดในอุปกรณ์ Android
3. ติดตั้งผ่าน File Manager

---

# 4. การสะท้อนผลลัพธ์ | Reflection (2 คะแนน / 2 pts)
ตัวอย่างหัวข้อ | Suggested points:

- พบปัญหาเวลาใช้ setState กับ async function
- เรียนรู้การใช้ Provider ในการจัดการสถานะ
- หากมีเวลา จะเพิ่มฟีเจอร์ login และ Firebase sync

---

# 5. การใช้ AI ช่วยพัฒนา | AI Assisted Development (Bonus / ใช้ประกอบการพิจารณา)
