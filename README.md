# Distributed Job Scheduler

## 🚀 Overview
A scalable distributed job scheduling system designed to handle asynchronous tasks like email processing, payment workflows, and report generation.

## 🧩 Problem Statement
Synchronous systems fail under heavy load and cannot handle retries efficiently. This project solves that using an event-driven architecture.

## 🛠 Tech Stack
- Java, Spring Boot
- Kafka
- Redis
- PostgreSQL
- Docker

## ⚙️ Features
- Async job execution
- Retry with exponential backoff
- Dead Letter Queue (DLQ)
- Distributed workers
- Job scheduling (delayed + cron)

## 🏗 Architecture
(Add diagram later)

## 📊 Scale
Designed to handle 50K+ jobs/day

## ▶️ Run Locally
docker-compose up --build
# distributed-job-scheduler
Production-grade distributed job scheduler using Spring Boot, Kafka, Redis, and PostgreSQL with retry, DLQ, and horizontal scaling support.
