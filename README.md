Velox API
A lightweight REST API built with FastAPI

!Python
!FastAPI
!License

---

A minimal REST API for user authentication and resource management. No unnecessary dependencies, no bloat.

Installation
git clone https://github.com/yourname/velox-api.git
cd velox-api
pip install -r requirements.txt
uvicorn app.main:app --reload


API runs at http://localhost:8000 · Docs at /docs

Endpoints
| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | /auth/login | Obtain JWT token |
| GET | /users/me | Get current user |
| GET | /items/{id} | Retrieve item |
| POST | /items | Create item |
