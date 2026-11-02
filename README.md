# Journal de bord (Frontend)

Interface web d'un journal de bord, développée avec **Vue 3** et **Vite**.
Elle communique avec une API backend pour gérer les entrées du journal.

> d'humeur ou de tâches, avec visualisation des statistiques

## Fonctionnalités

- Navigation entre plusieurs pages avec Vue Router
- Communication avec l'API via Axios
- Graphiques de suivi avec Chart.js
- connexion, ajout / modification / suppression d'entrées, etc.

## Technologies

| Outil | Rôle |
|-------|------|
| Vue 3 | Framework JavaScript |
| Vite | Outil de build et serveur de développement |
| Vue Router | Navigation entre les pages |
| Axios | Requêtes HTTP vers l'API |
| Chart.js | Graphiques |
| Font Awesome | Icônes |

## Prérequis

- [Node.js](https://nodejs.org/) (version 18 ou plus récente)

## Installation

```bash
git clone https://github.com/rboulkriat/journal-de-bord-frontend.git
cd journal-de-bord-frontend
npm install
```

## Configuration

Créez un fichier `.env` à la racine :

## Lancer le projet

```bash
npm run dev
```

L'application est accessible sur http://localhost:5173.

## Compiler pour la production

```bash
npm run build
npm run preview
```

## Structure du projet

```
├── public/        # Fichiers statiques
├── src/           # Code source (composants, pages, routes)
├── index.html     # Point d'entrée
├── vite.config.js # Configuration de Vite
└── package.json
```

## Auteur

**Rabab Boulkriat** 
GitHub : [@rboulkriat](https://github.com/rboulkriat)
