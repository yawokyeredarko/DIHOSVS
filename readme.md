# Aegis Bank — Landing Page
## "Néobanque Éthique & Transparente"
### Version HTML5 · CSS3

---

## À propos du projet

Ce projet est la landing page pour **Aegis Bank**, une néobanque fictive éthique se positionnant comme une alternative responsable aux banques en ligne classiques.

Réalisée dans le cadre d'un exercice pédagogique de développement web frontend, cette interface met en avant une **finance numérique responsable**, centrée sur la confidentialité des données, la transparence absolue et la non-monétisation des informations personnelles.

Le site affirme son identité visuelle par un design noir et blanc épuré, une typographie Impact en grands caractères et le message : *"La néobanque qui place la confidentialité au cœur de la finance moderne."*

> **Note :** Aegis Bank et Namcod sont des entités fictives créées dans le cadre d'un exercice pédagogique de développement web.

---

## Pourquoi ce projet est utile

Cette landing page répond à un cahier des charges strict alliant **objectifs marketing** et **contraintes techniques** :

- **Expérience "Zero-Scroll"** : L'interface est conçue pour tenir sur une hauteur de vue unique (`100vh`), l'ensemble du contenu s'affichant sans aucun défilement vertical grâce à une grille CSS de 7 lignes × 6 colonnes.
- **Architecture de l'information** : Un en-tête fixe avec logo, boutons LOGIN / REGISTER et icône menu burger, structuré en Flexbox pour un positionnement précis.
- **Hero Section impactante** : Titre principal en `15vw`, texte descriptif, offre promotionnelle **20€ OFFERT** et icônes SVG des réseaux sociaux alternatifs (Bluesky, Mastodon, Telegram).
- **Appel à l'action clair** : Bouton "TÉLÉCHARGER AEGIS BANK" en pleine largeur sur fond noir, positionné stratégiquement dans la grille.
- **Transparence et éthique** : Un design épuré qui reflète les valeurs de la banque, avec des lignes décoratives de fond semi-transparentes (`opacity: 0.2`) et un footer fixe incluant les mentions légales.

---

## Comment démarrer

Ce projet est un site statique classique. **Aucune installation complexe ou compilation n'est requise.**

### Structure du projet

Le dépôt contient uniquement les fichiers essentiels :
aegis-bank/
├── index.html   → La structure principale et le contenu de la page
├── style.css    → La feuille de style gérant le design et le zero-scroll
└── image/
├── menu.svg
├── Bluesky_Logo 1.svg
├── Mastodon_Logotype_(Simple) 1.svg
└── Vector.svg

### Installation et utilisation

1. Clonez le dépôt sur votre machine :
```bash
git clone https://github.com/votre-utilisateur/aegis-bank.git
```
2. Accédez au dossier du projet :
```bash
cd aegis-bank
```
3. Ouvrez simplement le fichier `index.html` dans votre navigateur web préféré (Chrome, Firefox, Safari) en double-cliquant dessus.

> **Astuce pour les développeurs :** Si vous utilisez VS Code, lancez l'extension **Live Server** pour bénéficier du rechargement automatique à chaque modification de votre code.

---

## Où obtenir de l'aide

Si vous rencontrez des problèmes d'affichage (notamment sur la contrainte zero-scroll sur certains appareils mobiles) ou si vous avez des questions sur l'intégration :

- Ouvrez une **Issue** directement sur ce dépôt GitHub en décrivant le problème (taille de l'écran, navigateur utilisé).
- Vérifiez votre **console navigateur** (`F12`) pour vous assurer que les chemins vers `style.css` ou les icônes du dossier `image/` sont corrects.

---

## Mainteneurs et contributions

Ce projet est développé et maintenu individuellement dans le cadre d'une **formation en développement web frontend**.

**Auteur :** Yaw Okyere Darko

Les retours constructifs et les suggestions d'amélioration pour le design UI/UX sont les bienvenus. Si vous souhaitez proposer une modification :

1. **Forkez** le projet.
2. Créez une branche pour votre fonctionnalité :
```bash
git checkout -b feature/AmeliorationDesign
```
3. Poussez vos modifications :
```bash
git push origin feature/AmeliorationDesign
```
4. Ouvrez une **Pull Request**.