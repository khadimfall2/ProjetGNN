# ProjetGNN

# ProjetGNN

GNNExplainer: Visualisation des Explications
d’un GNNExplainer sur un Réseau de Neurones
Graphique

Présentation 

Ce projet vise à explorer et à visualiser les explications fournies par
GNNExplainer, une méthode innovante permettant d’interpréter les prédictions
des modèles basés sur les réseaux neuronaux graphiques (GNN) appliqués
à des ensembles de données structurées en graphe. Les GNN sont de-
venus des outils essentiels pour analyser et prédire sur des données com-
plexes telles que les réseaux sociaux, les molécules chimiques et les réseaux
de transport. Cependant, ces modèles souffrent souvent d’un manque
d’interprétabilité, ce qui limite leur adoption dans des domaines où la
transparence et la compréhension des décisions sont cruciales.
Dans ce travail, nous utilisons GNNExplainer pour identifier les struc-
tures de sous-graphe et les caractéristiques de nœuds les plus importantes
qui contribuent aux prédictions des modèles GNN. En appliquant cette
méthode à un ensemble de données spécifique, nous générons des explica-
tions interprétables pour chaque instance de graphe, mettant en évidence
les motifs et les attributs clés utilisés par le modèle pour prendre des
décisions. Nous formulons ce processus comme une tâche d’optimisation
visant à maximiser l’information mutuelle entre les prédictions du modèle
GNN et les distributions des structures de sous-graphe possibles.
À l’aide d’expériences sur des ensembles de données réels, nous démontrons
l’efficacité de GNNExplainer dans l’identification des structures de graphe
importantes et des caractéristiques de nœuds influentes. De plus, nous
proposons une méthode de visualisation pour rendre ces explications compréhensibles,
permettant aux utilisateurs de mieux comprendre le fonctionnement des
modèles GNN et les décisions qu’ils prennent. Ces résultats ouvrent de
nouvelles perspectives pour l’interprétabilité des modèles GNN et leur
application dans des domaines où la transparence est primordiale.



Installation
1 Cloner le dépôt
Clonez le dépôt GitHub en utilisant la commande suivante :
git clone  [lien du dépôt]


2 Préparer l'environnement
Assurez-vous d'avoir Python installé sur votre système. Il est recommandé d'utiliser un environnement virtuel pour éviter les conflits de dépendances. Vous pouvez créer un environnement virtuel avec venv :

python -m venv env
source env/bin/activate  # Sur Windows, utilisez `env\Scripts\activate`


3 Installer les dépendances
Installez les dépendances requises en utilisant le fichier requirements.txt (assurez-vous qu'il est présent à la racine du dépôt). Si ce fichier n'existe pas, vous devrez installer les bibliothèques nécessaires manuellement.
pip install -r requirements.txt

4 Configurer les données
Assurez-vous que le fichier dataset Mondiale.P et le code source soit dans le meme dossier ou bien  ajoutez l’extension du dataset Mondiale.P au code source  . Le fichier doit être structuré correctement pour que le code puisse l'utiliser.
Le dataset Mondiale.P contient les pays et leurs caractéristiques socio-économiques et démographiques, structuré sous forme de graphe   dont les nœuds représentent les pays et arêtes les frontières entres les pays . 

5 Exécuter le code
Vous pouvez maintenant exécuter le code en utilisant le fichier Jupyter Notebook situé dans le dossier. Lancez Jupyter Notebook et exécutez  le fichier gnncode.ipynb  

Utilisation

Après avoir installé toutes les dépendances et configuré les données, vous pouvez utiliser le code de plusieurs manières. Voici comment procéder :
1. Lancer Jupyter Notebook

Pour commencer à travailler avec le code, lancez Jupyter Notebook :

bash

jupyter notebook

Cela ouvrira Jupyter Notebook dans votre navigateur web. Naviguez jusqu'au fichier gnncode.ipynb situé dans le dossier src et ouvrez-le.
2. Exécuter le Code

Une fois le notebook ouvert, vous pouvez exécuter les cellules une par une en appuyant sur Shift + Enter, ou utiliser le menu "Run" pour exécuter toutes les cellules en séquence. Assurez-vous que le dataset Mondiale.P est correctement chargé et accessible dans le notebook.
3. Analyser les Résultats

Après l'exécution des cellules, vous pourrez visualiser les résultats dans le notebook. Les sorties des cellules devraient fournir des insights sur les analyses effectuées par le code.


Contribution

Les contributions sont les bienvenues ! Si vous souhaitez contribuer au développement du projet, veuillez suivre ces étapes :

    Forker le dépôt : Créez une copie personnelle du dépôt en utilisant le bouton "Fork" sur GitHub.
