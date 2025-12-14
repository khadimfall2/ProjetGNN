# GNNExplainer – Explicabilité des Réseaux de Neurones Graphiques


## Contexte et objectifs


Les **Graph Neural Networks (GNN)** sont aujourd’hui largement utilisés pour modéliser des données structurées sous forme de graphes (réseaux sociaux, données géographiques, molécules, réseaux de transport, etc.). Malgré leurs performances, ces modèles souffrent d’un **manque d’interprétabilité**, ce qui limite leur adoption dans des contextes sensibles ou décisionnels.


L’objectif de ce projet est d’étudier et de mettre en œuvre **GNNExplainer**, une méthode d’explicabilité permettant d’identifier :
- les **sous-graphes les plus influents** dans une prédiction,
- les **caractéristiques de nœuds** déterminantes pour la décision du modèle.


Le projet s’inscrit dans un cadre **académique et de recherche**, en collaboration avec un laboratoire, et vise à fournir une analyse claire, reproductible et interprétable des prédictions d’un GNN.


---


## Problématique abordée


À partir d’un jeu de données structuré sous forme de graphe (pays comme nœuds, frontières comme arêtes, variables socio-économiques et démographiques comme attributs), nous cherchons à :


- entraîner un modèle GNN pour une tâche de **classification**,
- analyser les décisions du modèle à l’aide de **GNNExplainer**,
- identifier et visualiser les **variables et relations les plus influentes**,
- fournir une interprétation statistique et graphique des résultats.


⚠️ Le projet met volontairement l’accent sur la **méthodologie, l’explicabilité et l’analyse**, et non sur l’usage applicatif final.


---


## Méthodologie


1. **Préparation des données**
- Construction d’un graphe à partir des pays (nœuds) et de leurs frontières (arêtes)
- Normalisation et sélection des variables


2. **Modélisation GNN**
- Implémentation d’un réseau de neurones graphique
- Entraînement et évaluation des performances


3. **Explicabilité avec GNNExplainer**
- Extraction des sous-graphes explicatifs
- Calcul de masques sur les nœuds et les arêtes
- Analyse de l’influence des variables


4. **Analyse et visualisation**
- Visualisation des sous-graphes explicatifs
- Interprétation statistique des décisions du modèle


---


## Technologies utilisées


- **Langage** : Python
- **Deep Learning** : PyTorch, PyTorch Geometric
- **Graph Learning** : GNN, GNNExplainer
- **Analyse de données** : NumPy, Pandas
- **Visualisation** : Matplotlib, NetworkX
- **Environnement** : Jupyter Notebook


---


## Installation


### 1. Cloner le dépôt


```bash
git clone git@github.com:khadimfall2/ProjetGNN.git
cd ProjetGNN
