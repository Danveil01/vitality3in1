# vitality3in1
A 3-in-1 web platform for Vitality Purified Mineral Water combining a public website, inventory &amp; sales management system, and real-time operational dashboard with financial automation, audit logs, and role-based access control.
# Vitality Sachet Water Management System (SWMS)

## Overview

The Vitality Sachet Water Management System (SWMS) is a modern 3-in-1 web application developed for **Vitality Purified Mineral Water**.

The platform combines:

1. Public Business Website
2. Inventory & Operational Management System
3. Administrative & Analytics Dashboard

The goal of the system is to digitize and automate the company’s operations while improving customer engagement, inventory tracking, production monitoring, financial accountability, and business intelligence.

---

# Core Modules

## 1. Public Website

Customer-facing website where users can:

- Learn about the company
- View products and pricing
- Read blog posts
- Contact the company
- Place online orders

### Website Pages

- Homepage
- About Page
- Products Page
- Blog Page
- Contact Page

### Website Features

- Responsive UI
- SEO-friendly architecture
- CMS-managed content
- Live blog publishing
- WhatsApp ordering integration
- Real-time order notifications

---

## 2. Inventory & Operations System

Handles daily operational records and business activities.

### Features

- Fleet truck sales management
- Third-party (3P) sales tracking
- Walk-in/office sales
- Ice pack sales management
- Production monitoring
- Poly roll tracking
- Inventory management
- Expense management
- Machine maintenance records
- Employee commission tracking
- Employee savings management

---

## 3. Dashboard & Analytics System

Role-based dashboard for monitoring business performance.

### Dashboard Features

- Real-time analytics
- Financial reconciliation
- Sales tracking
- Production tracking
- Inventory summaries
- Audit logs
- Activity monitoring
- Automated calculations
- Report generation

---

# User Roles

| Role | Description |
|---|---|
| Super Admin | Full system access and configuration |
| Admin | Operational and website management |
| Secretary | Sales, expenses, orders, reconciliation |
| Operator | Production and maintenance records |
| Auditor | Audit verification and monitoring |

---

# Key Features

## Customer Ordering System

Customers can:

- Select product type
- Choose order type
- Enter quantity
- Submit delivery orders

Orders are automatically:
- Stored in database
- Sent to dashboard
- Trigger notifications

---

## Blog & CMS Management

Admins can:

- Create blog posts
- Edit blog posts
- Delete blog posts
- Publish instantly
- Upload images
- Manage website content

No coding required for content updates.

---

## Fleet Sales Management

Tracks:

- Truck dispatch
- Driver assignments
- Mate assignments
- Fuel allocation
- Daily returns
- Revenue
- Commission splits
- Reconciliation

### Automated Calculations

The system calculates:

- Bags sold
- Expected revenue
- Commission
- Fuel deductions
- Net expected cash

---

## Third-Party (3P) Sales

Supports wholesale sales for external distributors.

### Features

- Wholesale pricing
- Customer tracking
- Receipt printing
- Payment tracking

---

## Production Management

Tracks:

- Poly roll batches
- Production output
- Yield efficiency
- Machine usage
- Operator commission
- Maintenance logs

---

## Employee Savings System

Supports commission retention system.

Example:
- Daily Commission = GHS 100
- Employee Takes = GHS 80
- Saved Amount = GHS 20

Savings accumulate monthly.

---

## Audit & Activity Logs

Tracks:

- Record edits
- User actions
- Login history
- Financial changes
- Dashboard activities

Ensures accountability and transparency.

---

## Automated Financial Reconciliation

The system compares:

- Expected cash
- Actual cash received

Automatically flags:
- shortages
- excess cash
- mismatches

---

## Duplicate Detection Engine

Automatically checks for:
- duplicate expenses
- duplicate sales entries
- duplicate production records

---

## Reporting System

Automated reports include:

- Sales summary
- Expense summary
- Production summary
- Inventory reports
- Profit analysis
- Charts & analytics

Reports can be exported as:
- PDF
- CSV
- Excel

---

# Product Categories

The system currently supports:

- Sachet Water
- Chilled Sachet Water
- Ice Pack / Ice Block Pack

---

# Tech Stack

| Category | Technology |
|---|---|
| Frontend | Next.js |
| Styling | Tailwind CSS |
| Backend | Supabase |
| Database | PostgreSQL |
| Authentication | Supabase Auth |
| Hosting | Vercel |
| Security | Row Level Security (RLS) |
| Offline Support | Progressive Web App (PWA) |

---

# Security Features

- Role-Based Access Control (RBAC)
- Secure authentication
- Protected routes
- Encrypted credentials
- Audit logs
- Immutable records
- Session management
- Duplicate detection

---

# System Architecture

The platform follows a modular architecture:

```text
Public Website
        ↓
Customer Orders
        ↓
Operations System
        ↓
Dashboard & Analytics
        ↓
Reports & Audit Logs
