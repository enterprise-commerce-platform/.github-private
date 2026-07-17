## Welcome to the team 🙌

# Enterprise Commerce Platform

A production-grade enterprise e-commerce platform built using modern cloud-native technologies.

## Technology Stack

- Java 21
- Spring Boot 3
- Spring Cloud
- OAuth2
- JWT
- Kafka
- Redis
- PostgreSQL
- Docker
- Kubernetes
- Helm
- Terraform
- GitHub Actions
- Prometheus
- Grafana
- ELK

## Architecture

Microservices Architecture

- API Gateway
- Auth Service
- User Service
- Product Service
- Inventory Service
- Order Service
- Payment Service
- Notification Service

**Business Flow:**

Customer
    │
    ▼
API Gateway
    │
    ▼
Authentication
    │
    ▼
Product Service
    │
    ▼
Order Service
    │
    ▼
Inventory Service
    │
    ▼
Payment Service
    │
    ▼
Kafka
    │
    ├────────► Notification Service
    │
    └────────► Analytics Service
