# Infrastructure

This repository contains **Kubernetes infrastructure configuration** for the Shop system.
It is responsible for deploying **shared platform services**, **datastores**, **observability stack**, and **application services** using **Helm**.

## Tooling

* **Kubernetes**
* **Helm**
* **Helmfile** (recommended for orchestration)
* **Minikube** (local development)

---

## Helm Repositories

The following Helm repositories are used:

* **Bitnami**

  * Kafka
  * PostgreSQL
* **Prometheus Community**

  * Prometheus
* **Grafana**

  * Grafana
  * Loki
  * Alloy

Each service has its **own isolated database instance**.