# Aegis Bank — Landing Page
### Version HTML5 · CSS3

---

## À propos du projet

Ce projet est la landing page pour **Aegis Bank**, une néobanque fictive éthique positionnée comme une alternative responsable aux banques en ligne classiques.

Réalisée entièrement en **HTML5 et CSS3**, l'interface met en avant une identité visuelle forte et minimaliste — noir et blanc, typographie Impact en grands caractères — autour du message : *"La néobanque qui place la confidentialité au cœur de la finance moderne."*

> **Note :** Aegis Bank et Namcod sont des entités fictives créées dans le cadre d'un exercice pédagogique de développement web frontend.

---

## Pourquoi ce projet est utile

Cette landing page répond à un cahier des charges alliant **objectifs pédagogiques** et **contraintes techniques** :

- **Architecture sémantique HTML5** : Structuration avec les balises `<header>`, `<main>`, `<section>` et `<footer>` pour une hiérarchie claire.
- **Mise en page CSS Grid** : La section principale (`.main-page`) repose sur une grille de 7 lignes × 6 colonnes gérant le positionnement de chaque bloc.
- **En-tête fixe** : Logo NAMCO, boutons LOGIN / REGISTER et icône de menu burger, positionnés en `fixed` au-dessus du contenu.
- **Hero Section impactante** : Titre principal en `15vw`, texte descriptif, icônes SVG des réseaux sociaux alternatifs (Bluesky, Mastodon, Telegram) et offre promotionnelle **20€ OFFERT**.
- **Appel à l'action** : Bouton "TÉLÉCHARGER AEGIS BANK" en pleine largeur sur fond noir.
- **Lignes décoratives de fond** : Six `<div>` positionnées en CSS Grid créent un effet de grille verticale semi-transparente (`opacity: 0.2`) en arrière-plan.
- **Footer fixe** : Texte de présentation centré et date de mise en ligne, positionné en `fixed` en bas de page.

---

## Structure du projet
aegis-bank/
├── index.html        → Structure et contenu de la page
├── style.css         → Mise en page (CSS Grid, Flexbox, typographie)
└── image/
├── menu.svg                          → Icône menu burger
├── Bluesky_Logo 1.svg                → Logo Bluesky
├── Mastodon_Logotype_(Simple) 1.svg  → Logo Mastodon
└── Vector.svg                        → Icône Telegram

---

## Utilisation

Ce projet est un site statique. **Aucune installation, aucune dépendance, aucune compilation n'est requise.**

1. Téléchargez ou clonez le dossier du projet
2. Ouvrez le fichier `index.html` directement dans votre navigateur (Chrome, Firefox, Safari…)

> **Astuce VS Code :** L'extension **Live Server** permet de visualiser les modifications en temps réel sans recharger manuellement la page.

---

## Objectifs pédagogiques

- Structurer une page web avec les balises sémantiques HTML5
- Organiser une interface avec **CSS Grid** (grille 7×6)
- Positionner des éléments avec **Flexbox**
- Utiliser des polices externes via **Google Fonts** et **CDN Fonts** (Inter, Impact)
- Intégrer des ressources graphiques au format **SVG**
- Travailler la hiérarchie visuelle et la mise en page responsive

---

## Pistes d'amélioration

- Ajouter des **media queries** pour une meilleure adaptation mobile et tablette
- Améliorer l'**accessibilité** (attributs `alt`, contrastes, navigation clavier)
- Normaliser les noms de classes CSS (ex : corriger `second-element-coantainer`, `pormotion-element-container`, `bottom-foot-caontainer`)
- Ajouter des **animations CSS** sur les boutons et le titre
- Transformer les boutons LOGIN / REGISTER en liens `<a>` fonctionnels

---

## Auteur

**Yaw Okyere Darko**  
Projet réalisé dans le cadre d'un exercice de développement web frontend.