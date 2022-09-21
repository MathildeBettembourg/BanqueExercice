# BanqueExercice
# Projet première réunion avec un client : La banque de France

## Objectif

Créer une application java qui permet de gérer les comptes bancaires d'une banque et ses clients.
Cette application permettra également de gerer les transactions bancaires.

## Entités

Une banque est composée de plusieurs agences, chaque agence regroupe des clients et des comptes bancaires.
Il existe trois types de comptes bancaires : Compte courant, Compte épargne, Compte Rémunéré. 
Il existe trois type de personnes : Client, Conseiller Bancaire, Directeur de la Banque.

Fonctionnalités du client :
- retrait d'argent (si le solde est suffisant ou qu'il est dans son découvert)
- versement d'argent
- affichage de son solde

Futur fonctionnalité du client :
- virement d'argent

Fonctionnalités du conseiller bancaire :
- tous ce que peut faire un client
- ouverture de compte
- fermeture de compte
- gestion des clients (ajout, suppression, modification)

Fonctionnalités du directeur de la banque :
- tous ce que peut faire un conseiller bancaire
- gestion des agences (ajout, suppression, modification)
- gestion des conseillers bancaires (ajout, suppression, modification)

L'application sera en ligne de commandes !
Pas de sauvegarde en dehors de l'application pour le moment.

## Lot 1 :

- Diagramme de classe

## Banque version 1.0

Un client peut avoir plusieurs type de comptes (courant, épargne, rémunéré) et peut déposer de l'argent et en retirer

## Banque version 1.1

Le client à des contrôles sur son compte (découvert,)

## Banque version 2.0

On retrouve les opérations du clients mais aussi celles du conseiller bancaire. Le conseiller peut ouvrir un compte, fermer un compte, gérer les clients (ajout, suppression, modification).
Le conseiller se connectera à l'application avec un login et un mot de passe. Le conseiller aura un identifiant unique.

## Banque version 3.0

On retrouve les opérations du conseiller bancaire mais aussi celles du directeur de la banque. Le directeur se connectera à l'application avec un login et un mot de passe. Le directeur aura un identifiant unique.
Le directeur peut gérer les agences (ajout, suppression, modification) et les conseillers bancaires (ajout, suppression, modification).

