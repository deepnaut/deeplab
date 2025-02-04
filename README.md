# Projet `deeplab`

Ce projet est un prétexte pour l'UE d'informatique avancée.

## Installation

### 1. Création de l'environnement virtuel

```bash
python -m venv venv
```

### 2. Activation de l'environnement virtuel

```bash
source venv/bin/activate
```

### 3. Installation des dépendances

```bash
pip install -r requirements.txt
```

## Structure du Projet

* `data/`: Contient les données brutes et processed
* `models/`: Stocke les modèles entrainés
* `notebooks/`: Contient les Jupyter notebooks exploratoires
* `src/`: Contient le code source du projet
* `tests/`: Test unitaires


---

# Git Setup Guide

## Initial Configuration
```bash
git config --global user.name "Your_Name"
git config --global user.email "your.email@example.com"

# Initialize Git in project folder
git init

# Create .gitignore
venv/
__pycache__/
*.pyc
.env

# Add all files and commit
git add .
git commit -m "Initial commit"

# Link local to GitHub repository
git remote add origin https://USERNAME:YOUR_TOKEN@github.com/USERNAME/REPO.git
git branch -M main
git push -u origin main

git status          # Check changes
git add .           # Stage all changes
git commit -m "..."  # Commit with message
git push           # Push to GitHub

---
---

```bash
pip freeze > requirements.txt
pip freeze | grep -f requirements.txt
```

```bash
pip check
deactivate
```

```bash
git config --global user.name "Votre_Nom"
git config --global user.email "email@utilisé_sur_github.com"

cd path
git init
```

.gitignore

```bash
git add .
git commit -m "Initial commit : projet deeplab"
```

create new repo
https://github.com/deepnaut/deeplab.git

```bash
git remote add origin https://github.com/deepnaut/deeplab.git            
git branch -M main
git push -u origin main
```

```bash
git add .
git commit -m "Description des modifications"
git push
```

token

```bash
git status
```
