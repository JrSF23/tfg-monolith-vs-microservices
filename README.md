# PFE — Comparaison Monolithe vs Microservices (E-commerce)

## Objectif
Implémenter deux versions d’une application e-commerce (Monolithe et Microservices) et comparer leurs performances via des tests de charge (latence p95, débit, CPU/RAM, taux d’erreurs).

## Stack
- Frontend : React
- Backend : Laravel
- Bases de données : MySQL (utilisateurs) + MongoDB (commandes en microservices)
- Conteneurisation : Docker / Docker Compose
- Tests de charge : Apache JMeter
- Monitoring : Prometheus + Grafana (optionnel)

## Structure du dépôt
- /docs : UML, KPI, méthodologie, documentation
- /monolithe : application monolithique
- /microservices : passerelle API + services
- /tests : scripts JMeter + résultats
- /infra : docker-compose et configuration (si nécessaire)

## Endpoints mesurés (KPI)
- GET /me
- POST /orders

## Protocole de tests
Charges : 10 / 100 / 1000 utilisateurs — Durée : 3 min — Répétitions : 3