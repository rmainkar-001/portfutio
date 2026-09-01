# 🤖 ERP Agent

## AI-Powered Conversational ERP Assistant

**ERP Agent** is an AI-powered assistant designed to let ERP users interact with business data using natural language instead of navigating multiple reports and screens.

---

## 🎯 Business Problem

ERP users often need to search across sales, inventory, purchasing, and branch data before finding an answer.

```text
Open ERP
 ↓
Select Module
 ↓
Select Branch
 ↓
Apply Filters
 ↓
Run Report
 ↓
Analyze Data
```

ERP Agent simplifies this interaction:

```text
Business Question
 ↓
AI Agent
 ↓
Understand Intent
 ↓
Identify Relevant Data
 ↓
Generate / Validate Query
 ↓
ERP Database
 ↓
Business Answer
```

---

## ⭐ Key Features

- 🤖 Natural-language ERP queries
- 🧠 AI agent workflow
- 🔎 Database schema awareness
- 🗃️ Natural Language → SQL
- ✅ Query validation
- 📊 Business-data analysis
- ⚡ Streaming responses
- 🔐 Controlled database access

---

## 🏗️ Application Architecture

```text
                    User
                     │
                     ▼
              React AI Assistant
                     │
                     ▼
                  FastAPI
                     │
                     ▼
                AI Agent
                     │
          ┌──────────┼──────────┐
          ▼          ▼          ▼
       Intent      Schema     Context
       Analysis    Discovery  Handling
          │          │          │
          └──────────┼──────────┘
                     ▼
                SQL Generation
                     │
                     ▼
                SQL Validation
                     │
                     ▼
                 PostgreSQL
                     │
                     ▼
               Result Processing
                     │
                     ▼
               Business Answer
```

---

## 🔄 Query Workflow

```text
User Question
      ↓
Understand Question
      ↓
Identify Business Context
      ↓
Find Relevant Tables
      ↓
Generate SQL
      ↓
Validate SQL
      ↓
Execute Query
      ↓
Process Result
      ↓
Generate Natural-Language Answer
```

---

## 🧩 Real-World Example

A business user asks:

```text
"Which branch sold the most Bhakarwadi this month?"
```

The system can reason about:

```text
Product
   ↓
Sales
   ↓
Branch
   ↓
Date Range
   ↓
Aggregation
```

Other examples:

```text
"Which products are low in stock?"

"Show pending purchase orders."

"Compare this month's sales with last month."

"Which branch has the highest sales?"
```

---

## 🧠 AI Workflow

```text
Question
   ↓
Agent
   ↓
Intent
   ↓
Schema
   ↓
Query Plan
   ↓
SQL
   ↓
Validation
   ↓
Database
   ↓
Result
   ↓
Answer
```

---

## 🛠️ Technology Stack

| Area | Technology |
|---|---|
| Frontend | React.js |
| Backend | Python |
| API | FastAPI |
| AI Orchestration | LangChain / LangGraph |
| LLM | LLM APIs |
| Database | PostgreSQL |
| Streaming | SSE / Streaming APIs |

---

## 👨‍💻 My Contribution

- AI assistant integration
- FastAPI API development
- Agent workflow design
- ERP data interaction
- Natural-language query handling
- Database integration
- Streaming response handling
- Frontend AI assistant experience
- Validation and error workflows

---

## ⚡ Engineering Focus

### AI Agent Design

Designed the workflow so the model does not operate as an unrestricted database interface.

### SQL Safety

Used validation and controlled execution concepts between generated queries and the database.

### ERP Context

Focused the agent around real business entities such as products, sales, branches, inventory, purchasing, and orders.

---

## 📊 Business Areas

```text
ERP Agent
│
├── Sales
├── Inventory
├── Products
├── Branches
├── Purchasing
├── Orders
├── Reporting
└── Business Analytics
```

---

## 🔐 Source Code

The production implementation is not publicly exposed.

This portfolio page presents the architecture, workflows, technologies, and engineering concepts without exposing proprietary source code, credentials, internal configuration, or company-specific implementation.

For a detailed technical discussion, please contact **Rohit**.

---

## 📌 Project Summary

**ERP Agent** demonstrates how AI agents can be integrated with enterprise applications to provide a natural-language interface over business data while maintaining controlled database access and application-level validation.

**Primary Focus:** React • Python • FastAPI • LangGraph • LangChain • PostgreSQL • AI Agents
