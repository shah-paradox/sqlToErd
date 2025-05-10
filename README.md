# SQL-to-ERD Generator

A web application that reads raw SQL code, extracts tables, columns, relationships, and constraints using a GPT-powered backend, and generates a visual ERD (Entity-Relationship Diagram) using PlantUML. It also optionally generates dummy data using the Faker library.

---

## 🚀 Features

- Upload raw SQL code (DDL)
- Extract table structures and relationships via GPT API (or RAG system)
- Generate ERD / Extended ERD diagrams with PlantUML
- Visualize ER diagrams in the browser
- Generate dummy data for tables using Faker
- Clean, modular React + Express architecture

---

## 🏗 Tech Stack

- **Frontend:** React (Vite), Axios
- **Backend:** Node.js, Express, OpenAI GPT API, PlantUML, Faker.js / Python Faker
- **Deployment (future):** Docker, Vercel/Netlify (frontend), Render/Fly.io (backend)

---

## ⚙ Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/sql-to-erd.git
cd sql-to-erd
