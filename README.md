# 🎓 Attendance Management System (AMS)

##  Features

###  Student Application
-  Mark attendance via:
  - Face recognition (OpenCV + face_recognition)
  - QR code scanning
  - Fingerprint simulation
  - Offline mode (syncs when online)
-  View personal attendance stats (ready for chart integration)
-  Secure login and access to personal data only

 Teacher Application
- 🧾 Manage students (add, list)
- 📅 View student attendance records
- 📈 Get visual-ready attendance insights
- 🔐 Access only to their own class data
- 💾 Backup attendance data (`backup.json`)

---

##  Tech Stack

- **Backend**: Python, Flask
- **Database**: SQLite
- **Authentication**: JWT (Flask-JWT-Extended), Bcrypt
- **Face Recognition**: face_recognition, OpenCV
- **QR Scanning**: pyzbar
- **Frontend**: Ready for Flutter / React (via REST API)

