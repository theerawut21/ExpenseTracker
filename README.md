# ExpenseTracker
**ชื่อ - นามสกุล (Full Name):** Theerawut Khamsuetrong

**รหัสนักศึกษา (Student ID):** 6631503024

**ชื่อแอป (App Name):** ExpenseTracker

**Framework ที่ใช้ (Framework Used):** React Native / อื่น ๆ

**ลิงก์ GitHub Repository:** https://github.com/theerawut21/ExpenseTracker

**ลิงก์ไฟล์ติดตั้ง (APK/IPA):** https://expo.dev/accounts/theerawut/projects/ExpenseTracker/builds/261b3b5c-9454-428e-96dd-829558bb3f3b

---

# 1. การออกแบบแอป | App Concept and Design (2 คะแนน / 2 pts)
**1.1 ผู้ใช้งานเป้าหมาย | User Personas**

Persona 1:  
- ชื่อ: ฟิวส์ 
- อายุ: 20 ปี  
- อาชีพ: นักศึกษาปี 1  
- ความต้องการ: ต้องการที่จะวางแผนการใช้เงินสำหรับแต่ละเดือน

Persona 2:  
- ชื่อ: พอส  
- อายุ: 26 ปี  
- อาชีพ: พนักงานบริษัท  
- ความต้องการ: ต้องการวางแผนการออมเงินเพื่อใช้สำหรับสร้างครอบครัวในอนาคต

**1.2 เป้าหมายของแอป | App Goals**
ตัวอย่าง (Example):

- ช่วยให้ทุกเพศทุกวัยรู้จักใช้จ่ายอย่างมีความเหมาะสม
- มีหน้าสถิติแจ้งการใช้จ่ายในเดือนนั้นๆและยอดเงินที่คงเหลือ
- มีเป้าหมายในการเก็บออมเงินที่ชัดเจน พร้อมติดตามความคืบหน้า

**1.3 โครงร่างหน้าจอ / Mockup**
ใส่รูปภาพ หรือคำอธิบายแต่ละหน้าหลัก 3 หน้า | Attach image or describe 3 main pages
  
  *1.3.1* 
  ![1 3 1](https://github.com/user-attachments/assets/9cb4c2c2-9ab5-4c44-8073-3577458b3c7d)


  *1.3.2*
  ![1 3 2](https://github.com/user-attachments/assets/e4f46258-f878-4a8c-a654-fc023ae1a206)


  *1.3.3*
  ![1 3 3](https://github.com/user-attachments/assets/a373dae4-cf7b-4bf0-ab01-f00fd7a0ffe8)
  

**1.4 การไหลของผู้ใช้งาน | User Flow**
ตัวอย่าง (Example):

เปิดแอป > เข้าหน้าหลัก > กด "+ Add Transaction" เพื่อเพิ่มรายการรายรับ-รายจ่าย > Save Transaction > เลือก "Statistics" เพื่อตรวจสอบการใช้จ่ายและเงินคงเหลือ > เลือก "Saving Goals" > กด "+" เพื่อตั้งเป้าหมายในการเก็บเงิน 

---

# 2. การพัฒนาแอป | App Implementation (4 คะแนน / 4 pts)
**2.1 รายละเอียดการพัฒนา | Development Details**
เครื่องมือที่ใช้ / Tools used:

- Flutter 3.19
- Dart 3.2
- Package: Provider, SharedPreferences

**2.2 ฟังก์ชันที่พัฒนา | Features Implemented**
Checklist:

- [x] เพิ่ม / แก้ไข / ลบ ตารางเรียน
- [x] ตั้งเตือนกิจกรรม
- [x] บันทึกงานที่ต้องทำ
- [ ] ซิงก์กับ Google Calendar

**2.3 ภาพหน้าจอแอป | App Screenshots**
แนบภาพหรือ URL (Attach images or image links):

- ![2 3 1](https://github.com/user-attachments/assets/ab38453e-0a60-410c-a4cb-199b807a05bb)

- ![2 3 2](https://github.com/user-attachments/assets/99534c0b-ae90-495b-be91-4055cfef7514)

- ![2 3 3](https://github.com/user-attachments/assets/219695c0-8380-45b7-9a1f-f4727c194623)


---

# 3. การ Build และติดตั้งแอป | Deployment (2 คะแนน / 2 pts)
**3.1 ประเภท Build | Build Type**

[x] Debug

[ ] Release

**3.2 แพลตฟอร์มที่ทดสอบ | Platform Tested**

[x] Android

[ ] iOS

**3.3 ไฟล์ README และวิธีติดตั้ง | README & Install Guide**
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
