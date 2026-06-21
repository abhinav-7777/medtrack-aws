# 🏥 MedTrack AWS

MedTrack AWS is a cloud-based healthcare management application designed to help users manage medications, track prescriptions, receive reminders, and maintain medical records securely using AWS cloud services.

---

## 🚀 Features

- User Authentication & Authorization
- Medicine Tracking
- Prescription Management
- Medication Reminders
- Secure Cloud Storage
- Patient Dashboard
- Responsive UI
- AWS Cloud Deployment

---

## 🛠️ Tech Stack

### Frontend
- React.js
- HTML5
- CSS3
- JavaScript

### Backend
- Node.js
- Express.js

### Database
- MongoDB / DynamoDB

### Cloud Services
- AWS EC2
- AWS S3
- AWS IAM
- AWS CloudWatch

---

## 🏗️ Architecture

User → Frontend (React) → Backend API (Node.js/Express) → Database

AWS Services:
- EC2 for application hosting
- S3 for file storage
- IAM for access management
- CloudWatch for monitoring

---

## 📂 Project Structure

```bash
medtrack-aws/
│
├── frontend/
│   ├── src/
│   └── public/
│
├── backend/
│   ├── routes/
│   ├── models/
│   ├── controllers/
│   └── server.js
│
├── aws/
│   └── deployment-config
│
├── screenshots/
│
└── README.md
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/abhinav-7777/medtrack-aws.git
cd medtrack-aws
```

### Backend Setup

```bash
cd backend
npm install
npm start
```

### Frontend Setup

```bash
cd frontend
npm install
npm start
```

---

## 🔑 Environment Variables

Create a `.env` file:

```env
PORT=5000
MONGO_URI=your_database_url
AWS_ACCESS_KEY=your_access_key
AWS_SECRET_KEY=your_secret_key
AWS_REGION=your_region
```

---

## ☁️ AWS Deployment

### Services Used

| Service | Purpose |
|----------|----------|
| EC2 | Application Hosting |
| S3 | File Storage |
| IAM | Security Management |
| CloudWatch | Monitoring |

---

## 📸 Screenshots

### Dashboard
(Add Screenshot)

### Medication Tracker
(Add Screenshot)

### Reminder System
(Add Screenshot)

---

## 🔒 Security Features

- JWT Authentication
- Password Encryption
- AWS IAM Policies
- Secure API Access

---

## 📈 Future Enhancements

- SMS/Email Reminders
- Doctor Portal
- Mobile Application
- AI-based Medication Recommendations
- Health Analytics Dashboard

---

## 👨‍💻 Author

**Abhinav**

GitHub: https://github.com/abhinav-7777

---

## 📄 License

This project is licensed under the MIT License.
