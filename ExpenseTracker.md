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
  
  *1.3.1 Home* 
  
  ![1 3 1](https://github.com/user-attachments/assets/9cb4c2c2-9ab5-4c44-8073-3577458b3c7d)  **>>>**  ![1 3 1 1](https://github.com/user-attachments/assets/1b914eb7-ddd0-4ae5-9d91-15a1c3eda1df)



  *1.3.2 Statistics*
  
  ![1 3 2](https://github.com/user-attachments/assets/26fabfc3-93a2-4880-ae0e-e91caabd02bc)



  *1.3.3 Saving Goals*
  
  ![1 3 3](https://github.com/user-attachments/assets/a373dae4-cf7b-4bf0-ab01-f00fd7a0ffe8)  **>>>**  ![1 3 3 1](https://github.com/user-attachments/assets/38a3db1f-33bc-4a17-8d7a-e1c644b1ca77)

  

**1.4 การไหลของผู้ใช้งาน | User Flow**
ตัวอย่าง (Example):

เปิดแอป > เข้าหน้าหลัก > กด "+ Add Transaction" เพื่อเพิ่มรายการรายรับ-รายจ่าย > Save Transaction > เลือก "Statistics" เพื่อตรวจสอบการใช้จ่ายและเงินคงเหลือ > เลือก "Saving Goals" > กด "+" เพื่อตั้งเป้าหมายในการเก็บเงิน > Save Goal

---

# 2. การพัฒนาแอป | App Implementation (4 คะแนน / 4 pts)
**2.1 รายละเอียดการพัฒนา | Development Details**

เครื่องมือที่ใช้ / Tools used:

- React Native
- Expo
- Package: react-navigation/native, react-navigation/bottom-tabs, react-navigation/stack, react-native-paper, react-native-vector-icons, react-native-safe-area-context

**2.2 ฟังก์ชันที่พัฒนา | Features Implemented**
Checklist:

- [x] เพิ่ม/ลบ รายรับ-รายจ่าย
- [x] แสดง รายรับ-รายจ่าย รวมในแต่ละเดือน
- [x] ตั้งเป้าหมายการเก็บออมเงิน
- [x] เพิ่ม/ลบ/แก้ไข เป้าหมายการออมเงิน

**2.3 ภาพหน้าจอแอป | App Screenshots**
แนบภาพหรือ URL (Attach images or image links):

- *Home*
  
  ![2 3 1](https://github.com/user-attachments/assets/ab38453e-0a60-410c-a4cb-199b807a05bb)

- *Statistics*
  
  ![2 3 2](https://github.com/user-attachments/assets/99534c0b-ae90-495b-be91-4055cfef7514)

- *Saving Goals*
  
  ![2 3 3](https://github.com/user-attachments/assets/d254bac5-9cd2-472c-bcc8-c1821d12f320)



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

- พบปัญหาเรื่องการ update / delete record ใน AsyncStorage
- ไม่มีระบบยืนยันตอนลบข้อมูล เพื่อป้องกันปัญหาการทำข้อมูลหายโดยไม่ได้ตั้งใจ
- หากมีเวลาจะเพิ่มฟีเจอร์ login และเชื่อม Firebase เพื่อเก็บข้อมูลและเพื่อความเป็นส่วนตัวของผู้ใช้งานมากยิ่งขึ้น

---

# 5. การใช้ AI ช่วยพัฒนา | AI Assisted Development (Bonus / ใช้ประกอบการพิจารณา)

**5.1 ใช้ AI ช่วยออกแบบ UI | UI Layout Prompt**

**Prompt ที่ใช้ :**

ออกแบบแอพสำหรับ บันทึกรายรับ-รายจ่าย

ฟังก์ชันหลัก

1.เพิ่มรายรับ / รายจ่าย 

-เลือกประเภท (รายรับ / รายจ่าย)

-ใส่จำนวนเงิน

-เลือกหมวดหมู่ (เช่น อาหาร, เดินทาง, เงินเดือน)

-เพิ่มคำอธิบาย

-เลือกวันที่

2.ดูรายการย้อนหลัง 

-แสดงรายการแบบรายวัน / รายเดือน

-แสดงตามหมวดหมู่

3.สรุปยอดเงิน 

-รายรับทั้งหมด

-รายจ่ายทั้งหมด

-ยอดคงเหลือสุทธิ

4.ตั้งเป้าหมายการออมเงิน (Saving Goals)

-สร้างเป้าหมาย เช่น "เก็บเงินซื้อโน้ตบุ๊ก"

-ใส่จำนวนที่ต้องการ และติดตามความคืบหน้า

เทคโนโลยี : React native 

**ผลลัพธ์ :**

ได้โค้ดสำหรับ React Native ที่ต้องการใส่ฟังก์ชั่นต่างๆ ให้สำหรับแอพ

**5.2 ใช้ AI ช่วยเขียนโค้ด | Code Writing Prompt**

**Prompt ที่ใช้ :**

ช่วยเพิ่มฟังก์ชันการลบรายการ รายรับ-รายจ่าย ในหน้า Home ให้หน่อยครับ

**ผลลัพธ์ :**

ได้โค้ดที่เพิ่มฟังก์ชันการลบรายการ รายรับ-รายจ่าย

**5.3 ใช้ AI ช่วย debug | Debug Prompt**

**Prompt ที่ใช้ :**

รันแอพแล้วเกิดปัญหาจอขาวแก้ยังไงครับ

**ผลลัพธ์ :**

AI แนะนำวิธีตรวจสอบปัญหาเบื้องต้น และช่วยแก้ไขปัญหา

**5.4 ใช้ AI ช่วย Deploy | Deployment Prompt**

**Prompt ที่ใช้ :**

วิธีการ Deploy แอพเป็นไฟล์ .apk

**ผลลัพธ์ :**

AI แนะนำขั้นตอนการ Build และแนะนำคำสั่ง

npm install -g eas-cli

eas login

eas build:configure

eas build -p android --profile preview
