# 🍬 SweetPOS

## Retail Billing & Inventory Management System

**SweetPOS** is a retail management platform designed for **sweet shops, dairy stores, and food-retail businesses**.

The system brings billing, inventory, stock management, and operational workflows into a single application.

---

## 🎯 Business Problem

Retail businesses need to manage multiple activities every day:

```text
Sales
 ↓
Billing
 ↓
Inventory Update
 ↓
Stock Tracking
 ↓
Reports
```

The goal of SweetPOS is to make these operations faster, simpler, and easier to manage from a single system.

---

## ⭐ Key Features

* 🧾 Retail billing
* 📦 Inventory management
* 📊 Stock tracking
* 💰 GST-related billing workflows
* 📈 Business dashboards
* 📱 Mobile application support
* 📴 Offline workflows
* 🔄 Data synchronization
* 📋 Business reporting

---

## 🏗️ Application Architecture

```text
                    User
                     │
          ┌──────────┴──────────┐
          │                     │
          ▼                     ▼
     Web Application       Mobile Application
          │                     │
          ▼                     ▼
       React.js            React Native
          │                     │
          └──────────┬──────────┘
                     ▼
                 REST APIs
                     │
                     ▼
              Business Services
                     │
                     ▼
                  MySQL
                     │
          ┌──────────┴──────────┐
          ▼                     ▼
       Billing              Inventory
          │                     │
          └──────────┬──────────┘
                     ▼
                  Reports
```

---

## 🔄 Billing Workflow

```text
Select Products
      ↓
Add to Cart
      ↓
Calculate Quantity
      ↓
Apply Pricing / Tax Rules
      ↓
Generate Bill
      ↓
Update Inventory
      ↓
Store Transaction
      ↓
Generate Receipt
```

---

## 📦 Inventory Workflow

```text
Purchase / Stock Entry
        ↓
Inventory Update
        ↓
Current Stock
        ↓
Sales Transaction
        ↓
Stock Deduction
        ↓
Low Stock Detection
        ↓
Inventory Report
```

---

## 📴 Offline Workflow

One of the important application requirements was supporting retail operations where network connectivity may not always be reliable.

```text
User
 ↓
Mobile Application
 ↓
Network Available?
 ├── Yes → API → Server
 │
 └── No
      ↓
   Local Data
      ↓
   Continue Operation
      ↓
   Network Restored
      ↓
   Synchronize
```

---

## 📱 Web & Mobile

SweetPOS supports both web and mobile-oriented workflows.

```text
             SweetPOS
                 │
        ┌────────┴────────┐
        │                 │
        ▼                 ▼
      Web              Mobile
        │                 │
     React.js        React Native
        │                 │
        └────────┬────────┘
                 ▼
              Backend
                 │
                 ▼
              MySQL
```

---

## 🛠️ Technology Stack

| Area             | Technology        |
| ---------------- | ----------------- |
| Web              | React.js          |
| State Management | Redux             |
| Mobile           | React Native      |
| Backend          | REST APIs         |
| Database         | MySQL             |
| Communication    | Axios / HTTP APIs |
| UI               | Responsive Web UI |

---

## 👨‍💻 My Contribution

Worked primarily on the **frontend and application experience**, including:

* React application development
* Reusable UI components
* Redux state management
* API integration
* Responsive interfaces
* Billing workflows
* Inventory-related screens
* Mobile application development
* Performance optimization
* UI/UX improvements
* Business workflow implementation

---

## ⚡ Engineering Focus

### Performance

Focused on reducing unnecessary frontend rendering and improving application responsiveness.

### Reusable Components

Designed reusable UI components to reduce duplication and make new business screens easier to develop.

### State Management

Used Redux to manage shared application state across billing, inventory, and other business workflows.

### Responsive Design

Designed interfaces that work across desktop and mobile-oriented use cases.

---

## 🧩 Example Business Scenario

A sweet shop receives a customer order:

```text
Customer
   ↓
Select Products
   ↓
Bhakarwadi × 2
Kaju Katli × 1
Mango Barfi × 1
   ↓
Calculate Bill
   ↓
Generate Invoice
   ↓
Update Inventory
   ↓
Store Sale
```

The inventory is updated as part of the sales workflow so that the business can maintain an up-to-date view of available stock.

---

## 📊 Business Areas

```text
SweetPOS
│
├── Billing
├── Products
├── Inventory
├── Stock
├── Sales
├── Customers
├── Reports
└── Mobile Operations
```

---

## 🔐 Source Code

The production implementation is not publicly exposed.

This portfolio page provides the **system overview, architecture, business workflows, technologies, and my contribution** without exposing proprietary implementation details.

For a detailed technical discussion of the implementation and architecture, please contact **Rohit**.

---

## 📌 Project Summary

**SweetPOS** demonstrates experience building a real-world retail application where frontend engineering, mobile development, API integration, inventory workflows, and business requirements come together in a production-oriented system.

**Primary Focus:** React • React Native • Redux • MySQL • Enterprise Retail Workflows
