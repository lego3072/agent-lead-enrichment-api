# Agent Lead Enrichment API

Company profile, likely budget tier, urgency indicators, and suggested next action returned in one structured response.

## Run locally
```bash
pip install -r requirements.txt
uvicorn app.main:app --reload --port 8000
```

## Endpoints
- `/`
- `/docs-page`
- `/health`
- `/v1/public/config`
- `/llms.txt`
