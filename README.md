# Salut, moi c'est Marc 👋

<div align="center">

### Développeur full-stack React · Node.js · TypeScript

*Des interfaces soignées, accessibles et testées, l'API et la base derrière (Node.js, NestJS, GraphQL, PostgreSQL), et de l'IA branchée sur de vraies données (MCP, Mistral).*

[**Portfolio**](https://marcchesnel.com) · [**LinkedIn**](https://www.linkedin.com/in/marc-che/) · [**Projets**](https://marcchesnel.com/#projets)

</div>

---

## ⭐ Projets phares

### Ronde : interventions terrain, même sans réseau

Un back-office Next.js pour la planification, une app React Native (Expo) pour les techniciens, une API GraphQL commune. Conçu, développé, testé et déployé de bout en bout.

<p align="center">
  <a href="https://github.com/mcpolo78/ronde">
    <img src="https://raw.githubusercontent.com/mcpolo78/ronde/main/docs/screenshots/web-planning.png" alt="Planning de la semaine du back-office Ronde" width="720">
  </a>
</p>

- 📴 **Hors ligne** : file d'opérations sur le téléphone, rejouée dans l'ordre et sans doublon au retour du réseau
- 🔁 **Mêmes règles partout** : règles métier en TypeScript pur, partagées par l'API, le web et le mobile ; GraphQL typé de bout en bout
- ♿ **Accessible et rapide** : audit WCAG 2.2 AA (axe-core) dans la CI, Lighthouse 100, alternative clavier au glisser-déposer
- 🧪 **Testé** : tests unitaires, E2E Playwright dont un scénario hors ligne complet, CI GitHub Actions avec une vraie base PostgreSQL

👉 [Démo](https://ronde-app.vercel.app) · [Code](https://github.com/mcpolo78/ronde) · [Fiches de décision d'architecture](https://github.com/mcpolo78/ronde/tree/main/docs/adr)

### Copilote portefeuille : un assistant IA branché sur des données métier par MCP

Un assistant qui interroge un portefeuille de crédits et de leasings via un serveur **MCP** écrit sans dépendance (JSON-RPC 2.0, HTTP et stdio). Six outils métier : encours, recherche de contrats, échéancier, simulation d'avenant, priorités de recouvrement. Chaque appel d'outil (arguments, résultat, durée) est affiché : aucun chiffre inventé.
`Node.js` `MCP` `Mistral AI` `JavaScript` `Vercel`

👉 [Démo](https://portefeuille-ia-demo.vercel.app) · [Code](https://github.com/mcpolo78/portefeuille-ia-demo)

### Agent de support IT : des tickets traités de bout en bout, sous contrôle humain

Un agent qui qualifie le ticket, retrouve la procédure, répond ou escalade, et attend la validation d'un technicien avant toute action sensible.
`Python` `FastAPI` `LangGraph` `MCP` `pgvector` `Azure OpenAI` `React` `GitLab CI`

- ⏸️ **Validation humaine** : le graphe **LangGraph** se met en pause sur les actions sensibles, le serveur **MCP** exige un jeton de validation à usage unique
- 🔎 **RAG hybride** : pgvector + plein texte (fusion RRF), citations vérifiées ; données personnelles masquées avant le modèle
- 🧪 **Évalué** : banc de 50 cas dans la CI GitLab (100 % de bonnes décisions), déployé sur Azure Container Apps et Static Web Apps

👉 [Démo](https://agent-support.marcchesnel.com) · [Code (GitLab)](https://gitlab.com/mcpolo/agent-support-it)

### Granulo : devis instantané de granulats livrés sur chantier

Le moteur croise sites d'extraction, rotations de camions et indexation gazole pour classer les meilleures offres. Un assistant transforme « allée de 12 × 3 m » en produit et tonnage, recalculés côté serveur.
`React` `Express` `Prisma` `PostgreSQL` `Redis` `Mistral AI`

👉 [Démo](https://devis-granulats-demo.vercel.app)

### Console IoT : supervision d'équipements en temps réel

API **NestJS** (modules, guards JWT et rôles, gateway WebSocket) et front Next.js : carte Leaflet des balises, télémétrie poussée en direct.
`NestJS` `Next.js` `Socket.IO` `Prisma` `PostgreSQL` `Docker`

👉 [Démo](https://console-iot-self.vercel.app) · [Code](https://github.com/mcpolo78/console-iot)

---

## 🛠️ Stack

**Front-end**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![React Flow](https://img.shields.io/badge/React_Flow-FF0072?style=for-the-badge&logo=react&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![three.js](https://img.shields.io/badge/three.js-000000?style=for-the-badge&logo=three.js&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)

**Tests et qualité**

![Jest](https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white)
![Testing Library](https://img.shields.io/badge/Testing_Library-E33332?style=for-the-badge&logo=testing-library&logoColor=white)
![Cypress](https://img.shields.io/badge/Cypress-17202C?style=for-the-badge&logo=cypress&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)

**IA**

![MCP](https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=anthropic&logoColor=white)
![Mistral AI](https://img.shields.io/badge/Mistral_AI-FA520F?style=for-the-badge&logo=mistralai&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)

**Back-end et déploiement**

![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

Je travaille en Scrum, avec Git (GitHub, GitLab), revue de code et Claude Code au quotidien.

---

## 🎨 Autres projets

| Projet | Description | Technologies | Liens |
|---|---|---|---|
| **Mapbrain** (freelance) | Plateforme d'apprentissage par IA : cours, carte mentale et quiz générés depuis un PDF, un audio ou une vidéo ; générateur de cartes mentales interactives | React 19, Next.js 15, TypeScript, React Flow | [Site](https://www.mapbrain.ai) |
| **VineCore** | Plateforme SaaS de suivi sanitaire du vignoble, développée en CDI dans une agritech (environ 100 utilisateurs) | React, Next.js, TypeScript | [Démo reconstituée](https://vinecore-demo.vercel.app) |
| **Le Plus Grand Quiz de France** | Recréation en PWA du jeu TF1 de 2009 (+1 million de joueurs) : défis entre amis, quiz du jour, classements | TypeScript, Supabase, Vitest | [Jouer](https://quiz-de-france.vercel.app) |
| **Maquette 3D paramétrique** | Simulateur de rénovation énergétique : on décrit une maison, on la voit en 3D, le métré et les aides se recalculent | Next.js, three.js, TypeScript | [Démo](https://argile-demo.vercel.app) · [Code](https://github.com/mcpolo78/argile-demo) |
| **DreamExplorer** | Galerie d'images créées par IA, projet de fin de formation 3W Academy (2022), refondu en 2026 | Next.js, Supabase, Vitest | [Démo](https://dream-explorer.vercel.app) |
| **Service desk IT automatisé** | Jira Service Management où une IA locale trie les tickets et répond depuis une base de connaissances | Python, Ollama | [Code](https://github.com/mcpolo78/automatisation-jira-service-desk) |
| **Support IT vocal + chatbot** | Assistant de support à l'écrit ou à la voix, qui cite sa source et propose un ticket, 100 % en local | Python, faster-whisper, Piper | [Code](https://github.com/mcpolo78/LLM-Support-IT-vocal-chatbot-) |

Détails et captures sur mon [portfolio](https://marcchesnel.com/#projets).

---

## 📫 Me contacter

Je suis ouvert aux postes de **développeur full-stack** ou **front-end React / TypeScript**.
Le plus simple : [LinkedIn](https://www.linkedin.com/in/marc-che/) ou mon [portfolio](https://marcchesnel.com).
