# 🏆 Apprentissage par Renforcement - Exploration d'Environnement

![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)  
Un projet mettant en œuvre un agent intelligent capable d'explorer et d'apprendre dans un environnement de type grille en utilisant des techniques d'apprentissage par renforcement.

## 📖 Introduction

Ce projet explore comment un agent peut apprendre à naviguer dans une grille en optimisant ses choix d'actions grâce à l'apprentissage par renforcement.  
L'objectif est de permettre à l'agent d'identifier un chemin optimal en maximisant ses récompenses tout en évitant les obstacles.

## 🚀 Fonctionnalités

- 🔹 **Environnement sous forme de grille** 🗺️ (5x5)
- 🎯 **Récompenses positives et négatives** pour guider l'agent
- 🤖 **Stratégie d'exploration/exploitation** pour un apprentissage progressif
- 📈 **Mise à jour des valeurs de récompenses** à l'aide d'une méthode d'approximation incrémentale
- 🏁 **Simulation finale pour tester l'efficacité de l'apprentissage**

---

## ⚙️ Installation et Exécution

### 1️⃣ Prérequis  
Assurez-vous d'avoir **Python 3.8+** installé sur votre machine.

### 2️⃣ Cloner le projet  
```sh
git clone https://github.com/AchrafMenach/Reinforcement-Learning-TP-and-Project/tree/main/TP0-Devoir
```

### 3️⃣ Installer les dépendances  
```sh
pip install numpy
```

### 4️⃣ Exécuter le script principal  
```sh
python Devoir.ipynb
```

---

## 🛠️ Structure du Projet

📂 **`/` (Racine du projet)**  
📄 `Devoir.ipynb` - Contient l'implémentation principale de l'agent et de l'environnement  
📄 `README.md` - Documentation du projet  

---

## 🎮 Fonctionnement de l'Agent  

🔹 **Étape 1** : L'agent explore la grille en effectuant des actions aléatoires (exploration).  
🔹 **Étape 2** : Il met à jour sa connaissance des récompenses en fonction des résultats obtenus.  
🔹 **Étape 3** : Progressivement, il privilégie les actions les plus prometteuses (exploitation).  
🔹 **Étape 4** : Après plusieurs épisodes d'entraînement, il est capable de choisir le meilleur chemin.  

---

## 📊 Résultats Attendus

✔️ L'agent apprend à éviter les zones à forte pénalité  
✔️ Il converge vers la stratégie optimale après un certain nombre d'itérations  
✔️ Affichage final du chemin appris  

---

## 📜 Licence & Auteur

📌 **Auteur** : [Achraf Menach]  
📅 **Date** : Mars 2025  
📜 **Licence** : MIT  
💡 **Contact** : [menachachraf3@gmail.com]  
