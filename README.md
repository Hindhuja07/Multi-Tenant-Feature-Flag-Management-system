# Multi-Tenant Feature Flag Management System

A simple SaaS-style feature flag management platform built using Node.js, Express.js, SQLite, HTML, CSS, and JavaScript.

This project was developed as part of a technical assessment to demonstrate backend development, REST API design, role-based workflows, authentication handling, and multi-tenant feature management.

---

## Project Overview

The application allows organizations to manage feature availability dynamically without changing or redeploying application code.

The system contains three separate user roles:

### Super Admin

* Login using static credentials
* Create organizations
* View organization details

### Organization Admin

* Signup using organization code
* Login securely
* Create feature flags
* Enable or disable features
* Delete feature flags

### End User

* Check whether a feature is enabled or disabled for their organization

---

## Tech Stack

### Backend

* Node.js
* Express.js

### Frontend

* HTML
* CSS
* JavaScript

### Database

* SQLite

---

## Features Implemented

* Multi-tenant organization support
* Organization-specific feature flags
* Custom authentication
* REST API integration
* Persistent database storage
* Feature enable/disable controls
* Separate frontend interfaces for all user roles
* Clean and responsive UI

---

## Project Structure

backend/
│
├── db/
├── routes/
├── middleware/
├── server.js

frontend/
│
├── super-admin/
├── admin/
├── user/
├── index.html

---

## Installation and Setup

### 1. Clone the Repository

git clone <your-github-repo-link>

### 2. Navigate to Project Folder

cd byepo-feature-flag-system

### 3. Install Dependencies

npm install

### 4. Start the Server

npm start

Server will run at:

http://localhost:5000

---

## Application Routes

### Home Page

http://localhost:5000

### Super Admin

http://localhost:5000/super-admin

### Organization Admin

http://localhost:5000/admin

### End User

http://localhost:5000/user

---

## Default Super Admin Credentials

Username: superadmin
Password: admin123

---

## Example Workflow

1. Super Admin creates an organization
2. Organization Admin signs up using organization code
3. Admin logs in and creates feature flags
4. End User checks feature availability

---

## Future Improvements

* JWT authentication
* Role-based access middleware
* Feature scheduling
* Audit logs
* Search and filtering
* Improved UI responsiveness
* Docker deployment

---

## Author

Hindhuja J
