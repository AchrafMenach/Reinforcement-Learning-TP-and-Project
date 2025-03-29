# 🏆 Apprentissage par Renforcement - CartPole-v1

![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)  
![Gymnasium](https://img.shields.io/badge/Gymnasium-0.29%2B-orange.svg)  
Un projet démontrant l'apprentissage par renforcement sur l'environnement classique CartPole-v1.

## 📖 Introduction

Ce projet explore comment un agent peut apprendre à maintenir en équilibre un bâton sur un chariot mobile en utilisant des techniques d'apprentissage par renforcement.  
L'objectif est de développer une stratégie optimale pour maximiser la durée d'équilibre.

## 🚀 Fonctionnalités

- 🔹 **Environnement CartPole-v1** avec 4 paramètres d'observation
- 🎯 **Système de récompense** (+1 par pas réussi)
- 🤖 **Stratégie d'exploration/exploitation** adaptable
- 📈 **Visualisation des performances** sur multiples épisodes
- 🏁 **Mode interactif** pour tester manuellement l'agent

---

## ⚙️ Installation et Exécution

### 1️⃣ Prérequis  
Python 3.8+ et pip installés

### 2️⃣ Cloner le projet  
```sh
git clone https://github.com/AchrafMenach/Reinforcement-Learning-TP-and-Project/tree/main/TP1
```

### 3️⃣ Installer les dépendances  
```sh
pip install gymnasium numpy
```

### 4️⃣ Exécuter les démos  
```sh
# Version aléatoire
python cartpole_random.py

# Version interactive
python cartpole_human.py
```

---

## 🛠️ Structure du Projet

📂 **`/` (Racine)**  
├── 📄 `cartpole_random.py` - Implémentation avec actions aléatoires  
├── 📄 `cartpole_human.py` - Version avec rendu visuel  
├── 📄 `requirements.txt` - Dépendances Python  
└── 📄 `README.md`  

---

## 🎮 Fonctionnement de l'Agent  

🔹 **Phase 1** : Exploration aléatoire de l'environnement  
🔹 **Phase 2** : Apprentissage des actions optimales  
🔹 **Phase 3** : Exploitation des connaissances acquises  
🔹 **Phase 4** : Évaluation des performances  

---

## 📊 Résultats Attendus

✔️ Amélioration progressive de la durée d'équilibre  
✔️ Atteinte de 200+ pas après entraînement  
✔️ Visualisation claire de la courbe d'apprentissage  

---

## 📜 Licence & Auteur

📌 **Auteur** : [Achraf Menach]  
📅 **Date** : Mars 2025  
📜 **Licence** : MIT  
💡 **Contact** : [menachachraf3@gmail.com]  
```

