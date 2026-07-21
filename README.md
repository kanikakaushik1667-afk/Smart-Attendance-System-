# 📚 Smart Attendance System

A web-based Smart Attendance System that simplifies attendance management for educational institutions. The system provides separate dashboards for teachers and students, allowing attendance tracking, class scheduling, announcements, notes, assignments, and marks management.

---

## 🚀 Features

### 👨‍🏫 Teacher Module
- Teacher Login
- Schedule Classes
- Enable/Disable Attendance
- Mark Student Attendance
- Upload Assignments
- Upload Study Notes
- Post Announcements
- Manage Student Marks
- View Attendance Records

### 👨‍🎓 Student Module
- Student Login
- View Attendance
- View Class Schedule
- Download Notes
- View Assignments
- Submit Assignments
- View Announcements
- Check Internal & External Marks

---

## 🛠️ Tech Stack

### Frontend
- HTML5
- CSS3
- JavaScript

### Backend
- Python
- Flask

### Database
- MongoDB

---

## 📂 Project Structure

```
Smart-Attendance-System/
│
├── static/
│   ├── style.css
│   ├── login.js
│   ├── teacher.js
│   ├── student.js
│   └── website.png
│
├── templates/
│   ├── index.html
│   ├── teacher.html
│   ├── student.html
│   └── change_password.html
│
├── app.py
├── requirements.txt
├── README.md
└── .gitignore
```

---

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/kanikakaushik1667-afk/Smart-Attendance-System-.git
```

### Navigate to Project

```bash
cd Smart-Attendance-System-
```

### Create Virtual Environment (Optional)

```bash
python -m venv venv
```

### Activate Virtual Environment

Windows

```bash
venv\Scripts\activate
```

Mac/Linux

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🗄️ MongoDB Setup

1. Install MongoDB Community Server.
2. Start MongoDB.
3. Make sure MongoDB is running on:

```
mongodb://localhost:27017/
```

The application automatically creates the required collections.

---

## ▶️ Run the Project

```bash
python app.py
```

Open your browser and visit

```
http://127.0.0.1:5003
```

---

## 📷 Screenshots

Add screenshots of:

- Login Page
- Teacher Dashboard
- Student Dashboard
- Attendance Page
- Marks Section

---

## 📌 Future Improvements

- Face Recognition Attendance
- QR Code Attendance
- Email Notifications
- Role-Based Authentication
- Attendance Analytics Dashboard
- Export Attendance Reports (PDF/Excel)
- Mobile Responsive UI

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Added new feature"
```

4. Push to GitHub

```bash
git push origin feature-name
```

5. Open a Pull Request

---

## 👩‍💻 Author

**Kanika Kaushik**

- GitHub: https://github.com/kanikakaushik1667-afk

---

## ⭐ Support

If you found this project helpful, please consider giving it a ⭐ on GitHub.
