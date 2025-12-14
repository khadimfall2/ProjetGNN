# GNNExplainer : Explicabilité des Réseaux de Neurones Graphiques

## Description du projet
Ce projet explore l'interprétabilité des modèles de Deep Learning appliqués aux graphes (GNN). Les réseaux de neurones graphiques sont performants pour analyser des données structurées (réseaux sociaux, molécules), mais leurs décisions restent souvent opaques ("boîte noire").

Nous utilisons ici la méthode **GNNExplainer** pour identifier les sous-graphes et les caractéristiques de nœuds qui influencent le plus la prédiction du modèle. L'objectif est de générer des visualisations claires justifiant la classification opérée par le réseau.

## Données
Le projet utilise le dataset **Mondiale.P**.
* **Structure :** Graphe représentant des relations géopolitiques.
* **Nœuds :** Pays.
* **Arêtes :** Frontières terrestres partagées.
* **Attributs :** Données socio-économiques et démographiques.

## Installation

### 1. Cloner le dépôt
git clone git@github.com:khadimfall2/ProjetGNN.git
cd ProjetGNN

### 2. Environnement virtuel
Il est recommandé d'installer les dépendances dans un environnement isolé :

# Création et activation (Linux/Mac)
python -m venv env
source env/bin/activate

# Création et activation (Windows)
python -m venv env
env\Scripts\activate

### 3. Dépendances
pip install -r requirements.txt

### 4. Configuration
Assurez-vous que le fichier de données `Mondiale.P` se trouve à la racine du projet, au même niveau que le notebook Jupyter.

## Utilisation
L'analyse et les visualisations sont présentées dans un Jupyter Notebook.

1. Lancez Jupyter :
jupyter notebook

2. Ouvrez le fichier `gnncode.ipynb`.

3. Exécutez les cellules séquentiellement pour entraîner le modèle et visualiser les explications générées par GNNExplainer.

## Auteur
Khadim FALL
