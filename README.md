# ML Platform on Kubernetes

A production-style ML platform demonstrating:

- Scalable model serving on Kubernetes  
- Autoscaling with HPA  
- GitOps-based deployment using ArgoCD  
- Observability with Prometheus & Grafana  

---

## Architecture

User → ML API → Kubernetes → HPA → Prometheus → Grafana → ArgoCD

---

## System Behavior

Traffic ↑ → CPU ↑ → Pods ↑ → CPU per pod ↓ → System stabilizes  

---

## GitOps

Git push → ArgoCD → Auto deploy to cluster  

---

## What this shows

- Real-world autoscaling behavior  
- End-to-end observability  
- Production-style deployment patterns  

---

## About

Building scalable ML platforms | Kubernetes | MLOps | Cloud-native
