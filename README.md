# Logement_eco_responsable

Contenu de l'archive

Mon archive contient les éléments suivants :

1. Dossier Base_de_donnees

Fichiers principaux :

logement.db : Base de données SQLite contenant les données du projet.

logement.sql : Script SQL pour créer et initialiser la base de données.

remplissage.py : Script Python pour remplir la base de données avec des valeurs.

2. Dossier HTML_CSS_Javascript

Contient le code pour la partie front-end du projet.

Fichiers principaux :

serveur.py : Script Python pour lancer le serveur web.

Dossier projet_logement : Contient les pages HTML et les ressources associées.

index.html : Page d'accueil.

capteurs.html, configuration.html, consommation.html, economies.html : Pages pour les différentes sections du site.

Dossier styles : Contient le fichier styles.css pour la mise en page.

Dossier images : Contient l'image logo-eco-responsable.jpg.

3. Dossier meteo

Fichier principal :

prevision_meteo.py : Script Python pour générer les prévisions météo.

4. Dossier Remplissage_et_serveurWEB

Combine les outils pour gérer la base de données et un serveur RESTful.

Fichiers principaux :

logement.db : Copie de la base de données.

requete.txt : Contient des exemples de requêtes pour le serveur.

RESTful_serveur.py : Script Python pour un serveur RESTful.

Lancer le projet

Prérequis

Installez les dépendances Python nécessaires avec la commande suivante :

pip install flask flask-cors

Lancer le serveur web

Naviguez dans le dossier HTML_CSS_Javascript.

Exécutez le fichier serveur.py avec la commande :

python3 serveur.py

Ouvrez votre navigateur et accédez à la page index.html pour interagir avec le site.

Lancer le serveur RESTful

Naviguez dans le dossier Remplissage_et_serveurWEB.

Exécutez le fichier RESTful_serveur.py avec la commande :

python3 RESTful_serveur.py

Utilisez un outil comme Postman ou cURL pour tester les requêtes RESTful en suivant les exemples donnés dans requete.txt.

Organisation du projet

Chaque dossier et fichier est clairement annoté pour indiquer à quelle partie du TP il correspond. Les explications nécessaires sont incluses directement dans les fichiers ou sous forme de commentaires.

