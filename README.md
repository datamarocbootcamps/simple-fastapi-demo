# Task API

A tiny FastAPI app used as the demo project for the Git & GitHub lesson.

## Run locally

```bash
pip install -r requirements.txt
uvicorn main:app --reload --port 8000
```

Then open http://localhost:8000/docs for the interactive API.

## Endpoints

- `GET /tasks` — list all tasks
- `POST /tasks` — create a task (`{"title": "...", "done": false}`)
- `GET /tasks/{id}` — get one task
- `PUT /tasks/{id}` — update a task
- `DELETE /tasks/{id}` — delete a task
