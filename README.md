# 🐜 Le Fourmilier Anonyme

> Il n’a pas de nom, pas de visage, et un museau de 60 centimètres. Il entre dans vos systèmes, il repart avec vos diamants.

Un site parodique pour **apprendre la cybersécurité en s’amusant**, accompagné de **Nuit blanche**, un jeu d’horreur en 3D jouable directement dans le navigateur.

Tout tient en quelques fichiers HTML : pas d’installation, pas de serveur, pas de base de données. Tout est simulé et sauvegardé dans ton navigateur, et rien n’est envoyé sur Internet.

---

## ✨ Ce qu’il y a dedans

### 🔐 Le site
- **Labo d’audit** : teste la solidité d’un mot de passe, analyse un lien suspect, utilise la boîte à outils du terminal.
- **Défi CTF** : 7 failles à trouver pour récupérer des drapeaux `FOURMI{...}`, avec indices et diplôme à la clé.
- **L’Académie du Fourmilier** : 10 salles d’entraînement façon TryHackMe, du débutant à l’avancé :
  - Terminal Linux
  - Mots de passe et hachage
  - Phishing
  - Cryptographie
  - Inspecteur web (F12)
  - Réseau et scan de ports
  - Enquête OSINT
  - Analyse de logs
  - Stéganographie
  - Pare-feu
- **Profil de hacker** : points, rangs, badges, défi de la semaine, mémo sécurité et certificat final.
- **Tableau de chasse** : toute ta progression sur le site (CTF, Académie, jeu) réunie au même endroit.
- **Glossaire**, easter eggs… et un screamer qui t’attend quelque part.

### 🌙 Nuit blanche, le jeu
Tu es **Oslo Mignon**, nouveau gardien de nuit à la Résidence Opale. Ton père, Maurice, a disparu dans cet immeuble il y a vingt-huit ans. Ce soir, quelque chose renifle dans les couloirs.

- Horreur en 3D (three.js) sur **5 étages** générés aléatoirement, chacun avec son ambiance : Hall, Bureaux, Cuisine, Sous-sol… et le toit, dehors, la nuit, sous la pluie.
- **3 fourmiliers** aux comportements différents : l’un te traque, l’autre surgit pour t’observer, le dernier garde les clés.
- Armes avec balles visibles et impacts sur les murs, rechargement, lampe torche (sans piles en Facile), casiers pour se cacher, boutique avec objets fun et casino (roulette, machine à sous).
- Une histoire qui se dévoile en avançant : carnet de Maurice, pages cachées, badges des Neuf, bestiaire.
- **6 fins**, dont une cachée derrière la cellule 0007, avec leurs cinématiques, des easter eggs et un monde secret.
- Jouable au clavier et à la souris, mais aussi sur **tablette et téléphone**.

---

## 🚀 Lancer le projet

**En local**

Ouvre simplement `index.html` dans ton navigateur (Firefox, Chrome, Edge…).

Le jeu télécharge son moteur 3D au lancement : il faut une connexion Internet et un navigateur avec WebGL activé.

**En ligne avec GitHub Pages**
1. Mets les fichiers à la racine du dépôt.
2. Va dans **Settings → Pages**.
3. Choisis la branche `main` et le dossier `/ (root)`.
4. Le site sera disponible à l’adresse `https://<ton-pseudo>.github.io/<nom-du-depot>/`.

---

## 🎮 Commandes du jeu

| Action | Touche |
|---|---|
| Se déplacer | ZQSD / WASD / flèches |
| Regarder | Souris |
| Attaquer / tirer | Clic ou F |
| Courir | Maj |
| Sauter | Espace |
| Interagir (clé, boutique, casiers, ventilations) | E |
| Inventaire | I ou Tab |
| Changer d’arme | 1 à 5 ou molette |
| Recharger | R |
| Trousse de soin | H ou 6 |
| Lampe torche | L |
| Siffler (dès l’étage 2) | G |
| Pause | Échap |

Les touches se modifient dans **Réglages**. Les codes secrets se tapent dans le menu pause (essaie `hareng`… ou `fin` pour choisir ta fin).

Sur écran tactile : pavé à gauche pour bouger, glisser sur l’écran pour regarder, boutons d’action à droite.

---

## 📁 Fichiers

```
├── index.html                    # Le site : audit, CTF, Académie, tableau de chasse
├── jeu-fourmilier-ameliore.html  # Nuit blanche, le jeu 3D
├── jeu-fourmilier.html           # L’ancienne version 2D du jeu
└── README.md
```

---

## 🛠️ Technologies

- HTML, CSS et JavaScript, sans framework ni étape de compilation.
- [three.js](https://threejs.org/) 0.160 pour la 3D, chargé depuis un CDN.
- Web Audio API : tous les sons et la musique sont générés par le code.
- `localStorage` pour les sauvegardes : progression, records, réglages.

---

## ⚠️ Avertissement

Ce projet est une **parodie** et un **outil pédagogique**. Les attaques présentées sont simulées et servent à comprendre comment se défendre. N’utilise jamais ces techniques sur un système sans autorisation. Toute ressemblance avec un vrai fourmilier serait fortuite.

---

<p align="center">Fait avec des fourmis, des diamants et beaucoup de JavaScript. 🐜💎</p>
