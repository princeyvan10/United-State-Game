# United-State-Game
# 🗺️ United States Game

Un jeu éducatif interactif développé en Python permettant d'apprendre la géographie des États-Unis de manière ludique.

## 📋 Description

Ce projet est un jeu de géographie où l'utilisateur doit deviner les noms des 50 états américains. Le programme affiche une carte des États-Unis et positionne automatiquement chaque état correctement deviné sur la carte. C'est un excellent outil d'apprentissage pour mémoriser la localisation des états américains.

## ✨ Fonctionnalités

- 🎮 Interface graphique interactive avec Turtle
- 📍 Affichage dynamique des états devinés sur la carte
- 📊 Suivi du score en temps réel
- 💾 Génération automatique d'un fichier CSV des états non devinés pour révision
- 🚪 Possibilité de quitter le jeu à tout moment avec la commande "Exit"
- 🔤 Reconnaissance insensible à la casse (majuscules/minuscules)

## 🛠️ Technologies utilisées

- **Python 3.x**
- **Turtle** - Bibliothèque graphique pour l'interface utilisateur
- **Pandas** - Manipulation et analyse des données CSV

## 📦 Installation

### Prérequis

Assurez-vous d'avoir Python 3.x installé sur votre système.

### Installation des dépendances

```bash
pip install pandas
```

Note : La bibliothèque `turtle` est incluse par défaut avec Python.

## 🚀 Comment jouer

1. Clonez le dépôt :
```bash
git clone https://github.com/princeyvan10/United-State-Game.git
cd United-State-Game
```

2. Lancez le jeu :
```bash
python main.py
```

3. Une fenêtre s'ouvre avec la carte des États-Unis
4. Entrez le nom d'un état américain dans la boîte de dialogue
5. Si votre réponse est correcte, l'état apparaît sur la carte
6. Continuez jusqu'à deviner les 50 états ou tapez "Exit" pour quitter

## 📂 Structure du projet

```
United-State-Game/
│
├── main.py                 # Script principal du jeu
├── 50_states.csv          # Données des états (noms et coordonnées)
├── blank_states_img.gif   # Image de la carte des États-Unis
├── states_to_learn.csv    # Fichier généré avec les états manqués
└── README.md              # Documentation du projet
```

## 🎯 Règles du jeu

- Devinez les 50 états américains en entrant leur nom
- Les noms ne sont pas sensibles à la casse
- Tapez "Exit" pour quitter et sauvegarder vos états manqués
- Un fichier `states_to_learn.csv` sera créé avec les états que vous n'avez pas trouvés

## 🔄 Améliorations futures possibles

- [ ] Ajout d'un système de temps/chronomètre
- [ ] Mode difficulté (indices, nombre d'essais limité)
- [ ] Sauvegarde des scores et statistiques
- [ ] Support multilingue
- [ ] Ajout d'autres jeux géographiques (pays, capitales, etc.)
- [ ] Interface utilisateur améliorée avec Tkinter ou PyQt

## 📝 Apprentissages clés

Ce projet m'a permis de développer mes compétences en :
- Programmation orientée objet avec Python
- Manipulation de données avec Pandas
- Création d'interfaces graphiques avec Turtle
- Gestion de fichiers CSV
- Logique de jeu et interactions utilisateur

## 👤 Auteur

**Prince Yvan Djine Kadji**
- GitHub: [@princeyvan10](https://github.com/princeyvan10)
- LinkedIn: [Prince Yvan Djine Kadji](https://linkedin.com/in/prince-yvan-djine-kadji-40a91737b)

## 📄 Licence

Ce projet est libre d'utilisation à des fins éducatives.

---

⭐ N'hésitez pas à mettre une étoile si ce projet vous a été utile !
