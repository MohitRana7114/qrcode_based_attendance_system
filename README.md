# 🎓 QR Code Based Attendance System - Student App

This is the **Student App** for the QR Code Based Attendance System.  
It allows students to **sign in, generate their unique QR code, and mark attendance** when scanned by the Admin app.  

---

## 🚀 Features
- 🔐 **Firebase Authentication** (Google Sign-In & Email/Password Login)  
- 🧑‍🎓 **Student Profile Setup** (Name, Roll Number, Email stored in Firestore)  
- 📱 **QR Code Generation** (Unique QR per student)  
- ✅ **Attendance Tracking** (QR scanned by Admin app → updates backend)  
- 🔄 **Real-time Sync** with Flask backend + Firebase  
- ⚡ **Duplicate Scan Prevention** (Attendance can’t be marked twice)  

---

## 📱 Screenshots (Optional)
_Add screenshots of your app UI here (login screen, QR screen, attendance success screen)._

---

## 🛠️ Tech Stack
- **Frontend:** Flutter (Dart)  
- **Backend:** Python Flask (Attendance API)  
- **Database:** Firebase Firestore + SQLite (for local backup)  
- **Authentication:** Firebase Auth (Google & Email/Password)  
- **Other:** QR Code Generator, Camera Scanner  

---

## 📂 Project Structure
qrcode_based_attendance_system/
│── student_app/ # Flutter Student App
│ ├── lib/
│ ├── android/
│ ├── ios/
│ └── ...
│── admin_app/ (coming soon)
│── backend_flask/ (Flask server + SQLite DB)

project run 
---

## 🔧 Installation & Setup

### 1️⃣ Clone Repository
```bash
git clone https://github.com/MohitRana7114/qrcode_based_attendance_system.git
cd qrcode_based_attendance_system/student_app

flutter pub get

flutter run
👨‍💻 Author

Developed by Mohit Rana
🚀 Flutter Developer | Firebase | AI/IoT Enthusiast









