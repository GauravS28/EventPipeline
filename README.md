# Eventora – Workflow-Based Event Booking System

Eventora is a full-stack MERN application designed to simulate real-world event booking workflows.
It enables users to request bookings while allowing administrators to manage approvals, payments, and booking lifecycle states through a structured system.

---

## Overview

The application follows a workflow-driven architecture:

**Pending → Approved → Confirmed**

This ensures controlled processing of booking requests and mirrors real-world transaction systems.

---

## Tech Stack

* **Frontend:** React.js, Tailwind CSS
* **Backend:** Node.js, Express.js
* **Database:** MongoDB
* **Authentication:** JWT, bcrypt
* **Email Service:** Nodemailer

---

## Key Features

* Secure authentication using JWT and hashed passwords
* OTP-based verification for account and booking validation
* Role-based access control (Admin / User)
* Event creation and management system
* Booking approval workflow with status tracking
* Real-time seat availability validation
* Admin dashboard for monitoring bookings and activity
* Email notifications for booking confirmation

---

## System Workflow

1. User registers and verifies account via OTP
2. User browses available events
3. User submits a booking request
4. Request enters **pending state**
5. Admin reviews and approves/rejects
6. Booking transitions to **confirmed state**

---

## Running the Project

```bash id="j8m3dx"
npm install
npm run install:all
npm run dev
```

* Frontend: http://localhost:5173
* Backend: http://localhost:5000

---

## Notes

This project focuses on backend workflow design, API structuring, and authentication systems, reflecting real-world system design patterns.

---

## Author

Developed as a full-stack MERN project to demonstrate practical backend engineering and system design fundamentals.
