# Flask – MySQL RDS User Management System (AWS Project)

A real-time full-stack cloud project built using *Flask API + MySQL AWS RDS + EC2 Frontend (Apache HTTPD)*.  
Users can *Add, View and Delete* data through a frontend hosted on EC2, and the backend connects securely to *AWS RDS MySQL*.

### 🔥 Tech Stack
| Component | Technology |
|----------|------------|
| Backend | Flask (Python) REST API |
| Database | AWS RDS – MySQL |
| Frontend | HTML / CSS / JavaScript |
| Hosting (Backend) | AWS EC2 Linux |
| Hosting (Frontend) | AWS EC2 + Apache HTTPD |
| Authentication | AWS Security Groups |

---

## ✨ Features
✔ Add new users  
✔ View all users  
✔ Delete users  
✔ Real-time DB operations on AWS RDS  
✔ Cross-instance communication through security groups  

---

## 📌 Project Architecture
```text
HTML + JavaScript (Frontend on EC2 Apache)
            ↓ API calls (HTTP)
Flask REST API (Backend on EC2)
            ↓ SQL
AWS RDS MySQL Database

## 📁 Project folder structure
Flask-RDS-User-Management-System/
│
├── backend/
│   ├── app.py
│   └── requirements.txt
│
└── frontend/
    └── index.html

```
## 📌 Architecture Diagram
![Architecture](architecture.png)

