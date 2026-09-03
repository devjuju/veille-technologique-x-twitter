# 🐦 Fil X/Twitter — Veille technologique

## 1. Objectif

Le compte X/Twitter constitue une source complémentaire au tableau de bord Feedly.

Feedly permet principalement de centraliser les flux RSS et Atom des sources
sélectionnées, tandis que X permet de suivre directement les développeurs,
mainteneurs, organismes de sécurité et acteurs de l'intelligence artificielle.

L'objectif n'est pas de suivre un grand nombre de comptes, mais de sélectionner
des comptes pertinents en fonction du périmètre défini dans la veille
technologique.

---

## 2. Critères de sélection

Les comptes ont été sélectionnés selon plusieurs critères :

- pertinence par rapport au développement logiciel ;
- lien avec PHP et Symfony ;
- expertise en cybersécurité ;
- intérêt pour l'intelligence artificielle appliquée au développement ;
- implication dans des projets open source ;
- caractère officiel des comptes lorsque cela est possible ;
- intérêt professionnel des informations publiées.

La sélection privilégie les comptes spécialisés plutôt que les comptes
technologiques généralistes afin de limiter le bruit informationnel.

---

## 3. Organisation du fil

Le fil X est organisé autour de plusieurs thématiques.

| Thématique                    | Nombre de comptes |
| ----------------------------- | ----------------: |
| 🧩 PHP & Symfony              |                 5 |
| 🔐 Cybersécurité              |                 5 |
| 🤖 IA & développement         |                 5 |
| 🏗️ Développement & écosystème |                 3 |
| 🤖 IA complémentaire          |                 1 |
| **Total**                     |            **19** |

---

# 4. Comptes suivis

## 🧩 4.1 PHP & Symfony

| Compte         | Rôle                 | Justification                             |
| -------------- | -------------------- | ----------------------------------------- |
| @symfony       | Symfony              | Actualités et évolutions du framework     |
| @fabpot        | Fabien Potencier     | Actualités Symfony et PHP                 |
| @nicolasgrekas | Core team Symfony    | Évolutions techniques de Symfony          |
| @ThePHPF       | PHP Foundation       | Évolution du langage PHP                  |
| @seldaek       | Composer / Packagist | Écosystème PHP et gestion des dépendances |

### Pertinence

Cette catégorie constitue le cœur de la veille technique car PHP et Symfony
font partie des technologies principales suivies.

---

## 🔐 4.2 Cybersécurité

| Compte          | Rôle                 | Justification                       |
| --------------- | -------------------- | ----------------------------------- |
| @CERT_FR        | CERT-FR              | Alertes et vulnérabilités           |
| @ANSSI_FR       | ANSSI                | Recommandations de cybersécurité    |
| @owasp          | OWASP Foundation     | Sécurité des applications web       |
| @troyhunt       | Expert cybersécurité | Vulnérabilités et fuites de données |
| @TheHackersNews | Actualités sécurité  | Veille cybersécurité internationale |

### Pertinence

Cette catégorie complète les flux CERT-FR, ANSSI, OWASP et CVE présents
dans Feedly.

Elle permet notamment de détecter rapidement certaines vulnérabilités et
actualités de sécurité.

---

## 🤖 4.3 IA & développement

| Compte         | Rôle              | Justification                             |
| -------------- | ----------------- | ----------------------------------------- |
| @OpenAIDevs    | OpenAI Developers | IA et outils pour développeurs            |
| @GitHubCopilot | GitHub Copilot    | IA appliquée au développement             |
| @AnthropicAI   | Anthropic         | IA, modèles et agents                     |
| @karpathy      | Andrej Karpathy   | IA et deep learning                       |
| @simonw        | Simon Willison    | Développement et usages pratiques de l'IA |

### Pertinence

Cette catégorie permet de suivre l'évolution des outils d'intelligence
artificielle utilisés dans le développement logiciel.

Elle complète notamment la veille consacrée à GitHub Copilot et à
l'automatisation du workflow développeur.

---

## 🏗️ 4.4 Développement & écosystème

| Compte           | Rôle                  | Justification                        |
| ---------------- | --------------------- | ------------------------------------ |
| @github          | GitHub                | Développement et outils développeurs |
| @arstechnica     | Actualités techniques | Évolutions technologiques            |
| @newsycombinator | Hacker News           | Actualités et discussions techniques |

### Pertinence

Ces comptes permettent d'élargir ponctuellement la veille au-delà de PHP et
Symfony et d'identifier des tendances susceptibles d'avoir un intérêt pour
le développement logiciel.

---

## 🤖 4.5 IA complémentaire

| Compte  | Rôle          | Justification                                           |
| ------- | ------------- | ------------------------------------------------------- |
| @BFM_IA | Actualités IA | Actualités francophones sur l'intelligence artificielle |

Ce compte constitue une source complémentaire permettant de suivre
l'actualité de l'IA dans un contexte francophone.

---

# 5. Comptes volontairement écartés

Certains comptes proposés par X n'ont pas été retenus.

Il s'agit notamment des comptes principalement consacrés :

- aux smartphones ;
- au divertissement ;
- aux voyages ;
- à l'aéronautique ;
- à la culture générale ;
- à l'actualité technologique grand public.

Cette sélection permet de conserver un fil principalement orienté vers le
développement logiciel, la cybersécurité et l'intelligence artificielle.

---

# 6. Complémentarité avec Feedly

X/Twitter et Feedly n'ont pas exactement le même rôle.

| Outil                     | Rôle                                                 |
| ------------------------- | ---------------------------------------------------- |
| 📡 Feedly                 | Collecte structurée des flux RSS/Atom                |
| 🐦 X/Twitter              | Suivi des experts et acteurs de l'écosystème         |
| 📚 Documentation Markdown | Conservation et analyse des informations importantes |

Le fonctionnement global est donc :

```text
             🔭 VEILLE TECHNOLOGIQUE
                       │
             ┌─────────┴─────────┐
             │                   │
          📡 Feedly           🐦 X/Twitter
             │                   │
        Sources RSS          Experts / acteurs
             │                   │
             └─────────┬─────────┘
                       │
                       ▼
                    🔎 TRI
                       │
                       ▼
                   🧠 ANALYSE
                       │
                       ▼
                 📚 DOCUMENTATION
```
