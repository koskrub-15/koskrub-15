<h1 align="center">Hi, I'm Kostiantyn 👋</h1>

<p align="center">
  <b>Backend developer — Python</b><br>
  Async APIs with FastAPI &amp; Django · PostgreSQL · Docker · CI from day one<br>
  Rust on the side, for CLI tools and algorithms
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/kostiantyn-bevz-022901343/">
    <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white">
  </a>
  <a href="mailto:kostiantyn.bevz@gmail.com">
    <img alt="Email" src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white">
  </a>
</p>

---

### 🧭 About me

- 🐍 I build **backends in Python** — REST APIs, async database access, authentication, background logic.
- 🦀 I use **Rust** for small CLI tools and for working through algorithms and data structures.
- 🧪 Every project I publish ships with **tests, linters, type checking and GitHub Actions** — not as an afterthought, but from the first commit.
- 🐳 Comfortable with **Docker Compose**, multi-service setups (app + PostgreSQL + Redis + Nginx) and database migrations.
- 🚀 Currently: getting my **Habit RPG API** deployed to production on Fly.io.

---

### 🛠️ Tech stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css&logoColor=white)

**Backend**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white)
![Alembic](https://img.shields.io/badge/Alembic-6BA81E?style=for-the-badge&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=for-the-badge&logo=socketdotio&logoColor=white)

**Data & infrastructure**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=for-the-badge&logo=redis&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Fly.io](https://img.shields.io/badge/Fly.io-8B5CF6?style=for-the-badge&logo=flydotio&logoColor=white)

**Quality & tooling**

![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![Ruff](https://img.shields.io/badge/Ruff-D7FF64?style=for-the-badge&logo=ruff&logoColor=black)
![mypy](https://img.shields.io/badge/mypy-2A6DB2?style=for-the-badge&logo=python&logoColor=white)
![pre--commit](https://img.shields.io/badge/pre--commit-FAB040?style=for-the-badge&logo=precommit&logoColor=black)
![uv](https://img.shields.io/badge/uv-DE5FE9?style=for-the-badge&logo=uv&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

---

### 📌 Projects

<table>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/koskrub-15/habit-rpg-api">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/pin/?username=koskrub-15&repo=habit-rpg-api&theme=tokyonight&hide_border=true">
    <img alt="habit-rpg-api" src="https://github-readme-stats.vercel.app/api/pin/?username=koskrub-15&repo=habit-rpg-api&hide_border=true">
  </picture>
</a>

**⚔️ Habit RPG API** — a gamified habit tracker where real tasks grant XP, gold, items and achievements.

- FastAPI + **async SQLAlchemy 2.0** + Pydantic v2
- JWT auth with refresh-token rotation, Argon2 hashing
- A generic `RouterFactory` that generates 8 CRUD endpoints — with ownership rules — per resource
- **299 tests**, ~95% coverage, Alembic migrations, Docker

</td>
<td width="50%" valign="top">

<a href="https://github.com/koskrub-15/django-pc-builder">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/pin/?username=koskrub-15&repo=django-pc-builder&theme=tokyonight&hide_border=true">
    <img alt="django-pc-builder" src="https://github-readme-stats.vercel.app/api/pin/?username=koskrub-15&repo=django-pc-builder&hide_border=true">
  </picture>
</a>

**🖥️ Django PC Builder** — a custom-PC shop with live quoting, order tracking and a blog.

- Django 5.2 served over **both WSGI and ASGI** behind Nginx
- Real-time chat on Django Channels + Redis; admins quote builds inside the conversation
- Five-stage order tracker with email notifications
- Gunicorn + Daphne + PostgreSQL + Redis, one `docker compose up`

</td>
</tr>
</table>

---

### 📊 GitHub

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=koskrub-15&show_icons=true&hide_border=true&theme=tokyonight&include_all_commits=true&count_private=true">
    <img height="165" alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=koskrub-15&show_icons=true&hide_border=true&include_all_commits=true&count_private=true">
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=koskrub-15&layout=compact&hide_border=true&theme=tokyonight&langs_count=8">
    <img height="165" alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=koskrub-15&layout=compact&hide_border=true&langs_count=8">
  </picture>
</p>

---

### 📫 Get in touch

- **Email:** [kostiantyn.bevz@gmail.com](mailto:kostiantyn.bevz@gmail.com)
- **LinkedIn:** [kostiantyn-bevz](https://www.linkedin.com/in/kostiantyn-bevz-022901343/)
