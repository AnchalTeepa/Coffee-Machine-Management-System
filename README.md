# ☕ Coffee Machine Management System

<div align="center">

### A Centralized Coffee Machine Management Solution

**Built with Microsoft Power Apps, Microsoft Dataverse, and Power Fx**

</div>

---

## 📌 Project Overview

The **Coffee Machine Management System** is a low-code application developed using Microsoft Power Apps to centralize coffee machine records, manage machine images, compare specifications, and track approval workflows.

The application provides role-based navigation and structured review processes to improve the consistency, accessibility, and management of coffee machine information.

## 🎯 Business Problem

Managing coffee machine information manually can lead to scattered records, inconsistent pricing and stock details, unclear approval status, and difficulties comparing machine specifications.

This project addresses these challenges by providing a centralized application for machine data, image storage, comparison, and multi-level approval tracking.

## ✨ Key Features

- **Machine Management:** Add, edit, and view coffee machine records, including brand, type, model, supplier, price, and stock details.
- **Image Management:** Upload machine images to Dataverse and display linked images on machine detail and review screens.
- **Two-Level Approval Workflow:** Enable Level 1 review followed by Level 2 final approval or rejection.
- **Machine Comparison:** Compare two selected coffee machines side by side and dynamically update displayed specifications.
- **Role-Based Navigation:** Provide dedicated application screens for Admin, User, Level 1 Reviewer, and Level 2 Reviewer.
- **Master Data Management:** Maintain reference data for brands, machine types, models, suppliers, and locations.
- **Status Tracking:** Update machine approval status and provide confirmation or error messages during key actions.
- **Dashboard:** Provide central navigation, shortcuts, and summary cards for machine counts and review status.

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| Microsoft Power Apps | Canvas application, forms, dashboards, and comparison screens |
| Microsoft Dataverse | Storage for machine records, images, users, and related business data |
| Power Fx | Input validation, record operations, control behavior, and approval status updates |

## 👥 Application Roles

| Role | Responsibility |
|---|---|
| **Admin** | Manage machine information and related records |
| **User** | Access available application features according to assigned permissions |
| **Level 1 Reviewer** | Review machine records and approve or reject submissions |
| **Level 2 Reviewer** | Perform the final approval or rejection |

*Access and available actions depend on the application's configuration and role validation.*

## 🔄 Application Workflow

1. The employee logs in and opens the dashboard for their role.
2. The administrator enters machine details and uploads a machine image.
3. Dataverse stores the machine record and its linked image.
4. The Level 1 Reviewer reviews the machine and approves or rejects it.
5. The Level 2 Reviewer makes the final approval or rejection decision.
6. The Master Data screen displays the updated machine status.

## 🗄️ Data Model

The application uses Microsoft Dataverse to organize machine information and related records.

| Table | Purpose |
|---|---|
| **Coffee Machines** | Stores machine names, serial numbers, pricing, stock, descriptions, and approval status |
| **Coffee Machine Images** | Stores machine photos and upload information, linked to machine records |
| **Machine Brands** | Maintains brand reference data |
| **Machine Types** | Maintains machine type information |
| **Machine Models** | Maintains model reference data |
| **Suppliers** | Stores supplier information |
| **Locations** | Maintains location reference data |
| **App Users** | Stores application users, assigned roles, and active status |
| **Supporting Tables** | Includes Coffee Machine Sales, Inventory Transactions, Approval Configurations, Approval Histories, and Duplicate Records |

## 🖥️ Main Application Screens

- **Login Screen:** Accepts email, password, and role selection; validates details against active application user records.
- **Home Dashboard:** Provides navigation to machine records, inventory, sales, and comparison screens.
- **Machine Management Screen:** Supports machine record creation, editing, and viewing.
- **Image Management Screen:** Displays images associated with machine records.
- **Machine Comparison Screen:** Compares specifications of two selected machines.
- **Review Screens:** Support Level 1 and Level 2 approval decisions.
- **Master Data Screen:** Displays updated machine information and approval status.

## 📈 Results and Business Value

- Centralized machine records and images in Dataverse.
- Connected application forms to saved records.
- Enabled side-by-side comparison of machine specifications.
- Supported approval and rejection with status updates.
- Improved visibility into machine information and review status.
- Reduced repeated data entry and improved consistency in machine comparisons.

## 👩‍💻 Author

**Anchal Teepa**  
B.Tech in Computer Science and Engineering | 2026

---

<div align="center">

*Demonstrating centralized data management and structured approval workflows with Microsoft Power Platform.*

</div>
