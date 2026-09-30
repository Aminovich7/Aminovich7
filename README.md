# Mukhammad Batoshev

**Python Backend Developer · FastAPI · Django REST Framework · Django**

Tashkent, Uzbekistan · Open to backend developer roles · [m.aminovich7@gmail.com](mailto:m.aminovich7@gmail.com) · Telegram [@aminovich7](https://t.me/Aminovich7)

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?logo=django&logoColor=white)
![DRF](https://img.shields.io/badge/DRF-A30000?logo=django&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?logo=celery&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)

I build backend systems in Python, mostly with FastAPI and async SQLAlchemy. My most complete work is a finance and payroll system for a private clinic that I designed, built, tested and deployed on my own. It replaced the clinic's spreadsheets and paper records and is deployed to production.

I care about getting the details right: exact money arithmetic, role-based access enforced on the server, tests against a real database, and deployments that are documented and backed up.

---

## Featured project

### [Clinic CRM](https://github.com/Aminovich7/clinic-crm-showcase) — FastAPI · deployed to production

Receipts, doctors' commissions, payroll, pharmacy account and expenses for a private clinic, with a dashboard and Excel-exportable reports.

- **86 API endpoints** across 8 modules, three user roles, server-rendered UI in Uzbek
- **158 automated tests** against real PostgreSQL and Redis, including 65 HTTP-level security and permission tests
- **Correct by design:** `Decimal` money with per-receipt rounding, business dates in Tashkent time, salary proration by working day
- **Hardened:** JWT with token revocation, Argon2, rate-limited login, strict CSP, non-root container; fixed an N+1 query that ran five queries per staff member
- **Operated:** Docker on Render, PostgreSQL on Neon, Redis, daily verified backups with retention

FastAPI · SQLAlchemy 2.0 (async) · PostgreSQL · Alembic · Redis · Pydantic v2 · pytest · Docker

[**Read the case study →**](https://github.com/Aminovich7/clinic-crm-showcase) *(source is private, client project — walkthrough on request)*

---

## FastAPI

### [EduGroup](https://github.com/Aminovich7/edugroup) — online learning platform

Teachers run courses and groups with video lessons; students enrol, pay in full or by instalments, and only then unlock the lessons; managers approve profiles and payments; a superadmin sees system-wide reports.

- Four roles with a documented permission matrix; one FastAPI app serves both a JSON API and a Jinja2 web UI
- Instalment payment plans with scheduled Celery jobs that expire stale enrolments hourly and flag overdue instalments daily
- **193 passing tests** · Docker Compose with PostgreSQL, Redis, Celery worker and beat · rate limiting

FastAPI · async SQLAlchemy · PostgreSQL · Alembic · Celery · Redis · JWT · pytest · Docker

### [FastAPI course work](https://github.com/Aminovich7/najot-talim/tree/main/fastapi-nt)

Nine homework projects that build from basic CRUD to async SQLAlchemy, Alembic migrations, JWT auth, pytest and Redis, finishing with Celery and RabbitMQ background processing.

---

## Django REST Framework

| Project | What it is | Highlights |
|---|---|---|
| [**Suhulat**](https://github.com/Aminovich7/suhulat.uz) | Marketplace for goods sold by weight or volume: listings, requests for quotation with counter-offers, orders, cart, reviews, admin moderation | Order status workflow, JWT with token blacklist, role-based permissions, throttling, OpenAPI docs, 19 tests |
| [**Job-X**](https://github.com/Aminovich7/job-x) | Freelance marketplace API, Upwork-style: projects, bids, contracts | 28 endpoints, JWT, filtering, OpenAPI docs, Postman collection · team project |

## Django

| Project | What it is |
|---|---|
| [**Smart City**](https://github.com/Aminovich7/smart-city) | Incident reporting for city services with four roles: citizens report with photos, operators assign, technicians resolve, citizens confirm · team project |
| [**Clinic management**](https://github.com/Aminovich7/project-x) | Doctors, consultations, surgeries and room stays with doctor-share and profit reports · Docker |
| [**Mini Online Shop**](https://github.com/Aminovich7/mini-online-shop) | Buyer and seller accounts, cart with promo codes, checkout and order history |
| [**Najot Ta'lim course work**](https://github.com/Aminovich7/najot-talim) | Django, DRF and FastAPI homework and exam projects, one folder each |

---

## Skills

- **Languages:** Python, SQL, JavaScript
- **Frameworks:** FastAPI, Django, Django REST Framework, Pydantic, Jinja2
- **Data:** PostgreSQL, SQLAlchemy 2.0 (sync and async), Django ORM, Alembic
- **Async and messaging:** asyncio, Celery, Redis, RabbitMQ
- **Auth and security:** JWT (access/refresh tokens, revocation), OAuth2 password flow, Argon2/bcrypt, role-based access, rate limiting, CSP and security headers
- **Testing:** pytest, pytest-asyncio, httpx, Django test framework
- **DevOps:** Docker, Docker Compose, Render, Neon, Git
- **API tooling:** OpenAPI/Swagger, drf-spectacular, Postman

## Contact

The quickest way to reach me is [email](mailto:m.aminovich7@gmail.com) or Telegram [@aminovich7](https://t.me/Aminovich7).
