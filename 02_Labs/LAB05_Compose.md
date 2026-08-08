# Lab 05 — Docker Compose

**Purpose:** turn a containerised service into a reproducible stack with the dependencies that its service boundary actually needs.

Use [FIT4110_lab05_docker_compose](https://github.com/TrangLe1912/FIT4110_lab05_docker_compose) as the authoritative technical starter. Treat it as a skeleton to analyse and complete, not as a finished integrated system. Your stack must contain the API and the appropriate dependency or dependencies for your boundary, such as a database, message broker, AI/worker service, or another service; AI and PostgreSQL are not mandatory for every team.

Three containers running and healthy do not prove end-to-end integration. Demonstrate that the API actually communicates with the relevant dependency and preserve local health, test, and Newman evidence. In the current starter, review/fix the external `class-net`, healthcheck commands, AI runtime dependencies and port exposure, the in-memory API data flow, and the TODO `test:compose` command before claiming readiness.

---

## Bản tiếng Việt

# Lab 05 — Docker Compose

**Mục đích:** chuyển service đã được container hóa thành một stack tái lập được với các dependency thực sự cần cho service boundary.

Dùng [FIT4110_lab05_docker_compose](https://github.com/TrangLe1912/FIT4110_lab05_docker_compose) làm technical starter chính thức. Hãy xem starter này là skeleton để phân tích và hoàn thiện, không phải hệ thống tích hợp hoàn chỉnh. Stack phải có API và dependency/dependencies phù hợp với boundary, ví dụ database, message broker, AI/worker service hoặc service khác; AI và PostgreSQL không bắt buộc cho mọi nhóm.

Ba container cùng chạy và healthy không chứng minh tích hợp end-to-end. Hãy chứng minh API thực sự giao tiếp với dependency liên quan và lưu minh chứng health, test và Newman chạy tại local. Với starter hiện tại, cần kiểm tra/sửa external `class-net`, lệnh healthcheck, runtime dependency và port của AI, luồng dữ liệu API đang lưu trong bộ nhớ, cùng lệnh `test:compose` còn là TODO trước khi kết luận readiness.
