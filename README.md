# 🎯 Portfolio — Aaron Zerrouk

Bienvenue dans le dépôt GitHub de mon portfolio ! Ce document explique la structure et l'organisation de mon site portfolio.

---

## 📂 Structure du projet

### Vue d'ensemble
```
/
├── index.html          # Page principale du portfolio
├── index.css           # Styling global
├── index.js            # Comportements interactifs
├── _config.yml         # Configuration Jekyll
├── README.md           # Ce fichier
├── img/                # Images et ressources visuelles
├── cards/              # Images des projets 
├── oil/                # Ressources pour le projet e-commerce
├── E5/                 # Documents officiels de l'épreuve E5
└── modules/            # Modules RGPD du Certificat CNIL
```

---

## 🏗️ Sections du portfolio

Le portfolio est organisé en **10 sections principales** accessibles via la navigation :

### 1️⃣ **Section Héros (Home)**
- **ID** : `#home`
- **But** : Présentation immédiate avec accroche professionnelle
- **Éléments** :
  - Fond animé avec orbes dégradés
  - Introduction personnelle (BTS SIO 2 SLAM, Développeur Web)
  - Boutons d'appel à l'action (CTA) : Voir mes projets, GitHub, Contact
  - Animations fluides au scroll
  - Indicateur de scroll vers le bas

### 2️⃣ **Section À propos**
- **ID** : `#about`
- **But** : Se présenter et montrer les qualités clés
- **Éléments** :
  - Description personnelle avec parcours BTS SIO
  - 3 cartes de traits personnels :
    - 🧘 **Calme** : Résilience face aux défis techniques
    - ⚡ **Adaptable** : Capacité à s'intégrer dans tout environnement
    - 🎯 **Autonome** : Proactif et orienté résultats
  - Mise en page responsive avec flexbox

### 3️⃣ **Section Projets**
- **ID** : `#projets`
- **But** : Montrer les réalisations sous forme de portfolio interactif
- **Éléments** :
  - **7 cartes de projets** interactives et cliquables :
    - **01** : Site J-Pop YOASOBI (HTML · CSS · JS)
    - **02** : Gestion de parc informatique (GLPI · Réseau)
    - **03** : Site E-Commerce — Huiles (React · Tailwind · Node.js)
    - **04** : Configurateur Plexiglass (Vue.js · WebGL · Canvas)
    - **05** : BiblioTech — Library Management (Laravel · PHP · SQLite)
    - **06** : BoutikPro — Commerce Management (Python · MySQL · SQLAlchemy)
    - **07** : Refonte site CoinMobile (PHP · MySQL · Bootstrap)
  - Chaque carte contient :
    - Image/screenshot du projet
    - Tags technologiques
    - Titre et description court
    - Lien vers modale détaillée
  - Grid responsive avec effets hover

### 4️⃣ **Section Éducation**
- **ID** : `#education`
- **But** : Présenter le parcours académique de manière chronologique
- **Éléments** :
  - Timeline verticale avec 3 étapes :
    - **2024 — 2026** : BTS SIO SLAM (Lycée Simone Weil)
      - Formation en Services Informatiques aux Organisations
      - Spécialité Solutions Logicielles et Applications Métier
      - Tags : HTML/CSS/JS, PHP/Laravel, React, Base de données
    - **2023 — 2024** : L0 Musicologie (Université Jean Monnet)
      - Année préparatoire de musicologie
      - Découverte des bases de l'histoire musicale et théorie
      - Tags : Histoire musicale, Éducation auditive, Théorie musicale, Solfège
    - **2022 — 2023** : Baccalauréat STI2D (Lycée Jacob Holtzer)
      - Sciences et Technologies de l'Industrie et du Développement Durable
      - Mention Assez Bien
      - Tags : Mention Assez Bien, Technologies numériques, Innovation, Eco-conception
  - Design avec points (dots) reliés et animations hover
  - Descriptions détaillées pour chaque formation

### 5️⃣ **Section Expérience Professionnelle**
- **ID** : `#experience`
- **But** : Afficher l'expérience professionnelle acquise via les stages
- **Éléments** :
  - Timeline verticale avec 2 stages :
    - **Juin 2025** : Stage Développeur Web chez CTRLZ SAS
      - Focus : Création d'un site configurateur interactif
      - Missions principales :
        - Création et optimisation de fiches produits WordPress
        - Optimisation et gestion de la BDD PHP MySQL
        - Mise en place d'une solution de configurateur Vue.js
        - Gestion du back office WordPress ecommerce
      - Tags : Vue.js, WebGL, Canvas, UI/UX Design, Frontend moderne
      - Lien vers le projet : Configurateur Plexiglass
    - **Janvier 2026** : Stage Développeur Full-Stack chez CoinMobile
      - Focus : Cycle complet de développement web
      - Missions principales :
        - Développer/enrichir une base de données
        - Intégration des données dans le backend
        - Déploiement site vitrine en production
        - Utilisation des outils d'interface utilisateur
      - Tags : Base de données, Backend, Déploiement, Frontend, Full-Stack
  - Design cohérent avec la timeline d'éducation
  - Missions présentées avec puces et flèches

