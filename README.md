# Employee Record Management System

A modern, responsive and frontend-only **Employee Record Management System** built using **HTML, CSS and Vanilla JavaScript**.

The system allows you to add, manage, search, view, edit, delete and export complete employee records without requiring a backend or database server.

## ✨ Features

* 🏠 Professional Dashboard
* 👤 Add New Employee
* 📋 Manage Employees
* 🔍 Search Employee by Name or CNIC
* 👁️ View Complete Employee Record
* ✏️ Edit Employee Information
* 🗑️ Delete Employee with Confirmation Popup
* 🖼️ Employee Photo Upload & Preview
* 🖨️ Print Employee Record
* 📊 Dashboard Employee Statistics
* 📥 Export Complete Employee Data to Excel
* 💾 Browser LocalStorage Database
* 📱 Fully Responsive Design
* 🚫 No Backend Required

## 📌 Employee Information

The system stores the following information:

* Employee Name
* Designation
* Father's / Husband's Name
* CNIC No.
* CNIC Expiry
* Birth Date
* Age
* Place of Birth
* Gender
* Marital Status
* Religion
* Country
* Telephone No.
* Mobile No.
* Emergency Contact No.
* Blood Group
* Emergency Contact Name
* Personal Email
* Official Email
* Address
* Permanent Address
* Employee Photo

## 🧭 Dashboard Sections

### Home

Provides an overview of the employee database, including:

* Total Employees
* Recently Added Employees
* Male Employees
* Female Employees
* Recent Employee Records

### Add New Employee

Allows the user to create a new employee record with complete personal, contact, emergency and address information.

Employee photos can also be uploaded and previewed before saving.

### Manage Employees

Displays all saved employee records in a searchable management table.

Available actions:

* View
* Edit
* Delete

Deleting an employee requires confirmation before the record is permanently removed from the browser storage.

### View Record

Allows users to search employees by:

* Employee Name
* CNIC Number

The selected employee's complete profile is displayed along with their photo.

The record can also be printed using the built-in print function.

### Export Data

Exports the complete employee database into an Excel-compatible `.xlsx` file.

**Employee photos are not included in the Excel export.**

## 💾 Data Storage

This project does not use a backend or online database.

Employee records are stored locally in the browser using:

```text
localStorage
```

This means:

* Data remains available after refreshing the page.
* No server is required.
* No database setup is required.
* Data is stored only in the browser where the application is being used.

> **Important:** Clearing the browser's site data/localStorage can remove the saved employee records. This project is therefore best suited for local/internal record management unless a backend database is added later.

## 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript (Vanilla JS)
* LocalStorage API
* SheetJS / XLSX for Excel export

## 📁 Project Structure

```text
Employee-Record-Management-System/
│
├── index.html
├── style.css
├── script.js
├── assets/
│
└── README.md
```

## 🚀 Running the Project

No installation or backend setup is required.

Simply open:

```text
index.html
```

in a modern web browser.

For development, the project can also be run using **VS Code Live Server** or any static development server.

## 🌐 Deployment

Because this is a completely frontend-only project, it can be deployed on static hosting platforms such as:

* GitHub Pages
* Netlify
* Vercel
* Cloudflare Pages

No server-side configuration is required.

## 🔐 Privacy

Employee information is stored locally in the user's browser and is not automatically uploaded to any server.

For real organizational use with multiple users or centralized access, a secure backend/database should be added in a future version.

## 📄 License

This project is intended for personal/internal use and can be modified according to project requirements.

---

### Employee Record Management System

**Frontend-only • HTML • CSS • JavaScript • LocalStorage**
