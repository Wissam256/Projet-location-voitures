# Projet-location-voitures
Ce programme est une application de gestion d'un service de location de voitures, permettant à la fois aux administrateurs et aux clients de gérer et interagir avec les voitures disponibles.

### Description des fonctionnalités :
1. **Utilisateur : Admin**
   - L'administrateur peut gérer les voitures : ajouter, afficher, modifier, supprimer et enregistrer les voitures dans un fichier.
   - Un code de vérification est requis pour accéder aux options administratives.

2. **Utilisateur : Client**
   - Le client peut consulter la liste des voitures disponibles, rechercher une voiture par marque, et trier les voitures selon le prix de location.
   - Le client n'a pas la possibilité de modifier les voitures, mais peut rechercher et trier les véhicules.

### Fonctionnalités détaillées :
- **Ajouter des voitures** : L'administrateur peut ajouter plusieurs voitures avec des détails comme la marque, le modèle, le prix et la disponibilité.
- **Afficher les voitures** : Les informations des voitures sont affichées sous forme de liste avec les critères de disponibilité.
- **Modifier ou supprimer des voitures** : L'administrateur peut changer le prix ou la disponibilité d'une voiture, ou la supprimer complètement.
- **Rechercher des voitures** : Les clients peuvent rechercher des voitures par marque.
- **Trier les voitures** : Les voitures peuvent être triées par prix de location.
- **Enregistrer dans un fichier** : L'administrateur peut sauvegarder les informations des voitures dans un fichier texte.

Le programme utilise une interface en ligne de commande et se base sur des structures de données (`Voiture`, `Client`, `resp`) pour organiser les informations. Il fonctionne par menus où l'utilisateur (admin ou client) choisit une option à exécuter.
