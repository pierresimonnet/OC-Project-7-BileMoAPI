[![Codacy Badge](https://api.codacy.com/project/badge/Grade/a8a53bc40db64af89260c583062c9b3d)](https://www.codacy.com/manual/bashokusan/P7?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=bashokusan/P7&amp;utm_campaign=Badge_Grade)

# BileMo API

## BileMo est une entreprise offrant toute une sélection de téléphones mobiles haut de gamme.
### Offre : Fournir à toutes les plateformes qui le souhaitent l’accès au catalogue via une API

#### Besoins :

* Consulter la liste des produits BileMo
* Consulter les détails d’un produit BileMo
* Consulter la liste des utilisateurs inscrits liés à un client sur le site web
* Consulter le détail d’un utilisateur inscrit lié à un client
* Ajouter un nouvel utilisateur lié à un client
* Supprimer un utilisateur ajouté par un client

#### Contraintes :

* Seuls les clients référencés peuvent accéder aux API
* Niveaux 1, 2 et 3 du modèle de Richardson
* Données en JSON.
* Réponses mises en cache

## Documentation : 

La documentation de l'API est disponible sur domaine/doc

## Installation

* Cette application a été développée avec le framework [Symfony](https://symfony.com/)
1. Cloner le projet pour installer son contenu
```
cd projects/
git clone https://github.com/bashokusan/P7.git
```
2. Utiliser Composer pour installer les dépendances dans le dossier vendor
```
cd P7/
composer install
```
3. Créer la database
```
bin/console doctrine:database:create
```
4. Importer les tables dans la database
```
bin/console doctrine:migrations:migrate
```
