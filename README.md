<div align="center">

# Hi, I'm Bekzat Tursun 👋

### Go Backend Engineer

I build backend services and APIs with Go, PostgreSQL, Redis, and gRPC.
My projects focus on concurrency, testing, observability, and production
reliability.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/tursunbekzat)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tursunbekzat07@gmail.com)

</div>

---

## About

- Build REST and gRPC services primarily with **Go**
- Work with **PostgreSQL, Redis, Kafka, Protocol Buffers, and Docker**
- Develop concurrent processing with **worker pools and asynchronous jobs**
- Write table-driven unit and HTTP tests with **race detection**
- Support distributed production systems using **Kubernetes, Linux, logs, and metrics**
- Based in **Astana, Kazakhstan**

---

## Core Stack

<div align="center">

### Backend

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-005571?style=flat-square)
![gRPC](https://img.shields.io/badge/gRPC-244C5A?style=flat-square)
![Protocol Buffers](https://img.shields.io/badge/Protocol_Buffers-4285F4?style=flat-square)
![Concurrency](https://img.shields.io/badge/Concurrency-00ADD8?style=flat-square)
![Worker Pools](https://img.shields.io/badge/Worker_Pools-005571?style=flat-square)

### Data & Messaging

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)

### Infrastructure & Observability

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

### Testing & Quality

![Go Testing](https://img.shields.io/badge/Go_Testing-00ADD8?style=flat-square&logo=go&logoColor=white)
![Table Driven Tests](https://img.shields.io/badge/Table--Driven_Tests-005571?style=flat-square)
![httptest](https://img.shields.io/badge/httptest-00ADD8?style=flat-square)
![Race Detector](https://img.shields.io/badge/Race_Detector-CB3837?style=flat-square)

</div>

---

## Featured Projects

### [Scam Checker API](https://github.com/cobrich/scam-checker-api)

Concurrent threat-intelligence API for phishing and malicious URL detection.

- Analyzes URLs using DNS, TLS, WHOIS, HTTP, whitelist, and phishing heuristics
- Stores threat intelligence in PostgreSQL and caches repeated lookups in Redis
- Uses table-driven unit and HTTP tests for URL normalization, risk scoring, and API validation
- Runs tests with Go's race detector and without external network or database dependencies

[![Source Code](https://img.shields.io/badge/Source_Code-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/cobrich/scam-checker-api)

`Go` `Fiber` `PostgreSQL` `Redis` `httptest`

---

### [Netcfg Backup](https://github.com/cobrich/netcfg-backup)

Network configuration backup system with a Web UI, CLI, and authenticated gRPC API.

- Collects network-device configurations over SSH and Telnet
- Uses a worker pool and thread-safe asynchronous job management
- Defines versioned Protocol Buffers contracts for device and backup operations
- Stores backup history in SQLite with secure filesystem handling
- Exposes Prometheus metrics and Grafana monitoring
- Includes automated tests, race detection, static analysis, and Docker Compose deployment

[![Source Code](https://img.shields.io/badge/Source_Code-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/cobrich/netcfg-backup)

`Go` `gRPC` `Protocol Buffers` `SQLite` `SSH` `Prometheus` `Docker`

---

### [Order Service](https://github.com/cobrich/order-service)

Event-driven order processing system built with Kafka producer and consumer services.

- Implements asynchronous order processing with Apache Kafka
- Persists order data in PostgreSQL
- Exposes service metrics through Prometheus
- Containerized for reproducible local deployment

[![Source Code](https://img.shields.io/badge/Source_Code-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/cobrich/order-service)

`Go` `Kafka` `PostgreSQL` `Prometheus`

---

### [AI Ustaz](https://github.com/cobrich/ai-tutor-bot)

Educational backend supporting text, image, and voice interactions.

- Integrates Gemini and OpenAI APIs
- Stores conversation history in PostgreSQL
- Provides analytics, user feedback, and health monitoring
- Supports Docker-based deployment

[![Live Demo](https://img.shields.io/badge/Telegram_Bot-26A5E4?style=flat-square&logo=telegram&logoColor=white)](https://t.me/youraiustazbot)
[![Source Code](https://img.shields.io/badge/Source_Code-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/cobrich/ai-tutor-bot)

`Go` `PostgreSQL` `Gemini` `OpenAI` `Docker`

---

<div align="center">

### Let's connect

[LinkedIn](https://linkedin.com/in/tursunbekzat) ·
[GitHub](https://github.com/cobrich) ·
[Email](mailto:tursunbekzat07@gmail.com)

</div>
