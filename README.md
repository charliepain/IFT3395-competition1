# Instructions pour exécuter le code

Assurez-vous d'avoir Python 3.9 ou supérieur installé ainsi que pip. Vous pouvez utiliser soit Conda soit Virtual Environment (venv) pour gérer vos dépendances.

### Lien vers la compétition: https://www.kaggle.com/competitions/ift-6390-ift-3395-beer-quality-prediction/overview

### 📋 Configuration de l'Environnement

#### Option 1 : Utilisation de Conda 🐍
```bash
# Créer un nouvel environnement conda
conda create -n .venv python=3.9

# Activer l'environnement
conda activate .venv

# Installer les dépendances
pip install -r requirements.txt
```

#### Option 2 : Utilisation de Virtual Environment (venv) 📦
```bash
# Créer un environnement virtuel
python3.9 -m venv .venv

# Activer l'environnement
# Sur Linux/macOS :
source .venv/bin/activate
# Sur Windows :
# .venv\Scripts\activate

# Installer les dépendances
pip install -r requirements.txt
```

### Exécution du code

#### 1. Ouvrez jupyter notebook.
```
jupyter notebook
```

#### 2. Ouvrez notebook.ipynb avec jupyter notebook qui apparaît dans votre navigateur.

#### 3. Lancez toutes les cellules (bouton fast-forwarrd "Restart the kernel and run all cells").
Cela pourrait prendre quelques minutes (~2 minutes sur ma machine)  
Un fichier "submission.csv" qui contient les prédictions faites par le meilleur modèle sur l'ensemble de test de "test.csv" est créé.

#### 4. Soumission (pas certain si c'est possible pour les gens qui n'ont pas participé à la compétition)
Le fichier "submission.csv" peut être soumis à la compétition pour obtenir
la précision (accuracy) des prédictions.  
Lien vers la compétition: https://www.kaggle.com/competitions/ift-6390-ift-3395-beer-quality-prediction/overview

