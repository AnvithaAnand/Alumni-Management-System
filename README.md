# 🎓 Alumni Management System — PES University  
### Full-Stack Alumni Engagement & Communication Portal  
_Built by **Anvitha Anand**_

---

## 📌 Overview  
The Alumni Management System is a full-stack platform designed to streamline **alumni engagement**, **event communication**, and **record management**.  
It automates notifications, maintains alumni/user records, and provides admins with analytics to track engagement and activity.

---

## ⭐ Key Features  
- **Role-based authentication** (alumni + admin)  
- **Announcements & news** broadcasting panel  
- **Event creation** with automated reminders  
- **1,000+ notifications/month** handled automatically  
- **Admin dashboard** for analytics  
- **Fast SQL-backed search & filtering**  
- **Responsive UI** (React)  

---

## 🏗️ System Architecture  

```mermaid
flowchart LR
    A[React Frontend] --> B[Node.js / Express Backend]
    B --> C[SQL Database]
    B --> D[Email & Notification Service]
    B --> E[Admin Dashboard Analytics]
