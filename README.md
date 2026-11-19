# IQ-Tech-Ticketing-System
TVETMARA Ledang — Customer Support Ticketing System

Course Code / Name: MFN1034 / Managing Computer Systems Maintenance

Program / Class: Diploma of Competency in Computer Networking and System Administration (DCN 1)

Institution: Kolej Kemahiran Tinggi MARA (KKTM) Ledang, Johor

📌 Project Title & Description

TVETMARA Ledang Customer Support Ticketing System is a web-based IT helpdesk application developed for Kolej Kemahiran Tinggi MARA (KKTM) Ledang. It streamlines technical support requests across campus labs, offices, and network infrastructure using a structured 6-stage ticket lifecycle.

✨ Main Features (Tasks 3.1 – 3.10)

Authentication & Role-Based Access Control (Task 3.3):

Customer self-registration with password hashing (non-plaintext).

Dynamic role detection redirecting Customers to the Customer Dashboard and Support Personnel to the Support Dashboard.

Strict route guarding preventing Customers from accessing Support-only views.

Customer Ticketing Portal (Task 3.4):

Live summary cards (Total Tickets, Open/New, In Progress, Resolved/Closed).

Ticket submission form supporting exact required categories (Network, Hardware, Software, Account/Login, System/Application, Other) and priorities (Low, Medium, High, Urgent).

Automatic unique ticket ID generator (TK-2026-0001, TK-2026-0002, etc.).

Support Management & Resolution Workflow (Tasks 3.5 & 3.6):

Support Dashboard displaying New, Open, In Progress, Waiting for Customer, and Resolved metrics.

Filterable Ticket Queue (Ticket ID | Customer | Subject | Category | Priority | Status | Action).

Two-way conversation thread enabling Support replies, Customer follow-ups, status updates, and ticket closure.

Relational Database & Testing Evidence (Tasks 3.7 & 3.8):

Built-in Relational Database Inspector (USERS, TICKETS, TICKET_MESSAGES) with one-click .sql export.

Built-in 14-point System Testing & Troubleshooting Log.

👥 User Roles

Customer (Student / Staff): Register, login, submit support tickets, track status, reply to support responses, and logout.

Support Personnel (IT Technician / Lecturer): Login, view incoming ticket queue, inspect customer details, update priority/status, respond to tickets, resolve, and close tickets.

🔄 Ticket Workflow

New ➔ Open ➔ In Progress ➔ Waiting for Customer ➔ Resolved ➔ Closed


🛠️ Technologies Used

Frontend: HTML5, Tailwind CSS, Vanilla JavaScript (ES6+)

Database: Relational Schema (USERS, TICKETS, TICKET_MESSAGES) implemented with browser localStorage persistence + MySQL/MariaDB SQL schema (database_schema.sql)

Hosting: GitHub & GitHub Pages
