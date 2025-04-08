from pathlib import Path


# 📝 ToDo App (FastAPI + SQLAlchemy + Jinja2)

Це простий веб-застосунок для управління завданнями (ToDo), створений на базі **FastAPI**, **SQLAlchemy** та **Jinja2 Templates**. Ви можете додавати, відмічати як виконані, та видаляти задачі.

---

## 🚀 Стек технологій

- **FastAPI** – асинхронний фреймворк для створення API
- **SQLAlchemy** – ORM для взаємодії з базою даних
- **SQLite** – легка файлова база даних
- **Jinja2** – шаблонізатор для HTML-інтерфейсу
- **Starlette** – для шаблонів, редіректів, відповіді на запити

---

## 🏁 Як запустити

### 1. Клонувати репозиторій:

```bash
git clone https://github.com/your_username/fastapi-todo.git
cd fastapi-todo

pip install -r requirements.txt


uvicorn todo.main:app --reload


🗂 Структура проєкту

D:.
├───.idea
│   └───inspectionProfiles       
├───todo
│   ├───database
│   │   ├───DB
│   │   └───__pycache__
│   ├───static
│   │   └───css
│   ├───templates
│   │   └───todo
│   ├───todo
│   │   └───database
│   │       └───DB
│   └───__pycache__

