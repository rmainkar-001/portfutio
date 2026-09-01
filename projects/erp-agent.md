# 🤖 ERP Agent

## AI-Powered Conversational ERP Assistant

ERP Agent is an AI-powered assistant designed to let users interact with enterprise ERP data using natural language.

Instead of manually navigating reports and filters, users can ask business questions directly.

### Example

> Which branch sold the most Bhakarwadi?

> Show products with low stock.

> Show pending purchase orders.

> Give me this month's sales summary.

---

## 🔄 Workflow

```text
User
 ↓
AI Assistant
 ↓
FastAPI
 ↓
AI Agent
 ↓
Understand User Intent
 ↓
Database Schema
 ↓
Generate SQL
 ↓
Validate SQL
 ↓
Execute Query
 ↓
PostgreSQL
 ↓
Business Response
