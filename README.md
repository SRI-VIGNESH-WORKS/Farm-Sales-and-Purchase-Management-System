# Farm Sales & Purchase Management System

A full-stack farm business management application designed to simplify sales, purchases, inventory tracking, payment management, and financial reporting through a centralized digital platform.

## Project Links

**Live Demo:** https://farm-sales-project.vercel.app/

## Overview

The Farm Sales & Purchase Management System, also known as **Digital Farm Register**, is a web-based application developed to help farm businesses manage their daily commercial activities efficiently.

The system replaces manual registers and disconnected records with a centralized platform for handling sales transactions, purchase records, stock movements, customer and supplier accounts, payments, and financial analytics.

It provides an organized workflow for tracking business transactions, monitoring inventory, managing outstanding balances, and reviewing financial performance.

## Key Features

### 1. Sales and Invoice Management

* Create and manage sales transactions.
* Generate invoices with applicable tax calculations.
* Maintain organized sales records.
* Process sales returns.
* Track payments received from customers.

### 2. Purchase Management

* Record purchases from suppliers.
* Maintain purchase transaction history.
* Track purchase-related payments.
* Manage purchase returns.
* Keep purchase records organized for financial review.

### 3. Inventory Management

* Track available product stock.
* Update inventory based on sales and purchases.
* Record stock adjustments.
* Monitor stock movements.
* Maintain more accurate inventory records.

### 4. Customer Management

* Maintain customer information.
* Track customer transactions.
* Manage outstanding customer balances.
* Maintain customer credit ledgers.
* Record payments received from customers.

### 5. Supplier Management

* Maintain supplier records.
* Track purchases associated with suppliers.
* Manage outstanding supplier balances.
* Maintain supplier credit ledgers.
* Record payments made to suppliers.

### 6. Payment Management

* Record and track business payments.
* Support multiple payment methods:

  * Cash
  * Bank transfer
  * UPI
  * Card
  * Other payment methods
* Maintain payment records for sales and purchases.
* Track outstanding amounts and payment balances.

### 7. Financial Reports and Analytics

* Review sales and purchase information.
* Monitor financial performance.
* Analyze gross profit.
* Access business reports and transaction summaries.
* Use financial information to support business decisions.

### 8. User Roles and Access Control

* Support administrator and staff roles.
* Apply role-based access restrictions.
* Provide authentication for protected application features.
* Maintain audit trails for improved transaction accountability.

## Technology Stack

The project uses the following technologies:

### Frontend

* React 18
* TypeScript
* Vite
* Tailwind CSS
* Lucide React
* Recharts

### Backend

* Node.js
* Express.js
* Prisma ORM

### Database

* PostgreSQL for production
* SQLite for local development

### Validation and Security

* Zod
* JSON Web Tokens (JWT)
* bcryptjs

### Testing and Deployment

* Vitest
* Vercel

## Application Architecture

The application follows a full-stack architecture in which the frontend communicates with the backend to process business operations and manage application data.

```text
Farm Sales & Purchase Management System
                 |
                 v
       Frontend Application
        React + TypeScript
                 |
                 v
          Backend API
          Node.js + Express
                 |
                 v
            Prisma ORM
                 |
                 v
             Database
       PostgreSQL / SQLite
```

## Getting Started

Follow these steps to set up the project locally.

### Prerequisites

Make sure the following tools are installed:

* Node.js
* npm
* Git
* A compatible database configuration for your environment

### 1. Clone the Repository

```bash
git clone https://github.com/SRI-VIGNESH-WORKS/Farm-Sales-and-Purchase-Management-System.git
```

### 2. Navigate to the Project Directory

```bash
cd Farm-Sales-and-Purchase-Management-System
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Configure Environment Variables

Create the required environment configuration file based on the project's existing environment template and database setup.

Configure the necessary values for:

* Database connection
* Authentication secrets
* Backend configuration
* Frontend API configuration, if required

**Important:** Use environment variables for credentials and secrets. Do not commit passwords, private keys, or production environment files to the repository.

### 5. Configure the Database

Configure the database connection according to the project's Prisma schema and environment settings.

For Prisma-based database workflows, the appropriate migration or schema synchronization command depends on the scripts defined in the project.

### 6. Run the Application

Use the development scripts configured in `package.json`.

```bash
npm run dev
```

If the project uses separate frontend and backend development commands, start each service using its corresponding script.

### 7. Open the Application

Open the local development URL displayed in your terminal after the development server starts.

> **Note:** The exact setup commands, environment variables, and database migration steps may vary depending on the project's current configuration.

## Usage

Once the application is running:

1. Sign in using an authorized account.
2. Manage customer and supplier information.
3. Record sales and generate invoices.
4. Enter purchase transactions.
5. Monitor stock levels and record inventory adjustments.
6. Track customer and supplier payments.
7. Review financial reports and gross profit analytics.
8. Use the available access controls to manage administrative and staff operations.

## Security Considerations

* Use secure authentication practices.
* Store passwords using appropriate password-hashing mechanisms.
* Keep authentication secrets and database credentials in environment variables.
* Restrict access to administrative operations based on user roles.
* Avoid exposing sensitive configuration values in source control.
* Maintain transaction and audit records for accountability.

## Future Enhancements

Potential improvements for future versions include:

* Advanced inventory forecasting.
* More detailed financial dashboards.
* Enhanced report filtering and export options.
* Additional business performance metrics.
* Improved mobile usability.
* Expanded audit and transaction history features.

## Author

**SRI**

GitHub: [SRI-VIGNESH-WORKS](https://github.com/SRI-VIGNESH-WORKS)

## Project Information

This project demonstrates the application of modern full-stack web development technologies to farm business operations, including transaction management, inventory control, database integration, authentication, and financial reporting.
