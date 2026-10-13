# DocuMind: AI Knowledge Assistant (RAG)

Upload documents and ask questions. Answers come from your documents, with sources.

## Tech stack
Java 21, Spring Boot, Spring AI, PostgreSQL + pgvector, Kafka, Redis, Docker, GitHub Actions, AWS

## Run locally
1. `docker compose up -d`
2. `cd services/api-service && ./mvnw spring-boot:run`
3. `curl http://localhost:8080/api/ping`

## Status
Work in progress (Day 1: project skeleton)