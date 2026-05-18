# 🎱 Loto en Salle

> Application web de tirage de loto et bingo pour animations de salle — kermesses, associations, salles des fêtes, anniversaires.

[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![GitHub Pages](https://img.shields.io/badge/demo-en%20ligne-brightgreen)](https://romain62300.github.io/loto-salle/loto.html)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)]()
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)]()

---

## 📖 À propos

**Loto en Salle** est une application web 100 % gratuite, sans installation et sans connexion requise. Elle remplace le boulier traditionnel lors de vos soirées loto ou bingo. Il suffit d'ouvrir le fichier `loto.html` dans un navigateur, de brancher un vidéoprojecteur ou une télévision, et c'est parti.

Idéale pour :
- 🏘️ Associations et collectes de fonds
- 🎪 Kermesses d'école et fêtes de village
- 🎂 Soirées entre amis et anniversaires
- 🏛️ Maisons de retraite et clubs du 3ᵉ âge
- 🍻 Bars et restaurants souhaitant animer leurs soirées

---

## ✨ Fonctionnalités

- 🎱 **Mode Loto** — tirage aléatoire de 1 à 90, boules colorées par dizaine
- 🃏 **Mode Bingo** — tirage de 1 à 75 avec colonnes B-I-N-G-O
- 🔊 **Annonce vocale** — style animateur traditionnel ("5, le 5 tout seul !")
- 🎵 **Son de boule** — effet sonore à chaque tirage (Web Audio API)
- ⏱️ **Délai configurable** entre les tirages (5s à 30s), modifiable en cours de partie
- 🔁 **Bouton Répéter** — rejoue l'annonce du dernier numéro à la demande
- ⛶ **Mode plein écran** — parfait pour vidéoprojecteur ou grande télévision
- ⏸️ **Pause / Reprise** à tout moment
- 📊 **Grille complète** avec tous les numéros tirés mis en évidence
- 📜 **Historique complet** scrollable de tous les tirages
- 🎊 **Confettis** et mélodie à la fin de partie
- 📱 **Responsive** — fonctionne sur mobile, tablette et PC
- 🌐 **Fonctionne hors-ligne** une fois la page chargée (aucune dépendance externe)

---

## 🚀 Démo en ligne

👉 **[Ouvrir l'application](https://romain62300.github.io/loto-salle/loto.html)**

Aucune installation requise. Fonctionne sur Chrome, Edge, Firefox et Safari.

---

## 📦 Installation locale

```bash
# Cloner le dépôt
git clone https://github.com/Romain62300/loto-salle.git

# Ouvrir le fichier directement dans votre navigateur
# Windows
start loto-salle/loto.html

# macOS
open loto-salle/loto.html
```

Ou simplement télécharger le fichier `loto.html` et double-cliquer dessus.

---

## 🎮 Utilisation

1. Choisir le mode **Loto** (1–90) ou **Bingo** (1–75)
2. Régler le délai entre les tirages selon le rythme souhaité
3. Activer ou désactiver la voix et le son selon l'environnement
4. Cliquer sur **▶ Démarrer**
5. Mettre en **⏸ Pause** à tout moment (pour vérifier les cartons par exemple)
6. Cliquer sur **🔁 Répéter** si un joueur n'a pas entendu le numéro
7. Utiliser **⛶ Plein écran** si l'application est projetée sur grand écran

---

## 🛠️ Technologies

- HTML5, CSS3, JavaScript vanilla — aucun framework
- Web Speech API pour l'annonce vocale
- Web Audio API pour les effets sonores
- Canvas API pour les confettis
- Un seul fichier autonome, zéro dépendance

---

## 📁 Structure du projet

```
loto-salle/
└── loto.html      # Application complète (HTML + CSS + JS)
└── README.md      # Documentation
└── LICENSE        # Licence MIT
└── .gitignore     # Fichiers exclus du dépôt
```

---

## 📜 Licence

Ce projet est distribué sous licence **MIT**.
Vous êtes libre de l'utiliser, le modifier et le redistribuer, à condition de conserver la mention de l'auteur original.

Voir le fichier [LICENSE](LICENSE) pour les détails complets.

---

## 👤 Auteur

**Romain** — [Alakachan Dev](https://romain62300.github.io/alakachan-dev/)  
Développeur web freelance en formation

---

## 🌟 Contribuer

Les suggestions et améliorations sont les bienvenues !  
N'hésitez pas à ouvrir une [issue](https://github.com/Romain62300/loto-salle/issues) ou une pull request.
