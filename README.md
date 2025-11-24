# Plateforme Low-Code Chatbot (PFA)

Une plateforme permettant de créer des chatbots conversationnels intelligents et multilingues via une interface visuelle.

## 🏗 Architecture DevOps

Ce projet utilise une architecture micro-services conteneurisée :
- **Frontend :** React + Vite (Nginx en prod)
- **Backend :** Python FastAPI
- **Database :** MongoDB
- **Infrastructure :** Docker & Docker Compose

## 🚀 Démarrage Rapide

### Prérequis
- Docker et Docker Compose installés sur la machine.

### Installation et Lancement
Pas besoin d'installer Python ou Node.js localement. Tout est géré par Docker.

```bash
# 1. Cloner le projet
git clone <votre-repo-url>
cd chatbot-platform

# 2. Lancer l'environnement complet
docker-compose up --build
