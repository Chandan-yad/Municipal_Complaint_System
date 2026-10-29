# Municipal Complaint & Grievance Redressal System

An automated, transparent web portal enabling citizens to lodge civic complaints (garbage, roads, water supply, streetlights) and empowering municipal authorities to track, assign, and resolve grievances with real-time status updates.

## 📌 Project Overview
* **Course:** Software Engineering Lab CA
* **Repository:** `Municipal_Compliant_System`
* **Architecture:** MVC / Microservices-ready Web Architecture

## 👥 Team & Roles 
1. **Kavin Gupta:** Business Analyst / Requirements Engineer...

## 🚀 Core Features
* Citizen registration and secure OTP/JWT authentication
* Geotagged and category-based complaint filing with photo uploads
* Departmental routing (Sanitation, Road Work, Electricity, Water Board)
* Real-time ticket lifecycle tracking (`Submitted` -> `Assigned` -> `In-Progress` -> `Resolved`)
* Admin escalation matrix for overdue complaints
* Citizen feedback & rating system upon ticket closure

## 🛠️ Tech Stack (Suggested)
* **Client:** React.js / HTML5 / Tailwind CSS
* **Server:** Node.js (Express) / Python (Django/FastAPI)
* **Database:** PostgreSQL / MySQL
* **Tools:** Git, GitHub, Postman, Draw.io (UML)

## 📂 Project Deliverables
* **Lab-1:** GitHub Setup & Team Role Mapping
* **Lab-2:** Problem Statement & Feasibility Analysis
* **Lab-3:** Requirement Engineering & Elicitation
* **Lab-4:** IEEE 830 Standard Software Requirements Specification (SRS)
* **Lab-5:** UML Use Case Modeling & Diagrams
* **Lab-6:** UML Class Diagram DesignAssignment
* **Lab-7:** UML Sequence & Activity Diagram Assignment
* **Lab-8:** Software Design Principle - ReportAssignment
* **Lab-9:** Software Architecture Design & Design PatternsAssignment
  
# Municipal Complaint Management System

## 1. Introduction

The **Municipal Complaint Management System** is a software application designed to help citizens register and track complaints related to municipal services.

The system provides a centralized platform where citizens can report problems such as garbage collection, street lights, roads, water supply, drainage, sanitation, and other civic issues.

Municipal authorities can view, manage, assign, and resolve complaints efficiently through an administrative dashboard.

The main objective of this system is to improve communication between citizens and municipal authorities and make the complaint resolution process faster, transparent, and organized.

---

## 2. Problem Statement

In traditional municipal complaint systems, citizens may have to visit municipal offices or use different channels to report their problems. This can lead to:

- Delay in registering complaints
- Difficulty in tracking complaint status
- Lack of transparency
- Poor communication between citizens and authorities
- Difficulty in managing a large number of complaints
- Lack of proper complaint records

The proposed system solves these problems by providing a centralized digital platform for complaint registration, tracking, assignment, and resolution.

---

## 3. Objectives

The main objectives of the Municipal Complaint Management System are:

- To provide an easy platform for citizens to register complaints.
- To allow citizens to track the status of their complaints.
- To help municipal authorities manage complaints efficiently.
- To assign complaints to the appropriate department or employee.
- To maintain a centralized database of complaints.
- To reduce manual paperwork.
- To improve transparency in complaint resolution.
- To provide better communication between citizens and municipal authorities.
- To generate useful reports for administrative analysis.

---

## 4. Scope of the Project

The system can be used by:

### Citizens
- Register/Login
- Submit complaints
- Upload complaint images/documents
- Select complaint category
- Track complaint status
- View complaint history
- Provide feedback after resolution

### Municipal Authorities
- Login to admin dashboard
- View all complaints
- Filter complaints by category/status
- Assign complaints to departments/employees
- Update complaint status
- Monitor pending and resolved complaints
- Generate reports and statistics

### Departments/Employees
- View assigned complaints
- Update complaint progress
- Mark complaints as resolved
- Add resolution remarks

---

## 5. Key Features

### Citizen Module

- User Registration and Login
- Complaint Registration
- Complaint Category Selection
- Complaint Description
- Location Details
- Image Upload
- Complaint Tracking
- Complaint History
- Feedback and Rating

### Admin Module

- Secure Admin Login.
- Dashboard
- View All Complaints
- Complaint Filtering and Searching
- Department Management
- Employee Management
- Complaint Assignment
- Status Management
- Reports and Statistics

### Complaint Management

Each complaint can have different statuses:

```text
Submitted
    ↓
Under Review
    ↓
Assigned
    ↓
In Progress
    ↓
Resolved
    ↓
Closed
