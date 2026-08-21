# BB2 – Society Visitor Management System

MERN stack starter skeleton for the Society Visitor Management System.

## Purpose

This repository is a **starting map for the project**, not a completed application. It intentionally does not implement the client requirements.

Use the Project Requirement Document as the source of truth. The structure here is only meant to give you an initial idea of the application's major areas before you begin designing and implementing them.

## Stack

- MongoDB
- Express.js
- React.js
- Node.js

## Project structure

```text
BB2/
├── client/
│   └── src/
│       ├── components/
│       ├── pages/
│       │   ├── Login/
│       │   ├── Register/
│       │   ├── AdminDashboard/
│       │   ├── SecurityDashboard/
│       │   ├── ResidentDashboard/
│       │   ├── ResidentManagement/
│       │   ├── VisitorEntry/
│       │   ├── VisitorList/
│       │   ├── ExitManagement/
│       │   ├── VisitorHistory/
│       │   └── Profile/
│       └── styles/
│
├── server/
│   └── src/
│       ├── config/
│       ├── controllers/
│       ├── models/
│       ├── routes/
│       └── middleware/
│
├── .gitignore
└── README.md
```

The page folders provide a high-level view of the main application areas described in the requirements. Backend folders are intentionally left more open so you can decide how to organize models, controllers, routes, middleware, and other server-side logic.

## Important

The folder structure is **not a fixed architecture**. You are expected to add, rename, move, or remove files and folders as your implementation develops.

No business logic, database schema, API implementation, authentication, role-based access, CRUD implementation, or finished UI is provided intentionally.

Some directories contain a `.gitkeep` file only so Git can track an otherwise empty directory. **Remove the `.gitkeep` file when you start adding your actual files to that directory.**

## Getting started

1. Clone the repository.
2. Install dependencies from the frontend and backend package files.
3. Create your environment variables using the provided examples.
4. Read the Project Requirement Document carefully.
5. Plan your data models, API structure, routes, authentication, role permissions, and page flow.
6. Start implementing the application one part at a time.

The goal of this repository is to help you avoid starting from a completely blank folder while leaving the actual engineering decisions and implementation to you.
