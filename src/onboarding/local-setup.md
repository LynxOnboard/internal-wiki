# Local Setup

## Requirements
- Git
- Node.js (for web)
- Python 3.x (for API)
- VSCode
- PyCharm (Optional but recommended for backend dev)
- Postman

## Backend
```bash
cd backend-api
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
uvicorn app.main:app --reload
```

## Frontend
```
cd web
npm install
npm run dev
```

## Environment variables

Environment variables are documented by name only.
Values live in the team password manager.