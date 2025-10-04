# 🚀 System Design Learning Resources

This repository contains free resources to learn **System Design concepts**, understand **real-world architectural patterns**, and prepare for interviews.  
✅ **Start here if you are new:** System Design can feel HARD until you understand these fundamental concepts.

---

## 📚 System Design Key Concepts (Foundations)

- ⚡ [Scalability](https://medium.com/@s.g.manikandan)
  - Vertical vs Horizontal scaling
  - Stateless vs Stateful services (intro only, detailed trade-offs later)
- ⏱️ [Performance Metrics](https://medium.com/@s.g.manikandan) → Latency, Throughput, SLA/SLO/SLI, Tail latency (p99, p999)
- 🏛️ [CAP Theorem](https://medium.com/@s.g.manikandan) → Consistency, Availability, Partition Tolerance
- ⚖️ [PACELC Theorem](https://medium.com/@s.g.manikandan) → If Partition happens → CAP trade-offs, Else → Latency vs Consistency
- 🛠️ [Microservices Guidelines](https://medium.com/@s.g.manikandan) → Design best practices for modular, scalable services
- 🛡️ [Resilience & Reliability](https://medium.com/@s.g.manikandan) → SPOF, Fault Tolerance, Disaster Recovery
- 🔄 [Consistency Models](https://medium.com/@s.g.manikandan) → Strong, Eventual, Causal, Read-your-write
- 💾 [Database Fundamentals](https://medium.com/@s.g.manikandan) → Indexes, Query Optimization, Partition, ACID vs BASE
- 🧰 [Caching](https://medium.com/@s.g.manikandan) → Client-side, CDN, Reverse Proxy, Application-level (Redis, Memcached)
- 📦 [Replication](https://medium.com/@s.g.manikandan) → Master-Slave, Leader-Follower, Multi-Leader, Quorum-based
- 🗂️ [Data Partitioning (Sharding)](https://medium.com/@s.g.manikandan) → Hash-based, Range-based, Geo-partitioning, Directory-based
- ⚖️ [Load Balancing](https://medium.com/@s.g.manikandan) → DNS, L4 (network), L7 (application), Anycast routing
- 📬 [Messaging & Event Delivery](https://medium.com/@s.g.manikandan) → Queues, Pub/Sub, Streaming
- 🚦 [Backpressure & Flow Control](https://medium.com/@s.g.manikandan) → Handling overload
- 🔁 [Idempotency](https://medium.com/@s.g.manikandan) → Safe retries
- 🔄 [Failover Strategies](https://medium.com/@s.g.manikandan) → Auto vs manual failover
- 🚫 [Rate Limiting & Throttling](https://medium.com/@s.g.manikandan) → Token Bucket, Leaky Bucket, Fixed Window, Sliding Window
- 👀 [Monitoring & Observability Basics](https://medium.com/@s.g.manikandan) → Metrics, Logging, Tracing

---

## 🛠️ System Design Building Blocks (The Toolbox)

- 🌐 [Networking](https://medium.com/@s.g.manikandan) → DNS, CDN, Proxy & Reverse Proxies (Nginx, Envoy, HAProxy)
- 🏗️ [Application Layer](https://medium.com/@s.g.manikandan) → Web servers, Stateless services, Session stores (Redis, DynamoDB session tables)
- 💽 [Databases](https://medium.com/@s.g.manikandan)
  - Relational (MySQL, Postgres)
  - NoSQL (Key-value: DynamoDB, Wide-column: Cassandra, Document: MongoDB)
  - Time-series (InfluxDB, TimescaleDB)
  - Graph (Neo4j, JanusGraph)
- 🗄️ [Storage Systems](https://medium.com/@s.g.manikandan) → Object storage (S3, MinIO), Distributed File Systems (HDFS, Ceph), Block storage, Checksum
- 🔧 [Distributed Coordination](https://medium.com/@s.g.manikandan) → Consensus (Raft, Paxos), Service discovery (ZooKeeper), Gossip Protocols, Heartbeat, Distributed Locking
- 🛡️ [Resilience / Reliability Mechanisms](https://medium.com/@s.g.manikandan) → Circuit Breaker, Retry, Timeout, Bulkhead, Fallback
- 🧰 [Distributed Caching Systems](https://medium.com/@s.g.manikandan) → Redis, Memcached, CDN edge caches
- 📬 [Messaging Systems](https://medium.com/@s.g.manikandan) → Kafka (streaming), RabbitMQ (queue) & Aeron
- 🔍 [Search & Indexing Systems](https://medium.com/@s.g.manikandan) → Elasticsearch, Solr, OpenSearch
- 🌐 [APIs & Communication](https://medium.com/@s.g.manikandan) → REST, GraphQL, gRPC, WebSockets, WebRTC
- 👁️ [Observability](https://medium.com/@s.g.manikandan) → Monitoring (Prometheus, Grafana), Logging (ELK, Loki), Tracing (Jaeger, OpenTelemetry)
- 🚢 [Deployment & Infrastructure](https://medium.com/@s.g.manikandan) → Docker, Kubernetes, Service Mesh (Istio, Linkerd), Autoscaling

---

## 🎨 System Design Tradeoffs (The Art of Design)

- 🔄 [Stateless vs Stateful services](https://medium.com/@s.g.manikandan) (detailed pros/cons, scaling complexity)
- ⚡ [Concurrency vs Parallelism](https://medium.com/@s.g.manikandan) → Task interleaving vs simultaneous execution
- 🗄️ [SQL vs NoSQL](https://medium.com/@s.g.manikandan) → Transactions vs flexibility, joins vs scale
- 🏛️ [Monolith vs Microservices](https://medium.com/@s.g.manikandan) → Simplicity vs scalability & team independence
- 🌐 [REST vs GraphQL vs gRPC](https://medium.com/@s.g.manikandan) → Maturity vs flexibility vs performance
- ⚖️ [Consistency vs Availability vs Latency vs Throughput](https://medium.com/@s.g.manikandan) → CAP + PACELC
- 🧰 [Read-Through vs Write-Through Cache](https://medium.com/@s.g.manikandan) → Caching strategy choice
- ⏱️ [Synchronous vs Asynchronous Communication](https://medium.com/@s.g.manikandan) → Blocking vs non-blocking interactions
- 🔄 [Push vs Pull Models](https://medium.com/@s.g.manikandan) → Real-time vs efficiency
- 🏞️ [Batch Processing vs Stream Processing](https://medium.com/@s.g.manikandan) → Latency vs throughput
- ☁️ [On-Prem vs Cloud vs Hybrid](https://medium.com/@s.g.manikandan) → Control vs scalability vs cost
- ⚡ [Vertical vs Horizontal scaling](https://medium.com/@s.g.manikandan) → Simplicity vs elasticity
- 🗂️ [Stateful Storage Systems](https://medium.com/@s.g.manikandan) → Sharding vs Replication vs Multi-region
- ❄️ [Hot vs Cold Data Storage](https://medium.com/@s.g.manikandan) → Performance vs cost
- 🔄 [Strong Consistency vs Eventual Consistency](https://medium.com/@s.g.manikandan) → User experience vs availability

---

## 🏗️ System Design Architectural Patterns (Blueprints)

- 🏛️ [Classic Patterns](https://medium.com/@s.g.manikandan)
  - Client-Server
  - Layered / N-tier Architecture
  - Microservices
  - SOA (Service-Oriented Architecture)
- 🔄 [Distributed/Event-Driven Patterns](https://medium.com/@s.g.manikandan)
  - Event-Driven Architecture
  - CQRS (Command Query Responsibility Segregation)
  - Event Sourcing
  - Data Mesh
  - Peer-to-Peer Systems
- ☁️ [Cloud-Native Patterns](https://medium.com/@s.g.manikandan)
  - Serverless / FaaS
  - Hexagonal Architecture (Ports & Adapters)
  - Domain-Driven Design (DDD building blocks)
- 🛡️ [Resilience & Reliability Patterns](https://medium.com/@s.g.manikandan)
  - Saga Pattern (distributed transactions)
  - Circuit Breaker, Retry, Timeout
  - Bulkhead, Fallback patterns

---

## 🎯 System Design Interview Problems (Hands-On)

### Easy
- [URL Shortener (TinyURL)](https://medium.com/@s.g.manikandan)
- [Pastebin / Code Sharing](https://medium.com/@s.g.manikandan)
- [Notification Service (Email/SMS)](https://medium.com/@s.g.manikandan)
- [API Rate Limiter](https://medium.com/@s.g.manikandan)
- [Vending Machine](https://medium.com/@s.g.manikandan)
- [Distributed Key-Value Store](https://medium.com/@s.g.manikandan)
- [Parking Garage](https://medium.com/@s.g.manikandan)
- [Distributed Cache](https://medium.com/@s.g.manikandan)
- [Online Polling/Voting System](https://medium.com/@s.g.manikandan)
- [Unified Payments Interface (UPI)](https://medium.com/@s.g.manikandan)
- [Content Delivery Network (CDN)](https://medium.com/@s.g.manikandan)
- [Authentication System](https://medium.com/@s.g.manikandan)

### Medium
- [Twitter Feed / News Feed](https://medium.com/@s.g.manikandan)
- [Instagram / Photo Sharing](https://medium.com/@s.g.manikandan)
- [WhatsApp / Messenger (Chat)](https://medium.com/@s.g.manikandan)
- [YouTube / Video Streaming](https://medium.com/@s.g.manikandan)
- [Search Autocomplete](https://medium.com/@s.g.manikandan)
- [Payment Gateway](https://medium.com/@s.g.manikandan)
- [Job Scheduler (like cron at scale)](https://medium.com/@s.g.manikandan)
- [E-commerce Store like Amazon](https://medium.com/@s.g.manikandan)
- [Distributed Message Queue like Kafka](https://medium.com/@s.g.manikandan)
- [Flight Booking System](https://medium.com/@s.g.manikandan)

### Hard
- [Uber / Lyft (Ride Sharing)](https://medium.com/@s.g.manikandan)
- [Netflix (Video on Demand)](https://medium.com/@s.g.manikandan)
- [Amazon (E-commerce)](https://medium.com/@s.g.manikandan)
- [Stock Trading System / Exchange](https://medium.com/@s.g.manikandan)
- [Google Drive / Dropbox (File Storage & Sync)](https://medium.com/@s.g.manikandan)
- [Google Maps (Navigation + Geo)](https://medium.com/@s.g.manikandan)
- [Distributed Web Crawler](https://medium.com/@s.g.manikandan)
- [Zoom (Video Conferencing)](https://medium.com/@s.g.manikandan)
- [Multi-tenant SaaS Platform](https://medium.com/@s.g.manikandan)
- [Ticket Booking System like BookMyShow](https://medium.com/@s.g.manikandan)

---

**🔗 All links currently point to [My Medium](https://medium.com/@s.g.manikandan) and can be updated later.**
