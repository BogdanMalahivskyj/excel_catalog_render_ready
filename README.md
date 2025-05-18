# Excel Catalog Generator (FastAPI)

Генерує Excel-файл із фото, описами, розмірами та цінами.

## Локальний запуск:
```bash
pip install -r requirements.txt
uvicorn main:app --reload
```

Swagger: http://localhost:8000/docs

## Деплой на Render
- New Web Service
- Build command: pip install -r requirements.txt
- Start command: uvicorn main:app --host 0.0.0.0 --port 10000
- Port: 10000
