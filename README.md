# Manifestes Kubernetes & Observabilité (Applying-manifests)

Ce dépôt contient l'ensemble des manifestes déclaratifs utilisés par ArgoCD pour déployer l'application et la stack de monitoring sur le cluster AKS.

## 📁 Structure du dépôt

- `manifests/` : Déploiement de l'application Python et de l'Ingress NGINX.
- `observability/` : Configuration de Loki et Grafana pour la collecte des logs et le suivi des métriques.
- `application.yaml` : Manifeste de déploiement d'ArgoCD.
