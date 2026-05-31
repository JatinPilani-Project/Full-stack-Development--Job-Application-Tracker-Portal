# Respiratory Monitoring & Management Portal

## Project Overview
A full-stack healthcare platform for respiratory device monitoring, patient tracking, maintenance management, analytics, and clinical workflow support.

## Objective
Build an industry-oriented healthcare application that enables biomedical engineers, hospital staff, and administrators to manage respiratory equipment, monitor device status, schedule preventive maintenance, and generate reports.

## Key Features
- User Authentication (JWT)
- Device Inventory Management
- HFNO/Ventilator Tracking
- Preventive Maintenance Scheduler
- Service Call Management
- Dashboard Analytics
- Report Generation
- Role-Based Access Control
- Device History Logs
- Notification & Reminder System

## Tech Stack
### Frontend
- React.js
- Tailwind CSS
- React Router
- Axios

### Backend
- Node.js
- Express.js
- JWT Authentication
- REST APIs

### Database
- MongoDB
- Mongoose

## Folder Structure

```text
Respiratory-Management-Portal/
│
├── client/
│   ├── src/
│   ├── components/
│   ├── pages/
│   └── services/
│
├── server/
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── middleware/
│   └── config/
│
├── docs/
├── README.md
├── .gitignore
└── package.json
```

## Core Modules
1. Authentication
2. Device Management
3. Maintenance Tracking
4. Complaint Management
5. Reports & Analytics
6. Notification System

## Database Collections
### Users
- Name
- Email
- Password
- Role

### Devices
- Device Name
- Model
- Serial Number
- Department
- Status

### Maintenance
- Device ID
- Engineer Name
- Date
- Status
- Remarks

## API Endpoints

### Auth
- POST /api/auth/register
- POST /api/auth/login

### Devices
- GET /api/devices
- POST /api/devices
- PUT /api/devices/:id
- DELETE /api/devices/:id

### Maintenance
- GET /api/maintenance
- POST /api/maintenance

## GitHub Repository Details

### Repository Name
Respiratory-Management-Portal

### Description
Full Stack MERN-based Respiratory Equipment Management Portal for Hospitals and Biomedical Engineering Departments.

### Topics
mern, reactjs, nodejs, expressjs, mongodb, healthcare, biomedical-engineering, respiratory, hospital-management

## Learning Outcomes
- Full Stack Development
- REST API Design
- Authentication & Authorization
- MongoDB Schema Design
- Healthcare Software Workflow
- Git & GitHub Collaboration

## Future Enhancements
- IoT Device Integration
- Real-Time Monitoring
- AI-Based Predictive Maintenance
- Mobile Application
- Advanced Analytics Dashboard

## Author
Jatin Pilani
Biomedical Engineer | AI & Data Science
