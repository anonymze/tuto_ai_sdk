# AI SDK - Cours UDEMY | Yann METIER

<img src="https://ibb.co/cS3z9NyD" alt="AI SDK Toolkit" />

🚀 **Maîtrisez AI SDK avec cette course UDEMY** Ce dépôt contient tous les exemples de code et exercices de notre cours pratique axé sur AI SDK v5 - l'incroyable bibliothèque TypeScript devenant le standard pour le développement d'applications IA.

Apprenez à construire des applications IA prêtes pour la production en utilisant les fonctionnalités puissantes d'AI SDK v5 et les modèles de développement modernes. Disponible sur [aihero.dev](https://aihero.dev).

## 🎯 Ce que vous allez maîtriser avec AI SDK v5

Ce cours intensif vous fera passer des bases d'AI SDK v5 aux patterns de production avancés :

- **Concepts de base d'AI SDK v5** - Comprendre la boîte à outils moderne de développement IA
- **Streaming avec AI SDK v5** - Construire des expériences IA temps réel et réactives avec `streamText`
- **Tool Calling & Function Calling** - Créer des applications IA capables d'utiliser des outils et API externes
- **Message Parts & Data** - Travailler avec des composants de message structurés et données personnalisées
- **Support multi-providers** - Basculer facilement entre OpenAI, Anthropic, Google, et plus
- **Gestion de fichiers et images** - Traiter et travailler avec du contenu multimédia
- **Patterns de mémoire avancés** - Gestion d'état sophistiquée et gestion de conversations
- **Fonctionnalités production** - Tests intégrés, monitoring et capacités de déploiement

## 🚀 Démarrage rapide

### Prérequis

- [Node.js](https://nodejs.org/en/download) (version 22 ou supérieure)
- [pnpm](https://pnpm.io/) (recommandé) ou npm/yarn/bun
- Clés API pour vos providers IA préférés :
  - [OpenAI](https://platform.openai.com/api-keys) (GPT-4, GPT-3.5)
  - [Anthropic](https://console.anthropic.com/) (Claude)
  - [Google AI Studio](https://aistudio.google.com/apikey) (Gemini)

### Installation

1. **Clonez ce dépôt :**

```bash
git clone https://github.com/ai-hero-dev/ai-sdk-v5-crash-course.git
cd ai-sdk-v5-crash-course
```

2. **Installez les dépendances :**

```bash
pnpm install
```

3. **Configurez votre environnement :**

```bash
cp .env.example .env
```

4. **Ajoutez vos clés API dans `.env`** et vous êtes prêt à apprendre !

## 📚 Structure du cours

Commencez par lancer `pnpm dev` :

```bash
pnpm dev
```

Cela vous permettra de choisir entre les différentes sections du cours.

Vous pouvez aussi lancer `pnpm exercise <numéro-exercice>` pour sauter à un exercice spécifique.

## 📁 Modules du cours AI SDK v5

```
exercises/
├── 01-basics/                    # Fondamentaux AI SDK v5
│   ├── 01.1-what-is-the-ai-sdk/
│   ├── 01.2-choosing-a-model/
│   ├── 01.3-stream-text-to-terminal/
│   ├── 01.4-ui-message-streams/
│   ├── 01.5-stream-text-to-ui/
│   └── 01.6-system-prompts/
├── 02-agents/                    # Tool calling & agents
├── 03-advanced/                  # Patterns avancés
└── 99-reference/                 # Matériel de référence
```

## 🛠️ Méthodologie d'apprentissage

Chaque exercice suit cette structure d'apprentissage :

### Dossier `problem/`

- **Votre terrain de jeu** - Commencez ici !
- Contient `readme.md` avec instructions détaillées
- Fichiers de code avec commentaires `TODO` à implémenter

### Dossier `solution/`

- **Implémentation de référence** - Consultez quand vous êtes bloqué
- Code complet et fonctionnel pour chaque exercice
- Idéal pour comparer les approches et apprendre les bonnes pratiques

### Dossier `explainer/`

- **Approfondissements** - Explications et concepts additionnels
- Guides détaillés des sujets complexes
- Parfait pour renforcer votre compréhension

## 🤝 Obtenir de l'aide

1. **Consultez la solution** - Chaque exercice a une version complétée
2. **Vérifiez votre configuration** - Assurez-vous que les clés API et dépendances sont correctes
3. **Regardez le cours** - Explications complètes disponibles sur [aihero.dev](https://aihero.dev)

Prêt à maîtriser AI SDK v5 et devenir expert en développement IA ? Commençons à construire le futur ! 🚀
