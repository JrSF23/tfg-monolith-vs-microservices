\# Stack technique et versions (environnement Windows)



\## Outils et technologies

\- Frontend : React (Node.js v22.12.0)

\- Backend : Laravel (PHP 8.2.12)

\- Base de données : MySQL 8.0.x (utilisateurs et monolithe)

\- Base de données : MongoDB 6.0+ (service des commandes en microservices)

\- Conteneurisation : Docker Desktop + Docker Compose (v2)

\- Tests de charge : Apache JMeter (5.6+)

\- Monitoring : Prometheus + Grafana (optionnel)

\- Logs : logs Laravel (+ Telescope optionnel)



\## Justification (résumé)

Le stack a été choisi pour construire une application e-commerce réaliste et comparer de manière quantitative une architecture monolithique et une architecture microservices. Docker/Compose assure la reproductibilité et JMeter permet de mesurer p95, req/s et taux d’erreurs.

