# restaurant-limperial

![Image](https://github.com/user-attachments/assets/ee2ef40c-f6df-44ad-ad2a-febc4249a4bd)

Ce projet **L'Impérial** est un **restaurant fictif** créé uniquement pour le plaisir et à des fins d’apprentissage.  
Ce document décrit la vision, les objectifs et les fonctionnalités du site.  
Il servira de référence si vous souhaitez explorer, modifier ou améliorer ce projet.

---

## 1. Présentation du Projet

**Nom du site** : L'Impérial (fictif, non réel)  
**Type** : Site web vitrine avec fonctionnalités de réservation en ligne (fictives).  
**Objectif principal** : Apprendre et s’exercer à la création d’un site complet, incluant :

- Présentation de l’histoire, de l’ambiance et des valeurs (section *Notre Histoire*).
- Mise en avant de la carte (section *Notre Carte*).
- Système de réservation (section *Réserver*).

> **Note** : Aucune réservation n’est réellement enregistrée ou traitée. Tout est entièrement fictif.

---

## 2. Objectifs

1. **Exercice de conception**  
   Se familiariser avec la création d’un site vitrine et la présentation d’informations de type « restaurant ».

2. **Expérimenter la réservation en ligne**  
   Mettre en place un formulaire de réservation *fictif* pour apprendre à gérer des champs, des validations et des messages de confirmation.

3. **Responsivité & Accessibilité**  
   Appliquer les bonnes pratiques pour un affichage adapté à tous les supports (ordinateurs, tablettes, smartphones).

4. **Design & Esthétique**  
   Créer une interface élégante et immersive, mettant en avant un univers haut de gamme.

---

## 3. Arborescence et Structure des Pages

Le projet comprend quatre fichiers principaux :

1. **index.html**  
   - Page d’accueil avec une section *hero*, un aperçu de la carte et un lien vers la page de réservation.
   - Barre de navigation fixe au défilement.

2. **menu.html**  
   - Liste complète des plats fictifs (entrées, plats, cocktails, desserts).
   - Filtres (boutons) permettant de basculer entre les catégories.

3. **reservation.html**  
   - Formulaire fictif de réservation (nom, email, date, heure, etc.).
   - Confirmation JavaScript simulant une prise en compte de la réservation.

4. **style.css**  
   - Styles globaux (couleurs, typographie, transitions, responsivité).
   - Gère notamment l’aspect de la navbar, des sections, et des animations de survol.

---

## 4. Fonctionnalités Clés

### 4.1. Accueil (index.html)
- **Bannière principale (hero)** : Message d’accroche et CTA menant à la section *Notre Carte*.
- Informations pratiques (adresse fictive, horaires fictifs).
- Présentation de l’histoire du « restaurant » (fictive).

### 4.2. Notre Carte (menu.html)
- Affichage visuel des différents plats fictifs, avec photos et prix d’exemple.
- **Système de filtres** : Entrées, plats, cocktails, desserts.

### 4.3. Réserver (reservation.html)
- **Formulaire de réservation** fictif.
- Champ pour indiquer un message spécial (allergies imaginaires, etc.).
- Alerte de confirmation simulée en JavaScript.

### 4.4. Navigation
- **Navbar fixe** : Lien direct vers les sections principales et autres pages.
- Effet de changement de couleur au défilement (scroll).

### 4.5. Responsivité
- Grille **Bootstrap** et media queries dans `style.css`.
- Affichage adapté pour ordinateurs de bureau, tablettes et mobiles.

---

## 5. Technologies Utilisées

- **HTML5** : Structure des pages (index, menu, réservation).
- **CSS3** : Mise en forme et transitions (fichier `style.css`).
- **Bootstrap** : Système de grille et composants (navbar, formulaires, boutons).
- **JavaScript** : Scripts intégrés (validation du formulaire fictif, animations simples).
- **AOS (Animate On Scroll)** : Animations lorsqu’on fait défiler la page.
- **Bootstrap Icons** : Jeux d’icônes pour les réseaux sociaux, téléphone, etc.

---

## 6. Design et Charte Graphique

- **Palette de couleurs** :  
  - Or (#D4AF37) pour les éléments clés (boutons, accents).  
  - Noir / Gris foncé (#111111, #000000) comme couleur de fond.  
  - Blanc / Gris clair pour le texte.
  
- **Typographie** :  
  - *DM Sans* (Google Fonts).

- **Mise en page** :  
  - Sections aérées et visuelles, textes centrés, titres imposants.
  - Ambiance chic et intimiste, rappelant un restaurant haut de gamme.

---

## 7. Arborescence du projet
```
├── assets
│   ├── css
│   │    └── style.css
│   ├── img
│        └── (images du site)
├── index.html
├── menu.html
├── reservation.html
└── README.md
```
## 8. Évolutions Possibles

### 8.1. Envoi d’emails : Connecter à un back-end (par exemple, Node.js ou PHP) pour envoyer de faux e-mails de confirmation.
### 8.2. Système d’authentification : Imaginer un espace admin fictif pour gérer les réservations reçues (toujours hypothétiques).
### 8.3. Base de données : Conserver et lister les réservations dans une base de données (MySQL, PostgreSQL, etc.), à titre d’exercice.
### 8.4. Multilingue : Permettre la consultation en plusieurs langues (fr, en, etc.).
### 8.5. SEO : Ajuster les balises méta, générer un sitemap, et ainsi de suite, même si le site reste fictif.

## 9. Maintenance

### 9.1. Contenu : Mettre à jour les plats, tarifs fictifs, images, etc.
### 9.2. Dépendances : Surveiller les versions de Bootstrap, AOS et autres scripts.
### 9.3. Tests : Vérifier régulièrement l’affichage responsive et la compatibilité entre navigateurs.

## 10. Contact

- Pour toute suggestion ou problème rencontré lors de l’utilisation de ce projet purement fictif, vous pouvez créer une issue sur ce dépôt GitHub.
