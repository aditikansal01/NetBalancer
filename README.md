# NetBalancer – Layer 4 Traffic Load Balancer

NetBalancer is a distributed systems project that implements a **Layer-4 load balancing architecture** for routing TCP traffic across multiple backend servers. The system focuses on **high availability, scalability, and fault tolerance** using dynamic server selection strategies and health monitoring.

---

## 🚀 Key Features

* Layer-4 TCP traffic routing across multiple backend servers
* Round Robin load balancing algorithm
* Backend server pool management
* Health check system for server availability
* Dockerized multi-service deployment
* Modular architecture for extensibility

---

## 🧠 System Architecture

Client requests are routed through the Load Balancer, which dynamically selects an available backend server from the pool based on the configured scheduling strategy. Health checks ensure that only active servers receive traffic.

```
Client → Load Balancer → Server Pool → Backend Server → Response
```

---

## 🛠️ Tech Stack

* Go
* TCP/IP Networking
* Docker & Docker Compose
* Distributed Systems Concepts
* Load Balancing Algorithms

---

## 📊 Load Balancing Strategy

Currently implemented:

* Round Robin scheduling

Planned enhancements:

* Least Connections algorithm
* Weighted load balancing
* Dynamic health-based routing

---

## 🔍 Future Improvements

* Request logging and observability dashboard
* Metrics endpoint for traffic monitoring
* Retry and failover mechanisms
* Latency-based routing optimization
* Kubernetes deployment support

---

## 📌 Purpose

This project was built to strengthen understanding of:

* Computer Networks (TCP/IP)
* Distributed system design
* Concurrency and server-side architecture
* Real-world traffic routing mechanisms used in scalable systems

---

## 📁 Project Structure

* `main.go` – Entry point for load balancer
* `serverpool/` – Backend server management
* `health/` – Health check implementation
* `http-server/` – Backend service simulation
* `docker-compose.yml` – Multi-service orchestration

---

## ⚠️ Note

This project is actively being extended to include advanced load balancing strategies and system observability features.
