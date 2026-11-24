# Hi, I'm Prudhvi Krishna 👋

**Python backend developer (FastAPI) with an AI/ML background** · Artificial Intelligence graduate · Nellore, India (UTC+5:30)

I build API-first systems with real business rules: authentication, role-based access, payments, payroll, notifications and audit trails. Open to **entry-level backend / Python / FastAPI / Django roles**, including night shifts, and ready to join quickly.

📧 [prudhvikrishna2426@gmail.com](mailto:prudhvikrishna2426@gmail.com)

---

## 🛠 Tech stack

| Area | Tools |
|---|---|
| Languages | Python, SQL, JavaScript |
| Backend | FastAPI, Django, SQLAlchemy, Alembic, Pydantic, Flask |
| Frontend | React (Vite), Tailwind CSS, TanStack Query |
| Databases | MySQL, PostgreSQL, SQLite |
| Auth & payments | JWT (access + rotating refresh), OAuth (Google / Facebook), RBAC, Stripe |
| AI / ML | scikit-learn, NLTK, TF-IDF, RAG (Qdrant, sentence-transformers, Ollama) |
| DevOps & tools | Docker, GitHub Actions, Git, Postman, pytest |

---

## 🚀 Featured projects

### 🛒 [ShopStream](https://github.com/PrudhviKris/ShopStream) — full-stack e-commerce platform
FastAPI API + React storefront + Django admin with analytics, all on one MySQL database.
- Stripe Checkout / PaymentIntent with signed-webhook handling (mock mode for local runs)
- JWT with rotating refresh tokens, Google & Facebook login, admin / staff / customer RBAC re-checked from the DB on every request
- Real-time WebSocket events, order lifecycle, returns & refunds, moderated reviews, SQL-based recommendations
- Alembic migrations, Docker Compose, Postman collection, Chart.js analytics and CSV/PDF reports
- Tests: pytest suite, a 332-check end-to-end smoke script and 58 Django admin tests (counts from the repo README)

### 👥 [HR_Management_System](https://github.com/PrudhviKris/HR_Management_System) — HRMS (FastAPI + React)
- Employee onboarding, attendance, leave with balance/LOP rules, and payroll with a draft → locked → paid lifecycle
- PDF salary slips, template-based email notifications, reports exportable to CSV/PDF
- 25 fine-grained permissions with custom roles; refresh-token reuse detection; account lockout
- Read-only audit log enforced by MySQL triggers; secure file uploads (magic-byte checks, size limits)
- 29 API-level pytest tests (per README); ER diagram, schema, Postman collection and screenshots included

### 📝 [BLOG_Management_APP](https://github.com/PrudhviKris/BLOG_Management_APP) — blogging platform with an AI assistant
- Drafts, scheduled publishing (APScheduler), comments, likes, in-app notifications
- Subscription plans with enforced limits and PDF invoices (payment is simulated)
- RAG FAQ assistant (Qdrant + sentence-transformers + Ollama) with automatic keyword fallback
- Pytest suite and GitHub Actions CI; Dockerfile included

### 🤖 [Cyberbullying Detection](https://github.com/PrudhviKris/Cyberbullying-Detection-ML) — NLP classifier
- Compared 7 classical ML models on ~18,000 labelled texts with TF-IDF features
- Served a tuned LinearSVC (96.4% test accuracy, 0.17 s training) through a Flask app

---

## 🎯 What I care about

- **Correctness in the business rules**, not just CRUD: idempotent webhooks, state-machine transitions, locked payroll months
- **Security by default**: hashed passwords, token rotation, object-level permission checks, input validation
- **Reproducible projects**: seed data, migrations, Docker, API collections and tests in every repo

---

## 📫 Let's connect

I'm looking for my first full-time backend role. If you're hiring for Python / FastAPI / Django, email me at **prudhvikrishna2426@gmail.com**, or open any project above and read its README first.
