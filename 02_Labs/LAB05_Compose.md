# Lab 05 — Docker Compose

Use [FIT4110_lab05_docker_compose](https://github.com/TrangLe1912/FIT4110_lab05_docker_compose). Compose expresses the runnable architecture: services, networks, configuration, startup checks, and persistent data.

```mermaid
flowchart LR
  Client --> API[API :8000]
  API --> AI[AI service :9000]
  API --> DB[(PostgreSQL)]
  API --- N[team-internal network]
  AI --- N
  DB --- N
```

Copy `.env.example` to a local `.env`; do not commit it. Run `docker compose up -d --build`, inspect `docker compose ps` and logs, exercise API and AI health endpoints, and run the Compose test target if supplied.

> Source compatibility note: the current starter declares an external `class-net`, so create it first if it is not provided (`docker network create class-net`). Its published Compose test script is a TODO placeholder; copy/adapt your Lab 04 collection and document the actual Newman command/report. The API healthcheck may also need a Python-based check if the image does not include `curl`.

Deliverables: compose file, `.env.example`, run guide, evidence of each health check, architecture explanation, image tags, test report, and readiness checklist.
