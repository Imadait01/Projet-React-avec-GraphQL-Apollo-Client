# 🏦 Gestion des Comptes et Transactions

<img width="1360" height="593" alt="image" src="https://github.com/user-attachments/assets/bfaef485-6642-4e31-b32c-bf6d0d08597d" />

## Description

Application React de gestion de comptes bancaires et de transactions utilisant GraphQL et Apollo Client.

## Fonctionnalités

- Création et gestion de comptes bancaires
- Effectuer des transactions (dépôts, retraits, virements)
- Consulter l'historique des transactions
- Interface responsive avec Tailwind CSS

## Technologies

- **React** 19.2.0
- **Apollo Client** 3.8.0 - Client GraphQL
- **Tailwind CSS** 3.4.0 - Styling
- **GraphQL** 16.8.1

## Installation

```bash
# Installer les dépendances
npm install

# Configurer l'URL GraphQL dans src/apollo/client.js

# Lancer l'application
npm start
```

L'application sera accessible sur **http://localhost:3000**

## Scripts

| Commande | Description |
|----------|-------------|
| `npm start` | Mode développement |
| `npm test` | Lancer les tests |
| `npm run build` | Build production |

## Structure

```
src/
├── apollo/          # Configuration GraphQL
├── components/      # Composants React
│   ├── CompteList.js
│   ├── CreateCompte.js
│   ├── TransactionForm.js
│   └── TransactionList.js
├── graphql/         # Requêtes GraphQL
└── App.js          # Composant principal
```

---

**Projet pédagogique TP-16**
