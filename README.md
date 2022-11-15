# Déploiement d'un site d'évaluation de restaurants (Flask + PostgreSQL)

  1.Créer une application web + bdd dans le portail Azure, et remplir les différents champs dans la fenêtre de dialogue, en particulier:
    Pile d'exécution = Python 3.9
    Plan d'hébergement = base
    moteur de base de données = PostgreSQL - Serveur Flexible
  
  2.Créer un répertoire et effectuer un fork du dépôt à l'adresse suivante : https://github.com/Azure-Samples/msdocs-flask-postgresql-sample-app.
  
  3.Dans la page "App Service", sélectionner "Centre de déploiement". Dans "Source" sélectionner "GitHub". Dans "Organisation", sélectionner votre compte, dans "Dépôt", "msdocs-flask-postgresql-sample-app", dans "Branche", "Main". Enregistrer.
  
  4. Dans la page "App Service", sélectionner "SSH" à gauche. Lancer une sessions SSH. Executer la commande "flask db upgrade", puis quiiter la session.
  
  5.L'application est prêt
