<div align="center">

  # 🏫 CampusConnect - Smart University Management Platform
[![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github)](https://github.com/umaiirakram/CampusConnect-Smart-University-Management-Platform)

[![Live Website](https://img.shields.io/badge/Live-Website-brightgreen?style=for-the-badge)](https://umaiirakram.github.io/CampusConnect-Smart-University-Management-Platform/)

</div>

# **CampusConnect - Smart University Management Platform**
 
  ## **Project Report**

---

## **1. Project Overview**

**CampusConnect is an all-in-one university web platform that helps students access important notices, report campus issues, use Lost & Found, and get AI summaries - centralized platform to reduce manual handling.**

---

## **2. Project Objectives**

**The main objectives of CampusConnect are:**

1. **To provide a centralized platform for university students.**
2. **To make university notices easier to access and search.**
3. **To help students report and track campus issues.**
4. **To provide a digital Lost & Found system.**
5. **To improve communication between students and administration.**
6. **To reduce manual handling of common student services.**
7. **To use AI to simplify lengthy university notices.**

---

## **3. Main Modules**

### **Module 1: Smart Digital Notice Board**

**Student:**
- **View all notices**
- **Search & Filter (Dept/Semester)**
- **View details**
- **Deadlines**
- **Reminders**
- **Receive notifications**
- **Pinned notices**
- **AI summary**

**Admin:**
- **Create/Edit/Delete notices**
- **Pin important**
- **Set deadlines**
- **Target Dept/Semester**
- **Manage all**
- **Dashboard stats**

### **Module 2: Complaint & Issue Management**

**Categories: Classrooms, Computer Labs, Electricity, Wi-Fi, Furniture, etc.**

**Student:** **Submit complaint + description + upload images + category + Track status + History + Updates**

**Admin:** **View all, Filter by category/status, Assign to staff, Update status, Monitor pending/resolved**

**Status Flow:** **Submitted -> Assigned -> In Progress -> Resolved**

### **Module 3: Lost & Found System**

**Student:** **Report Lost Item, Report Found Item, name/description/images/location/date/time, Search/Filter listings, Claim submit, Item details**

**Admin:** **Manage listings, Manage claims, Verify ownership, Remove inappropriate, Monitor users**

### **Module 4: AI Feature**

- **AI API for notice summarization (e.g., Registration 20 Sep start, 30 Sep last)**

### **Module 5: Other**

- **Notifications, Student Profile**

---

## **4. User Roles**

### **Student Can:**

**Register/Login, View/Search/Filter notices, Receive notifications, View AI summaries, Submit complaints, Upload complaint images, Track complaint status, Report lost/found items, Search Lost & Found listings, Submit item claims**

### **Administrator Can:**

**Login to admin panel, Manage students/users, Create and manage notices, Pin important notices, Set deadlines, Target Dept/Sem, Manage complaints, Assign to staff, Update status, Manage Lost & Found, Review claims, Verify claims, Monitor pending/resolved, Remove inappropriate, View Dashboard stats, View recent complaints/notices/Lost&Found**

---

## **5. Suggested Website Structure**

**CampusConnect**
**├─ Home**
**├─ Notices (All Notices, Important/Pinned, Notice Details, Search & Filter)**
**├─ Complaints (Submit Complaint, My Complaints, Complaint Details, Status Tracking)**
**├─ Lost & Found (Lost Items, Found Items, Report Lost Item, Report Found Item, Item Details)**
**├─ Notifications**
**├─ Student Profile**
**└─ Admin Panel (Dashboard, Users, Notices, Complaints, Lost & Found, Claims)**

---

## **6. Basic Workflows**

### **Notice Workflow**

**Admin Creates Notice -> Select Department/Semester -> Publish Notice -> Student Receives Notification -> Student Views Notice -> AI Summary (optional) -> Deadline Reminder**

### **Complaint Workflow**

**Student Submits Complaint + Images -> Admin Reviews -> Assign to Staff -> Staff Works -> Status Updated (In Progress) -> Resolved -> Student Notified**

### **Lost & Found Workflow**

**Student Reports Lost/Found Item -> Listing Published -> Other Students Search Listings -> Student Finds Matching Item -> Claim Submitted -> Admin Verifies Claim -> Item Returned**

---

## **7. Admin Dashboard Content**

**Total Students, Total Notices, Active Notices, Pending Complaints, Resolved Complaints, Lost Items, Found Items, Pending Claims + Recent complaints, recent notices, recent Lost & Found reports**

---

## **8. Key Features**

**Student Authentication, Admin Authentication, Role-Based Access, Smart Digital Notice Board, Department-Based Notices, Semester-Based Notices, Notice Search & Filtering, Pinned Notices, Deadline Reminders, Notifications, AI Notice Summarization, Complaint Submission, Complaint Image Upload, Complaint Status Tracking, Complaint Assignment, Lost Item Reporting, Found Item Reporting, Image Uploads, Lost & Found Search, Item Claim System, Admin Dashboard, User Management, Notice Management, Complaint Management, Lost & Found Management, Claim Management**

---

## **9. Technology Stack**

**Frontend:** **HTML5, CSS3, Bootstrap, JavaScript**
**Backend:** **Flask / Python**
**Database:** **MySQL**
**AI:** **AI API for notice summarization**
**Development Tools:** **VS Code, Git, GitHub, Browser Dev Tools**

---

## **10. Database Modules**

**Tables:**
**users, departments, notices, notifications, complaints, complaint_images, staff, lost_found_items, claims**

---

## **11. Security**

**User authentication, Admin authentication, Password protection, Role-based access control, Input validation, File upload validation, Protected admin routes, Secure database queries**

---

## **12. Future Improvements**

**Email notifications, Mobile application, Real-time notifications, WhatsApp notifications, Advanced AI notice summarization, AI chatbot for university information, Complaint priority detection, Analytics and reports, Staff-specific dashboards, QR-based item verification, Multi-language support**

---

## **13. Project Status**

**Status: In Development**
**Course: Web Technologies, Type: University Web Application, Purpose: Semester Project**

---

**© 2026 CampusConnect - University of Layyah**
