CampusConnect - Smart University
Management Platform 🎓
University of Layyah - Web Technologies Semester Project
Status:
 In Development | 
Course:
 Web Technologies
Live
Status
📖 Project Overview
CampusConnect is an all-in-one university web platform that helps students
access important notices, report campus issues, use Lost & Found, and get AI
summaries. Centralized platform to reduce manual handling.
🎯 Project Objectives (7)
1. Centralized platform for university students
2. Make university notices easier to access and search
3. Help students report and track campus issues
4. Provide a digital Lost & Found system
5. Improve communication between students and administration
6. Reduce manual handling of common student services
7. Use AI to simplify lengthy university notices
🏗 Main Modules
1. Smart Digital Notice Board 📢
Student: View all, Search & Filter (Dept/Sem), Details, Deadlines, Reminders,
Notifications, Pinned, AI Summary
Admin: Create/Edit/Delete/Pin, Set deadlines, Target Dept/Sem, Manage dashboard
2. Complaint & Issue Management 📝
Categories: Classrooms, Computer Labs, Electricity, Wi-Fi, Furniture
Student: Submit + description + image evidence + category + Track status +
History
Admin: View all, Filter, Assign to staff, Update status, Monitor
Status Flow:
Submitted → Assigned → In Progress → Resolved
3. Lost & Found System 🔎
Student: Report Lost/Found, name/desc/images/location/date/time, Search/Filter,
Claim
Admin: Manage listings, Manage claims, Verify, Remove inappropriate
4. AI Feature 🤖
AI API for notice summarization
👥 User Roles
Student Can: Register/Login, View/Search/Filter notices, Notifications, AI
summaries, Submit complaints, Upload images, Track status, Report lost/found,
Search listings, Submit claims
Administrator Can: Admin panel, Manage users, Create/Manage notices, Pin,
Deadlines, Target Dept/Sem, Manage complaints, Assign to staff, Update status,
Manage Lost & Found, Review/Verify claims, View stats
🗺 Website Structure
1 CampusConnect
1 ├── Home
1 ├── Notices (All, Important/Pinned, Details, Search & Filter)
1 ├── Complaints (Submit, My Complaints, Details, Status Tracking)
1 ├── Lost & Found (Lost Items, Found Items, Report Lost, Report Found, 
1 ├── Notifications
1 ├── Student Profile
1 └── Admin Panel (Dashboard, Users, Notices, Complaints, Lost & Found, 
�
� Workflows
Notice: Admin Creates 
→
 Select Dept/Sem 
→
 Publish 
→
 Student Notification 
→
Views 
→
 AI Summary 
→
 Deadline Reminder
Complaint: Student Submit + Images 
→
 Admin Reviews 
→
 Assign to Staff 
→
 In
Progress 
→
 Resolved 
→
 Student Notified
Lost & Found: Reports Lost/Found 
→
 Listing Published 
→
 Search 
→
 Finds
Matching 
→
 Claim 
→
 Admin Verify 
→
 Item Returned
📊 Admin Dashboard
Total Students, Total Notices, Active Notices, Pending Complaints, Resolved
Complaints, Lost Items, Found Items, Pending Claims + Recent activity
⭐ Key Features
Student Auth, Admin Auth, Role-Based Access, Smart Notice Board, Dept/Sem
notices, Search & Filtering, Pinned, Deadlines, Notifications, AI Summarization,
Complaint Submit + Image + Status + Assignment, Lost/Found Reporting, Image
Uploads, Search, Claim System, Admin Dashboard, User Management
💻 Technology Stack
Frontend: HTML5, CSS3, Bootstrap 5, JavaScript
Backend: Flask / Python
Database: MySQL
AI: AI API for notice summarization
Tools: VS Code, Git, GitHub, Browser Dev Tools
🗄 Database Modules (9 Tables)
users 
, 
departments 
, 
notices 
, 
notifications 
, 
complaint_images 
, 
staff 
, 
complaints 
,
lost_found_items 
, 
claims
�
� Security
User authentication, Admin authentication, Password protection, Role-based
access control, Input validation, File upload validation, Protected admin routes,
Secure database queries
🚀 Future Improvements
Email notifications, Mobile app, Real-time & WhatsApp notifications, Advanced AI,
AI chatbot, Complaint priority detection, Analytics and reports, Staff-specific
dashboards, QR verification, Multi-language
👨‍💻 Team
Project: CampusConnect | Course: Web Technologies | Purpose: Semester Project
| University: University of Layyah | Developer: Umair Akram
Building in Public - Daily Commits | Learn 
→
 Build 
→
 Market 
→
 Repeat 🔁