### 6️⃣ **Section Compétences**
- **ID** : `#skills`
- **But** : Afficher le stack technique avec indicateurs visuels
- **Éléments** :
  - **3 catégories de compétences** :
    - **Langages** : HTML, CSS, JavaScript, TypeScript, PHP, MySQL, Python
    - **Frameworks** : React, Next.js, Vue.js, Laravel, Tailwind CSS, Faker
    - **Outils** : Git, VS Code, Figma, Docker, LLM API, Vercel, PostgreSQL, Supabase
  - Barres de progression pour chaque compétence
  - Pourcentage de maîtrise visuel

### 7️⃣ **Section Langues**
- **ID** : `#langues`
- **But** : Montrer la maîtrise des langues étrangères
- **Éléments** :
  - Cartes pour chaque langue parlée
  - Niveaux de maîtrise (Natif, C1, A2, etc.)
  - Description contextuelle du niveau

### 8️⃣ **Section Épreuve E5**
- **ID** : `#e5`
- **But** : Mettre à disposition les documents officiels de l'épreuve E5
- **Éléments** :
  - Section officielle pour les documents BTS SIO
  - **3 documents téléchargeables** :
    - 📄 Attestation de stage BTS1 (PDF)
    - 📄 Attestation de stage BTS2 (PDF)
    - 📊 Tableau de synthèse E5 2026 (XLSX)
  - Chaque document contient :
    - Icône du type de document
    - Titre du document
    - Description courte
    - Badge de format (PDF, XLSX)
  - Lien de téléchargement direct

### 9️⃣ **Section Certifications**
- **ID** : `#certifications`
- **But** : Montrer les certifications et formations pour enrichir le profil
- **Éléments** :
  - **7 cartes de certifications** détaillées :
    - **PIX** (✓ Complétée)
      - Certification française des compétences numériques
      - Reconnaissance nationale du niveau technique
    - **FreeCodeCamp - JavaScript** (✓ Complétée)
      - Concepts avancés du JavaScript
      - Fondations pour les frameworks modernes
    - **IBM - Intro to LLM** (📚 En cours)
      - Fondamentaux des Large Language Models
      - Transformer architecture
    - **IBM - Mastering Prompting** (📚 En cours)
      - Techniques avancées de prompt design
      - Chain-of-thought prompting et few-shot learning
    - **IBM - Intro to Generative AI** (📚 En cours)
      - Vue d'ensemble des technologies génératives
      - Cas d'usage d'entreprise et éthique
    - **CNIL - Atelier RGPD** (✓ Complétée)
      - Principes fondamentaux du RGPD
      - Compliance et privacy by design
      - Documents téléchargeables par module (5 modules)
  - Cartes avec statut (Complétée / En cours)
  - Descriptions contextuelles détaillées
  - Apport professionnel expliqué pour chaque certification
  - Liens vers documents officiels

### 🔟 **Section Contact**
- **ID** : `#contact`
- **But** : Faciliter la prise de contact et les opportunités professionnelles
- **Éléments** :
  - Message de bienvenue et disponibilité
  - **Carte de contact direct** :
    - ✉️ Email : aaron.zerrouk96@gmail.com
    - Lien mailto pour contact rapide
  - **Formulaire de contact** (via Formspree) :
    - Champs : Nom, Email, Message
    - Validation côté client
    - Message de succès après envoi
  - Design invitant et responsive

---

## 🎨 Éléments interactifs

### Animations et Effets
- 🎯 **Curseur personnalisé** : 
  - Follower qui suit le curseur
  - Point de curseur central
  - Orbital autour du curseur
- 🔄 **Animations au scroll** : Transitions fluides des sections
- ✨ **Hover effects** : Interactions sur les cartes, boutons et éléments
- 📍 **Starfield** : Fond animé avec étoiles clignotantes (section Héros)
- 🎭 **Modales** : Pop-ups détaillées pour chaque projet

### Modales Interactives
- Clic sur les cartes de projets = Ouverture de modales détaillées
- Chaque projet a sa propre modale avec :
  - Contexte complet du projet
  - Captures d'écran/images
  - Technologies utilisées
  - Points clés et réalisations
  - Bouton de fermeture

### Navigation
- Barre de navigation **fixe** avec menu responsive
- Logo "AZ." cliquable pour retour au top
- **Menu hamburger** pour mobile
- Scroll smooth entre sections
- Liens de navigation dans le menu déroulant

