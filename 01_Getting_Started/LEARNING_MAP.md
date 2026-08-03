# Learning map

| Phase | Question answered | Main artefact |
|---|---|---|
| Preparation | Can I run the toolchain? | setup evidence |
| Service Boundary | What does my service own? | boundary document |
| OpenAPI | What promise do provider and consumer share? | `openapi.yaml` |
| Testing | Does the promise hold in expected and bad cases? | Postman + Newman report |
| Docker | Does the service run consistently anywhere? | Dockerfile + image evidence |
| Compose | Can the dependencies run together? | `docker-compose.yml` |
| Integration / Plug-a-thon | Can independent teams connect safely? | handshake + demo |
| Final Demo | Can another person reproduce and understand it? | demo pack |

The hand-off is intentional: each lab consumes the verified artefacts of the previous one. Keep filenames predictable and do not discard earlier evidence.
