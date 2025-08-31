# Contacts API

Simple Contacts API (learning project).  
Stack: Java + Spring Boot + MySQL + Docker.

## Quick start (dev)
1. Copy `.env.example` to `.env` and adjust if needed.
2. Build the JAR:
   ```bash
   ./mvnw clean package -DskipTests
   ```
3. Run with Docker:
```bash
docker compose up --build -d
docker compose logs -f app
```

## API (planned)
- GET /api/contacts
- GET /api/contacts/{id}
- POST /api/contacts
- PUT /api/contacts/{id}
- DELETE /api/contacts/{id}

## Workflow

- Branch names: feature/, fix/, chore/*
- Create PRs, reviewers assigned by CODEOWNERS
