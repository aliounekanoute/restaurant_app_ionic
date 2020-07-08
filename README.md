# Ionic application

# Projet: développement d'une application pour restaurant avec IONIC

## Auteur : Alioune Harouna Kanoute. 

## Classe : Master 2 GLSI


#### *Cette application va consommer l'API restaurant_app_strapi*

## Objectifs
Il nous est demandé de développer une application mobile avec ionic qui permet : 

```
- aux utilisateurs de passer des commandes
- au gérant du restaurant de gérer les commandes, les plats et le menu du jour.
```

## Fonctionnalités
#### Côté admin
```
- Connexion et déconnexion
- Ajouter, modifier, lister, supprimer des plats
- Définir le menu du jour
- Voir les commandes du jour et l'historique des commandes
- Modifier ses informations personnelles (nom, prénom, téléphone et sa photo de profil)
```

#### Côté utilisateur
```
- Inscription, Connexion et déconnexion 
- Voir liste des plats 
```
#### Et s'il est connecté :
```
- Passer une commande
- Annuler une commande
- Voir son historique de commandes
- Modifier ses informations personnelles (nom, prénom, téléphone et sa photo de profil)
```

#### Télécharger le projet et installer les dépendances avec la commande suivante
```
> npm install
```

##### NB: Pour changer l'adresse de l'API (repository restaurant_app_strapi), ouvrir le projet, aller dans ```src/environments/environment.ts``` et changer la valeur de la variable ```API_URL```

#### Lancer l'application avec la commande 
```
> ionic serve
```
