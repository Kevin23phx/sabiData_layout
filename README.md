# 🇧🇫 SabiData Layout — Vitrine & Présentation

Bienvenue sur le dépôt officiel du **layout et de la landing page SabiData**, la plateforme de collecte crowdsourcée et de valorisation de données audio en langues nationales burkinabè (*Mooré*, *Dioula*, *Fulfuldé*, *Gulmancema*).

---

## 🌟 Aperçu du Projet

SabiData combine la collecte citoyenne de données vocales, la validation communautaire, des récompenses réelles via Mobile Money et des modèles d'intelligence artificielle (NLP & Reconnaissance Vocale).

Ce dépôt contient la vitrine web interactive présentant :
- 📱 **Le fonctionnement & les applications** (Mobile Flutter offline-first, Console Admin React, API cloud Railway)
- 🌍 **Les langues nationales supportées** et leurs métriques
- 🎮 **Le système de gamification & récompenses**
- 💡 **La mission culturelle & technologique**
- 👥 **La section L'Équipe (Team SabiData)** avec cartes personnalisables (photos, rôles, liens GitHub & LinkedIn)
- ⚖️ **Copyright 2026 Team SabiData**

---

## 👥 Personnalisation de l'Équipe (Team Panels)

La section **L'Équipe** (`#team`) dans `index.html` permet à chaque membre de la Team SabiData de mettre en valeur son profil :

### 1. Ajouter une photo
Dans chaque carte membre (`.team-card`), remplacez le bloc d'avatar par votre photo :
```html
<div class="team-card__avatar-wrap">
  <img src="https://github.com/votre-pseudo.png" alt="Votre Nom" class="team-card__avatar-img" />
</div>
```
*(Vous pouvez utiliser l'URL de votre avatar GitHub `https://github.com/<pseudo>.png` ou un chemin local).*

### 2. Mettre à jour vos liens GitHub et LinkedIn
Dans le bloc `.team-card__socials`, mettez à jour les attributs `href` :
```html
<a href="https://github.com/votre-compte" target="_blank" class="team-social-btn team-social-btn--github">
  ... GitHub
</a>
<a href="https://linkedin.com/in/votre-compte" target="_blank" class="team-social-btn team-social-btn--linkedin">
  ... LinkedIn
</a>
```

### 3. Modifier le rôle, la biographie et les compétences
- Nom : `<div class="team-card__name">Votre Nom</div>`
- Rôle : `<div class="team-card__role">Votre Rôle</div>`
- Bio : `<p class="team-card__bio">Description...</p>`
- Tags : `<span class="team-card__tag">Compétence</span>`

---

## 🚀 Lancement Local

Ce projet est conçu en HTML5 / CSS3 / JavaScript vanilla moderne, sans dépendance lourde requise pour la prévisualisation.

### Option 1 : Ouvrir directement
Double-cliquez simplement sur [index.html](file:///C:/Users/T490s/Downloads/sabidata_layout/index.html) dans votre navigateur web.

### Option 2 : Avec un serveur local (recommandé)
```bash
# Avec Python
python -m http.server 3000

# Ou avec Node.js / npx
npx serve .
```
Accédez ensuite à `http://localhost:3000`.

---

## 📜 Licence & Droits

© 2026 **Team SabiData** · Burkina Faso 🇧🇫  
*Fait avec ❤ par Team SabiData · Pour préserver nos langues.*
