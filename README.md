# Factory Reliability Simulator

A simulation project that models **factory system reliability** using streaming data and distributed components.  
Inspired by industrial environments like **Tesla Gigafactories**, this project explores resilience at scale.

## 🚀 Overview
- Event-driven simulation of factory sensors and production lines.
- Uses message queues for fault injection and real-time events.
- Demonstrates strategies for **observability, incident response, and resilience testing**.

## 🛠️ Tech Stack
- Go (simulation backend)
- Apache Kafka / GCP Pub/Sub
- Cassandra (or PostgreSQL for local testing)
- Docker + Kubernetes (optional)

## ✨ Features
- Generate synthetic sensor events.
- Replay failure scenarios.
- Visualize event flows with dashboards (Grafana/Prometheus).

## 📈 Roadmap
- [ ] Build baseline sensor simulation.
- [ ] Add fault injection and anomaly detection.
- [ ] Deploy with Pub/Sub on GCP free tier.

## 📂 Status
🚧 Planned – Initial design in progress.

## 📊 Architecture
![Architecture Diagram](./docs/architecture.png)

## 📄 License
This project is licensed under the [MIT License](LICENSE).
