Application Tracking System
This project is a fully functional Applicant Tracking System (ATS) that manages job postings, receives applications, and creates a hiring workflow for these applications. It is built using the MERN stack: MongoDB, Express, React, and Node.js.

Features
User account creation and login with role-based access
Job posting creation and management
Application submission and tracking
Multiple form checks for candidates
Coordinator and recruiter dashboards for managing job postings and applications
Screenshots
App Screenshot App Screenshot App Screenshot App Screenshot

Installation
Clone the repository:

git clone https://github.com/nikhilmalakar/application-tracking-system.git
cd application-tracking-system
Install server dependencies:

cd server
npm install
Install client dependencies:

cd client
npm install
Create a .env file in the server directory and add the following:

MONGODB_URL=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
Start the development server:

cd server
npm run dev
Start the client:

cd client
npm start
Usage/Examples
![01_Homepage](https://github.com/user-attachments/assets/78b361e5-7b94-46fa-a1e6-319780e509cb)
![02_Homepage](https://github.com/user-attachments/assets/92aac0b9-9542-465e-b4a5-4138864b58d7)
![03_Employer_Dashboard](https://github.com/user-attachments/assets/ebd68706-1781-43af-82fc-15de75cbcad7)
![04_Create_Job_Post_R1_form](https://github.com/user-attachments/assets/45a4b273-123b-4c3d-8986-0be3301c07d6)
![05_Shortlisted_Candidates](https://github.com/user-attachments/assets/3792932a-e48b-40ce-b846-84e3f95889a9)
![06_Coordinator_dashboard](https://github.com/user-attachments/assets/caff5429-87f0-4c2f-b25f-d58c32153342)

![07_Coordinator_assign_R2_form](https://github.com/user-attachments/assets/444ce11e-7e9e-474c-9894-8f6a1369e2d8)

![08_Recruiter_dashboard](https://github.com/user-attachments/assets/ebda9611-216a-4d05-8c1b-51d5c944879d)
![09_Recruiter_R2__form](https://github.com/user-attachments/assets/18634a87-2a9a-4669-b2f0-cee16c52367e)
![10_Candidate_dashboard](https://github.com/user-attachments/assets/5950f156-1a23-439e-a0d4-e5dc26907ec7)
![11_All_job_listings](https://github.com/user-attachments/assets/904e10f9-2dd4-478c-acf8-e6abbb7b8d24)
![12_Job_Apply](https://github.com/user-attachments/assets/3018eca6-7e84-47f6-b5ef-ab74b659968a)
![13_Signup_Form](https://github.com/user-attachments/assets/937957b6-8886-4cba-9005-a0408db1332f)

![14_Login_Form](https://github.com/user-attachments/assets/73311772-642c-46ea-9196-338338e41f9c)

Navigate to http://localhost:3000 in your web browser.
Create a user account for each role (Candidate, Coordinator, Recruiter, Employer).
Use the application according to the role functionalities outlined in the SRS summary.
SRS Summary
Problem Statement
The task is to design an Applicant Tracking System (ATS) that manages job postings, receives applications, and creates a hiring workflow.

Users
Candidate: A job seeker who applies for jobs.
Coordinator: Manages job postings and recruitment workflows.
Recruiters: Screens candidates' resumes.
Employers: Creates job postings.
Job Posting Flow
Employer creates a job post, including a job description and an R1 check form.
Coordinator approves the job post, assigns recruiters, and adds an R2 check form.
Coordinator posts the job, making it live for candidates to apply.
Application Flow
Candidate creates an account, views job postings, and applies by uploading a resume and completing the R1 check form.
Recruiter reviews applications, completes the R2 check form, and shortlists candidates for the final stage.
Shortlisted applications appear in both employers' and coordinators' dashboards.
Additional Requirements
User account management with role-based access.
Basic security practices.
Tech Stack
Client: React, Redux, TailwindCSS

Server: Node, Express, Mongoose

Database: MongoDB
