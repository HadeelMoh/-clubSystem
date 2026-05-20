# 🏆 Club Management System | نظام إدارة الأندية واللجان

An integrated **Java Desktop Application** designed to organize and manage different aspects of a club, including committees, members, and events. The system features a fully hand-coded **Swing GUI** (without drag-and-drop tools) and implements robust data management.

<div align="right" dir="rtl">

مشروع متكامل بلغة **جافا** لإدارة الأندية واللجان، يتميز بواجهات رسومية (GUI) تم بناؤها وتصميمها برمجياً بالكامل داخل الكلاس الأساسي لضمان أقصى درجات التحكم والمرونة.

</div>

---

## واجهات البرنامج (GUI Showcase)

### 1️⃣ الواجهة الرئيسية وإضافة لجان (Main Form & Add Committees)
<img width="664" height="445" alt="addCommitte" src="https://github.com/user-attachments/assets/9490a59d-b98f-4770-8994-305a883a15a7" />
<img width="666" height="445" alt="addcommSuccef" src="https://github.com/user-attachments/assets/a50b3c29-b18a-48b4-a1b0-8ce23f48d770" />


### 2️⃣ واجهة تسجيل الأعضاء (Member Registration)
<img width="667" height="444" alt="addmember" src="https://github.com/user-attachments/assets/72e7d732-ad18-4f01-ae41-ff4dd86f8d7e" />
<img width="667" height="448" alt="addmembsuccf" src="https://github.com/user-attachments/assets/8d488fd1-5891-43f4-ba85-c9cc7bd7d5f0" />


### 3️⃣ واجهة التعديل على معلومات الأعضاء (Edit Member Information)
<img width="662" height="443" alt="EditMember" src="https://github.com/user-attachments/assets/3c7b1fc7-026e-4651-9b96-1e059a62ef7c" />

### 4️⃣ واجهة إضافة فعالية (Add Event)
<img width="661" height="445" alt="addevent" src="https://github.com/user-attachments/assets/e213f269-7a2c-41f6-8c40-1fa5464e6a2f" />
<img width="661" height="442" alt="eventsucc" src="https://github.com/user-attachments/assets/18d144ad-3c73-4cd1-ac1c-73f123a3e6b8" />

### 5️⃣ واجهة عرض تقرير للأعضاء والفعاليات (Display Reports)
<img width="661" height="445" alt="viewReport" src="https://github.com/user-attachments/assets/cd7386f2-bed2-4143-a156-8f1b5888c778" />
<img width="665" height="442" alt="viewReportsucc" src="https://github.com/user-attachments/assets/8276f02f-b7c6-444a-babc-e7d894c20a64" />
<img width="664" height="443" alt="reportevent" src="https://github.com/user-attachments/assets/f76ba067-0b33-4152-83b4-46b3a5d98b60" />


### 6️⃣ واجهة لإغلاق وحفظ البيانات (Close & Save Data)
<img width="661" height="441" alt="closeSystem" src="https://github.com/user-attachments/assets/6aace699-9a41-46e0-86ed-f805b4d7d619" />

---

## 🚀 المميزات الرئيسية | Key Features
- **Committee Management:** Allows users to add and manage different club committees.
- **Member Registration:** Supports registering multiple member roles (such as Board Members and Volunteers).
- **Information Editing:** Full capability to edit and update member details dynamically.
- **Event Organization:** Track and add club events and activities efficiently.
- **Detailed Reports:** Generates structured reports displaying comprehensive statistics for members and events.
- **Data Persistence:** Uses File I/O (`.dat` files via Object Serialization) to automatically save all data upon closing and load it back on startup.

---

## 🛠️ التقنيات المستخدمة | Technologies Used
- **Language:** Java ☕
- **UI Library:** Java Swing & AWT (Hard-coded GUI)
- **Data Persistence:** File I/O (`clubData.dat`)
- **OOP Concepts:** Polymorphism, Inheritance (Person -> Member -> BoardMember / Volunteer)