---

## 📁 Ressources (Dossiers)

### `/img/`
Contient les images statiques et icônes du site :
- `chine.png` — Favicon du portfolio
- `grp.jpg` — Image vignette projet YOASOBI
- `glpi.jpg` — Image vignette projet GLPI
- `coin.jpg` — Image vignette projet CoinMobile

### `/cards/`
Captures d'écran et images des projets pour les modales :
- `SCREENGLPI.png` — Screenshot GLPI
- `Screen4YOA.png` — Screenshot YOASOBI
- `screen1YOA.png`, `screen2YOA.gif`, `screen3YOA.png` — Variantes YOASOBI
- `conf.png` — Configurateur plexiglass
- `pl.png` — Image plexiglass
- `lara.png` — BiblioTech Laravel
- `python.png` — BoutikPro Python

### `/oil/`
Ressources pour le projet e-commerce huiles :
- `olive.png` — Logo/image principale du projet
- `oil1.png` à `oil6.png` — Produits ou screenshots du site

### `/E5/`
Documents officiel concernant l'épreuve E5 BTS SIO :
- `Attestation de stage BTS1 - SIO.pdf` — Attestation première année
- `Attestation de stage BTS2 - SIO.pdf` — Attestation deuxième année
- `BTS_SIO_ZERROUK-Aaron_VI.5_Epreuve E5 - Tableau de synthe.se_2026.xlsx` — Tableau de synthèse

### `/modules/`
Documents des modules CNIL RGPD :
- `MODULE 1 - LE RGPD ET SES NOTIONS CLÉS_Attestation...pdf`
- `MODULE 3 - LES RESPONSABILITES DES ACTEURS_Attestation...pdf`
- `MODULE 4 - LE DPO ET LES OUTILS DE LA CONFORMITÉ_Attestation...pdf`
- `MODULE 5 - LES COLLECTIVITÉS TERRITORIALES_Attestation...pdf`

---

## 🎯 Navigation et flux utilisateur

**Parcours utilisateur typique** :

1. **Atterrissage** → Section Héros avec présentation professionnelle
2. **Découverte** → Section À propos pour connaître la personnalité
3. **Portfolio** → Section Projets, exploration des 7 réalisations
4. **Détails projets** → Clic sur une carte → Modale avec informations complètes
5. **Parcours académique** → Section Éducation avec timeline (3 étapes)
6. **Parcours professionnel** → Section Expérience avec stages (2 internships)
7. **Stack technique** → Section Compétences et Langues
8. **Certifications** → Section Certifications avec 7 formations
9. **Documents officiels** → Section Épreuve E5 avec téléchargements
10. **Action** → Section Contact avec formulaire ou email direct
11. **Réseaux** → Liens externes (GitHub, etc.)

---

## 🎬 Fonctionnalités JavaScript

Le fichier `index.js` gère :

- ✅ Menu mobile responsive avec dropdown
- ✅ Gestion des modales (ouverture/fermeture des projets)
- ✅ Validation du formulaire de contact (nom, email, message)
- ✅ Animations au scroll (intersection observer)
- ✅ Effets de curseur personnalisé (suivi et orbitale)
- ✅ Messages de validation et succès du formulaire
- ✅ Gestion des clics sur les cartes de projets
- ✅ Scroll smooth entre les sections

---

## 🌐 Technologie front-end utilisée

- **HTML5** : Structure sémantique et accessible
- **CSS3** : 
  - Animations et transitions fluides
  - Flexbox et Grid pour layouts responsifs
  - Variables CSS pour cohérence des couleurs et espacements
  - Media queries pour mobile-first approach
- **JavaScript (Vanilla)** : Interactions et logique côté client
- **Responsive Design** : Optimisé pour tous les appareils (mobile, tablet, desktop)
- **Google Fonts** : 
  - `Syne` (700, 800) pour titres et accroches
  - `DM Sans` (300, 400, 500) pour corps du texte
- **Performance** : Images lazy-loaded, minification CSS/JS

---

## 📋 Fichiers clés

| Fichier | Rôle |
|---------|------|
| `index.html` | Structure HTML5 complète avec toutes les sections |
| `index.css` | Tous les styles, animations et variables CSS |
| `index.js` | Interactivité, modales, validation, curseur personnalisé |
| `_config.yml` | Configuration Jekyll pour GitHub Pages |
| `README.md` | Documentation du portfolio (ce fichier) |

---

## 🔗 Liens importants

- 📄 **Portfolio en ligne** : [aaronZER69.github.io](https://aaronZER69.github.io)
- 📧 **Email** : aaron.zerrouk96@gmail.com
- 🐙 **GitHub** : [@aaronZER69](https://github.com/aaronZER69)

---

**Dernière mise à jour** : Avril 2026
