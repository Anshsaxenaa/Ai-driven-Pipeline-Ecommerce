# 🧠 AI-Driven Ecommerce Pipeline (Supabase + Vite + Prometheus)

This repository contains a full-stack demo of an **AI-driven ecommerce pipeline** with integrated **observability and monitoring**.  
The project showcases a modern frontend backed by **Supabase**, extended with **AI features**, and monitored using **Prometheus**.

---

## 🚀 Features

### Storefront

- Product listing & detail pages powered by **Supabase**
- Responsive, fast UI built with **Vite + React + TypeScript**
- Tailwind CSS for styling and layout
- Authentication and user management (via Supabase)

### AI-Driven Pipeline

- AI-assisted product improvements and personalization
- Support for adding product recommendations, automated descriptions, or trend analysis
- Framework ready for integration with any LLM provider (OpenAI, Anthropic, etc.)

### 📊 Monitoring & Metrics (Prometheus)

The project includes **Prometheus** for application monitoring and pipeline visibility:

- Collects custom metrics such as API usage, request performance, and system health
- Enables performance optimization for ecommerce workloads
- Supports future **Grafana dashboards** for visualization
- Helps monitor AI inference load, latency, and failure rates (if added)

> Prometheus configuration and metrics endpoints can be found inside the backend or middleware layer of the project (depending on setup).

---

## 🧱 Tech Stack

- **Frontend**
  - Vite + React + TypeScript
  - Tailwind CSS

- **Backend / Data**
  - Supabase (Postgres, Auth, Storage)

- **Monitoring / Observability**
  - Prometheus
  - Optional support for Grafana dashboards

- **Tooling**
  - ESLint, PostCSS, Vite config, environment variables in `.env`

---

## 📂 Project Structure

```text
.
├── src/                     # Frontend files
│   ├── components/          
│   ├── pages/
│   ├── hooks/
│   └── main.tsx
├── supabase/                # Database config and migrations
├── prometheus/              # Prometheus monitoring config (if applicable)
├── public/                 
├── .env
├── package.json
└── vite.config.ts
