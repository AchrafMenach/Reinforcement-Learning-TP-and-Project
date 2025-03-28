# 🏆 Apprentissage par Renforcement - Taxi-v3

![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)  
![Gymnasium](https://img.shields.io/badge/Gymnasium-0.29%2B-orange.svg)  
Implémentation d'un algorithme PPO pour résoudre le problème Taxi-v3 de Gymnasium.

## 📖 Introduction

Ce projet démontre l'application de l'algorithme PPO (Proximal Policy Optimization) sur l'environnement Taxi-v3, où un agent taxi doit apprendre à prendre et déposer des passagers de manière optimale.

## 🚀 Fonctionnalités Clés

- 🔹 **Environnement Taxi-v3** avec 500 états et 6 actions
- 🎯 **Algorithme PPO** avec clipping des politiques
- 📈 **Reward Shaping** personnalisé pour accélérer l'apprentissage
- 📊 **Monitoring avancé** des performances
- 🏁 **Early Stopping** lorsque le taux de succès atteint 90%

---

## ⚙️ Installation et Exécution

### 1️⃣ Prérequis  
Python 3.8+ et pip installés

### 2️⃣ Installer les dépendances  
```sh
pip install gymnasium numpy tqdm matplotlib seaborn
```

### 3️⃣ Exécuter l'entraînement et Visualiser les résultats
```sh
python TP3.py
```


---

## 🛠️ Paramètres Optimisés

```python
gamma = 0.99               # Facteur d'actualisation
lr_policy = 0.001          # Taux d'apprentissage politique
lr_value = 0.1             # Taux d'apprentissage valeur
clip_epsilon = 0.2         # Paramètre de clipping PPO
num_train_episodes = 20000 # Nombre maximal d'épisodes
entropy_coeff = 0.01       # Coefficient d'entropie
```

---

## 📊 Résultats

| Métrique               | Avant Entraînement | Après Entraînement |
|------------------------|--------------------|--------------------|
| Récompense moyenne     | -763.55 ± 112.88   | -329.28 ± 730.34   |
| Taux de succès         | 0%                 | 76%                |
| Longueur moyenne       | -                  | 49.5               |
| Épisodes nécessaires   | -                  | 12,500             |

---

## 🎮 Fonctionnement de l'Agent

1. **Initialisation** des tables de politique et de valeur
2. **Collecte** des trajectoires d'épisodes
3. **Calcul** des récompenses actualisées et avantages
4. **Mise à jour** des politiques avec clipping PPO
5. **Optimisation** de la fonction de valeur
6. **Évaluation** périodique des performances

---

## 📜 Licence & Auteur

📌 **Auteur**: [Achraf Menach]  
📅 **Date**: Juin 2024  
📜 **Licence**: MIT  
💡 **Contact**: [menachachraf3@gmail.com]  

> 💡 **Astuce**: Activez `render_mode="human"` pour visualiser l'agent en action!


