# <center>Partie Frontend de l'application web Digital Banking</center>
***
**Ce rapport présente la composante frontend de l'application web Digital Banking, qui a été développée à l'aide du framework Angular. L'application offre diverses fonctionnalités permettant de gérer les opérations bancaires en ligne. Parmi celles-ci, on retrouve la consultation des comptes, la gestion des clients ainsi que des opérations financières telles que le débit, le crédit et le transfert d'argent.**

***
This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 16.1.0.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Partie Customers
***
**La section "Clients" est subdivisée en deux parties : la consultation des clients existants et l'ajout de nouveaux clients.**

1. - Consultation des clients

Dans cette section, vous trouverez la liste des clients existants. Un champ de recherche est disponible pour filtrer les clients en fonction de mots-clés. Chaque client est affiché dans un tableau contenant des informations telles que leur identifiant, leur nom et leur adresse e-mail. Deux boutons sont disponibles pour supprimer le client ou accéder à ses comptes.

<img src="Pictures/picture1.png">

***
1. 2. - Recherche des clients par mot clé

<img src="Pictures/picture2.png">

***
1. 3. - Supprimer le Client 

<img src="Pictures/picture3.png">

***
1. 4. - Ajout de nouveaux clients

**Cette section permet l'ajout de nouveaux clients à l'application. Un formulaire est présenté, comprenant les champs obligatoires tels que le nom et l'e-mail. Des validations sont appliquées aux champs afin de garantir l'exactitude des données saisies. L'utilisateur peut enregistrer le nouveau client en cliquant sur le bouton "Enregistrer".**
- Les requis

  <img src="Pictures/picture4.png">
***
- L'ajout

  <img src="Pictures/picture5.png">
***
2. - Comptes bancaires et opérations

La section des comptes bancaires permet à l'utilisateur de consulter les informations détaillées d'un compte spécifique ainsi que d'effectuer des opérations financières.

Cette partie affiche les détails du compte bancaire spécifié, y compris l'ID du compte et le solde actuel. Elle liste également les opérations effectuées sur le compte, affichant leur ID, la date, le type et le montant.

<img src="Pictures/picture6.png">

