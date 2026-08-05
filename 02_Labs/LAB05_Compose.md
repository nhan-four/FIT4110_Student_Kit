# Lab 05 — Docker Compose

**Purpose:** extend a single container into a reproducible multi-service stack with networks, configuration, readiness, and end-to-end tests.

Use [FIT4110_lab05_docker_compose](https://github.com/TrangLe1912/FIT4110_lab05_docker_compose) as the authoritative guide. The target stack contains at least API, AI/worker, and database services; students complete the source `RUN_COMPOSE.md`, readiness checklist, health evidence, Newman report, and pushed image tags.

Compatibility note for the current starter: its Compose file declares an external `class-net`, so create that network first if it is absent. Then verify/fix the healthcheck commands, AI runtime dependencies and port exposure, and the TODO `test:compose` command before claiming the stack is ready. The starter is a learning baseline, not proof that every supplied command already passes unchanged.

---

## Bản tiếng Việt

# Lab 05 — Docker Compose

**Mục đích:** mở rộng một container thành stack đa service có thể tái lập, gồm network, cấu hình, readiness và kiểm thử end-to-end.

Dùng [FIT4110_lab05_docker_compose](https://github.com/TrangLe1912/FIT4110_lab05_docker_compose) làm hướng dẫn chính thức. Stack mục tiêu có ít nhất API, AI/worker và database; sinh viên hoàn thành `RUN_COMPOSE.md`, readiness checklist, minh chứng health, Newman report và image tag đã push theo repo gốc.

Lưu ý tương thích với starter hiện tại: Compose file khai báo external `class-net`, vì vậy cần tạo network này trước nếu máy chưa có. Sau đó kiểm tra/sửa healthcheck, runtime dependency và port của AI service, cùng lệnh `test:compose` đang là TODO trước khi kết luận stack đã sẵn sàng. Starter là nền tảng thực hành, không phải bằng chứng rằng mọi lệnh cung cấp sẵn đều chạy nguyên trạng.
