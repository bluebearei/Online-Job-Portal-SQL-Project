# Online Job Portal - SQL Project

This project is a PL/SQL-based database management system for an **Online Job Portal**, developed as part of the Spring 2024 Project for school. It demonstrates core database design principles, procedural SQL (PL/SQL), and effective management of data related to job postings, job applications, and user accounts.

---

## 📚 **Project Overview**
The goal of this project is to:
1. Design a database schema to support the functionalities of an Online Job Portal.
2. Insert sample data for testing.
3. Implement individual and group features as PL/SQL procedures to manage the portal's functionality.

---

## 🔧 **Features Implemented**
### **Individual Features**
1. **Add Account**  
   Adds a new user account or updates existing account details if a duplicate phone number exists.
   
2. **Add Company**  
   Adds a new company or detects duplicates and prevents multiple entries.

3. **Search Job Posts**  
   Searches for active job posts by keyword, job type, and location.

4. **Apply for Job**  
   Allows job seekers to submit applications for specific job posts.

5. **List Applications for a Job Post**  
   Displays all applicants for a job post, including their account details, skills, and work experience.

### **Group Features**
1. **Add Job Post**  
   Enables recruiters to post job openings, including required skills and qualifications.

2. **Generate Job Alerts**  
   Sends notifications to qualified job seekers for matching job postings.

3. **Assign Initial Score to Applicants**  
   Ranks job applicants based on their qualifications, skills, and work experience.

4. **Update Application Status**  
   Tracks and updates the status of job applications, such as submission, acceptance, or rejection.

5. **Print Statistics**  
   Generates system-wide statistics, such as the number of active job posts, recruiters, and job seekers.

---

## 🗃️ **Database Schema**
The database includes the following key entities:

1. **Accounts**: Stores user account details (job seekers and recruiters).
2. **Companies**: Stores information about companies posting jobs.
3. **Job Posts**: Details about job openings, including requirements and pay ranges.
4. **Applications**: Tracks job applications and their statuses.
5. **Skills**: Manages the skills of job seekers and job requirements.
6. **Messages**: Stores messages sent to users, such as job alerts.

---

## 📊 **ER Diagram**
![ER Diagram](diagrams/er_diagram.png)  
*(Upload your ER diagram to the `diagrams/` folder and link it here.)*

---

## 🚀 **How to Run**
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/Online-Job-Portal-SQL-Project.git
   cd Online-Job-Portal-SQL-Project
