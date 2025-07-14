# JobNest – MERN Stack Job Portal

**JobNest** is a full-stack job portal application built using the MERN stack. It allows users to register/login, apply for jobs, and manage their profiles. Admins or recruiters can post jobs and manage listings.

> Secured with JWT Authentication  
>  Profile uploads and resume management via Cloudinary  
> ⚙️ Built with: MongoDB, Express.js, React.js, Node.js

---

## Features

### Authentication & Authorization
- JWT-based login & registration
- Role-based access control (Candidate / Recruiter / Admin)
- Secure route protection with tokens and cookies

### File Uploads
- Profile picture and resume upload with [Cloudinary](https://cloudinary.com/)
- Multer + Data URI integration for smooth file handling

### User Profiles
- Add skills, bio, resume, and profile photo
- Update profile information with real-time validation

### Job Management
- Recruiters can create, update, and delete job posts
- Candidates can view, search, and apply for jobs
- Application tracking per user

### Frontend (React)
- Responsive UI built with React 
- Login/Register pages with input validation
- Dashboard views based on user role
