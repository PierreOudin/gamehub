# GameHub

Plateforme de gestion de bibliothèque de jeux vidéo multi-plateforme.

## 🎮 Vision

Centraliser tous vos jeux (Steam, Epic Games, Ubisoft Connect, GOG) en un seul endroit, avec détection automatique des jeux installés et accès web/mobile.

## 🏗️ Architecture

- **Backend:** Go + PostgreSQL + REST API
- **Frontend:** React + TypeScript + Vite  
- **Agent:** Go natif (scan local)
- **Cloud:** Render (hébergement + BDD)

## 🚀 Quick Start

### Prérequis
- Go 1.21+
- PostgreSQL 15+
- Node.js 18+

### Installation

```bash
# Cloner le repo
git clone git@github.com:VOTRE_USERNAME/gamehub.git
cd gamehub

# Setup backend
cd backend
cp .env.example .env
# Éditer .env avec vos configurations
go mod download

# Setup frontend  
cd ../frontend
npm install

# Lancer le projet (dans 2 terminaux)
cd ../backend && go run cmd/api/main.go
cd ../frontend && npm run dev
```

## 📚 Documentation

- [Product Brief](../_bmad-output/planning-artifacts/product-brief-GameHub-2026-02-11.md)
- [Planning Semaine 1](../_bmad-output/planning-artifacts/semaine-1-planning.md)
- [Architecture Decisions](./docs/ADR/)

## 📝 License

MIT License - voir [LICENSE](./LICENSE)

## 🎯 Statut

**Phase:** MVP - Semaine 1 en cours  
**Dernière mise à jour:** 2026-02-11
