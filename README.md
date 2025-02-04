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

.gitignore

git add .
```