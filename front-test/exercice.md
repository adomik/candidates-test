### Création d'une mini App

- Le but de cet exercice est de voir si tu es à l'aise avec les principes fondamentaux de React et Typescript avec des use cases que l'on peut retrouver sur notre app. Il n'est pas obligatoire de finir complètement le test, l'objectif étant de nous montrer comment tu codes et comment tu organises ton projet.

## Il y a 2 apis (voir README.md pour lancer le serveur)

- /api/components: liste des produits à instancier dans l'app + liste déroulante du dropdown

- /api/users: liste des utilisateurs

## Prérequis

1 - utilisation de react et de typescript

2 - utilisation libre des outils et librairies

## Bonus

1 - styliser la page

2 - possibilité de trier par ordre alphabétique/alphanumérique chaque colonne du composant Table

## A implémenter

1 - créer deux pages accessibles depuis une navbar (une page par produit : voir clé product dans components.json pour le nom des produits). NB: le mockup n'affiche pas la navbar, tu peux la positionner où tu le souhaites

2 - créer les composants suivants: Form, Dropdown, Search, Table

3 - il y a une particularité avec le dropdown, la liste deroulante à afficher se trouve dans un objet data qu'il faut recuperer lorsque la page est créée dynamiquement

4 - le composant search tri les résultats sur le nom et/ou le prénom, et le composant Dropdown tri sur la ville

5 - le composant form doit englober les composants suivants: dropdown, search ainsi que le bouton de soumission

6 - par default le composant table affichera "no data" si il n'y a aucune donnée ou si le filtre ne renvoie aucun résultat

7 - en soumettant le formulaire j'obtiens le résulat de ma recherche dans le composant Table
