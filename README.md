# BCCL-EMS (Employee Management System)

This is a **web-based Employee Management System** for **Bharat Coking Coal Limited (BCCL)**.  
It provides a dashboard for managing employees, grievances, notices, and official contacts.  
The project is built using **React (via CDN + Babel)**, **Tailwind CSS**, and **Firebase Firestore** as the backend database.

---

## 🚀 Features

- **Authentication (basic)**
  - Admin login (with fixed credentials)
  - Employee login (email + name as password)

- **Dashboard**
  - Shows stats like total employees, total grievances, resolved grievances
  - Company information and services section

- **Employee Management**
  - Add, edit, and delete employee records
  - Search employees by name, email, or department
  - Employees can view their own profile

- **Grievances**
  - Employees can submit complaints
  - Admin can update grievance status (Pending, In Progress, Resolved, Rejected)
  - Search and filter grievances

- **Notices**
  - Admin can create and delete notices
  - All users can view and search notices
  - Pagination support

- **Contacts**
  - Displays important BCCL officials with phone numbers and email IDs

- **Responsive UI**
  - Styled with Tailwind CSS
  - Sidebar navigation + header bar
  - Mobile-friendly design

---

## 🛠️ Tech Stack

- **Frontend:** React (via CDN), JSX with Babel
- **Styling:** Tailwind CSS, FontAwesome icons
- **Backend / Database:** Firebase Firestore
- **Hosting:** Can be deployed on Firebase Hosting, GitHub Pages, or any static host

---

## ⚡ Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/BCCL-EMS.git
cd BCCL-EMS

## 🌐 Live Demo
Try it here: [BCCL-EMS Live](https://souravkrshaw21-alt.github.io/BCCL-EMS/)