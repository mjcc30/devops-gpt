# Exercice 2 : Git et Docker

## 1. Méthodologie et Git

### A. User Story

En tant qu'utilisateur de DevOpsGPT, je veux pouvoir accéder à un abonnement premium afin d'avoir un accès en priorité à l'IA de l'application avec plus de tokens journaliers.

### B. Commandes Git

```bash
git checkout -b feature-premium-subscription

# Si nouveaux fichiers, git add .
git commit -m "nouvelle feature : feature-premium-subscription"
git checkout main
git merge feature-premium-subscription
git tag -a v1.0.0 -m "ma version 1.0.0"
git push origin v1.0.0
```