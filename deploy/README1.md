Vous avez mis à jour votre workflow pour générer et déployer l’application de votre site web sur l’application Azure App Service définie dans votre fichier Bicep. Toutefois, le travail de test de détection de fumée échoue, car la base de données ne fonctionne pas encore. Dans cette unité, vous allez déployer une nouvelle base de données et un nouveau serveur logique Azure SQL, et vous allez configurer votre workflow pour générer et déployer le schéma de la base de données. Vous allez également mettre à jour votre workflow pour ajouter des exemples de données de produits pour votre environnement de test, afin que votre équipe puisse essayer le site web.

Pendant ce processus, vous allez :

Ajouter un conteneur d’objets blob dans le compte de stockage Azure.
Ajouter une base de données et un serveur logique Azure SQL.
Mettre à jour le travail de génération pour générer le projet de base de données dans un fichier DACPAC.
Ajoutez de nouvelles variables et de nouveaux secrets pour la base de données et le serveur logique Azure SQL.
Mettez à jour votre workflow pour utiliser les nouvelles variables et les nouveaux secrets.
Ajouter de nouvelles étapes de workflow pour déployer votre fichier DACPAC.
Exécutez le workflow et affichez le site web.