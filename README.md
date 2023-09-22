# Thymeleaf Google Login

Ce projet est une démonstration simple de l'authentification via Google OAuth2 dans une application web utilisant Thymeleaf.

## Aperçu

Cette application web montre comment intégrer l'authentification via Google OAuth2 dans une application Thymeleaf. Elle permet aux utilisateurs de s'authentifier avec leur compte Google et d'accéder à des fonctionnalités protégées.

## Fonctionnalités

- Authentification via Google OAuth2.
- Page d'accueil avec un lien de connexion Google.
- Page protégée accessible uniquement aux utilisateurs authentifiés.

## Installation

1. Clonez le repository :

   ```bash
   git clone https://github.com/IronNetta/thymeleaf-google-login.git
   cd thymeleaf-google-login
2. Configurez votre projet sur la [console Google Developers](https://console.developers.google.com/). Obtenez les identifiants OAuth2 et configurez les variables d'environnement `GOOGLE_CLIENT_ID` et `GOOGLE_CLIENT_SECRET` dans votre application. Vous pouvez également spécifier un fichier `application.properties` pour les configurations.

3. Exécutez l'application : 

## Utilisation

1. Accédez à l'application dans votre navigateur à l'adresse [http://localhost:8080](http://localhost:8080).

2. Cliquez sur "Se connecter avec Google" pour initier le processus d'authentification OAuth2.

3. Une fois authentifié avec succès, vous serez redirigé vers la page d'accueil protégée.

## Contribuer

Les contributions à ce projet sont les bienvenues. Si vous souhaitez contribuer, suivez ces étapes :

1. Fork du projet.
2. Créez une branche pour votre contribution (`git checkout -b ma-contribution`).
3. Faites vos modifications.
4. Commit et poussez vos modifications (`git commit -m "Ajout de ma contribution"`, `git push origin ma-contribution`).
5. Créez une demande d'extraction (pull request) vers la branche principale du projet.

## Licence

Ce projet est sous licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus de détails.
