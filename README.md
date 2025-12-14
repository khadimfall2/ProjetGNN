# 🧠 GNNExplainer : Explicabilité des Réseaux de Neurones Graphiques

Ce projet vise à explorer et visualiser les explications fournies par **GNNExplainer**, une méthode innovante permettant d’interpréter les prédictions des modèles basés sur les Graph Neural Networks (GNN).

Les GNN sont puissants pour analyser des structures complexes (réseaux sociaux, molécules), mais souffrent souvent d'un effet "boîte noire". Ce projet implémente une solution pour rendre ces décisions transparentes.

## 🎯 Objectifs du projet

* **Interprétabilité :** Identifier les sous-graphes et les caractéristiques de nœuds (features) qui influencent le plus la prédiction du modèle.
* **Optimisation :** Maximiser l'information mutuelle entre la prédiction du GNN et la distribution des sous-graphes potentiels.
* **Visualisation :** Générer des représentations graphiques claires des "motifs" décisionnels retenus par le réseau.

## 🌍 Le Jeu de Données (Dataset)

Le projet s'appuie sur le dataset **`Mondiale.P`** (format Pickle).
* **Type de graphe :** Graphe géopolitique et socio-économique.
* **Nœuds :** Pays du monde.
* **Arêtes (Liens) :** Frontières terrestres partagées entre les pays.
* **Attributs :** Caractéristiques socio-économiques et démographiques par pays.

## 🛠️ Installation

Suivez ces étapes pour configurer l'environnement de développement local.

### 1. Cloner le dépôt
```bash
git clone git@github.com:khadimfall2/ProjetGNN.git
cd ProjetGNN
