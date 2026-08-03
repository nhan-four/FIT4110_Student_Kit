# Lab 03 — Postman, mocks, and contract tests

Use [FIT4110_lab03_postman_mock_testing](https://github.com/TrangLe1912/FIT4110_lab03_postman_mock_testing). Turn the contract into executable requests and run the same collection against `mock` and `local` environments.

Required evidence: exported collection and environments (without secrets), test-case matrix, consumer/provider handshake, Newman report, and completed reliability checklist. Cover health, happy path, authentication, invalid payloads, boundary cases, and a consumer-side mock smoke test where applicable.

Keep URLs and tokens in environment variables; never hard-code or commit a real secret. Run `npm install`, start Prism as directed, then run Newman. CI is useful feedback, but the graded artefact is the reproducible repository ZIP.
