# 🏆 Apprentissage par Renforcement - FrozenLake-v1

![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)  
![Gymnasium](https://img.shields.io/badge/Gymnasium-0.29%2B-orange.svg)  
Implémentation d'un algorithme Q-Learning pour résoudre l'environnement FrozenLake-v1 de Gymnasium.

## 📖 Introduction

Ce projet démontre l'application du Q-Learning sur le problème FrozenLake, où un agent doit apprendre à naviguer sur une surface gelée pour atteindre un objectif tout en évitant des trous.

## 🚀 Fonctionnalités Clés

- 🔹 **Environnement FrozenLake** (4x4 ou 8x8)
- 🎯 **Algorithme Q-Learning** avec exploration ε-greedy
- 📈 **Mise à jour incrémentale** de la Q-table
- 📊 **Visualisation des progrès** par épisodes
- 🏁 **Mode test** pour évaluer l'agent entraîné

---

## ⚙️ Installation et Exécution

### 1️⃣ Prérequis  
Python 3.8+ et pip installés

### 2️⃣ Installer les dépendances  
```sh
pip install gym numpy
```

### 3️⃣ Exécuter l'entraînement et Tester l'agent entraîné
```sh
python Frozenlake.ipynb
```



---

## 🛠️ Structure du Code

```python
# Initialisation
env = gym.make("FrozenLake-v1", is_slippery=False)
q_table = np.zeros((state_space_size, action_space_size))

# Paramètres
learning_rate = 0.1
discount_rate = 0.99
exploration_rate = 1.0
```

---

## 📊 Résultats

| Épisodes | Taux de Réussite |
|----------|------------------|
| 1-1000   | 29.1%            |
| 2000     | 72.5%            |
| 5000     | 97.1%            |
| 10000    | 99.0%            |

**Q-table finale après entraînement:**
```python
[[0.94 0.95 0.95 0.94]
 [0.94 0.   0.96 0.95]
 ...
 [0.98 0.99 1.   0.98]]
```

---

## 🎮 Fonctionnement de l'Agent

1. **Initialisation** de la Q-table avec des zeros
2. **Exploration** aléatoire initiale (ε=1.0)
3. **Mise à jour** progressive des valeurs Q
4. **Réduction** du taux d'exploration (ε-decay)
5. **Convergence** vers la politique optimale

---

## 📜 Licence & Auteur

📌 **Auteur**: [Achraf Menach]  
📅 **Date**: Juin 2024  
📜 **Licence**: MIT  
💡 **Contact**: [menachachraf3@gmail.com]  

> 💡 **Astuce**: Activez `is_slippery=True` pour une version plus difficile avec glissement!
``` 

