# Gestion de Stock - Front

## Objectif

L'objectif du travail est la mise en place d'une application Android permettant de consommer une web API pour la gestion de stock.
Cette web API sera développé en Spring Boot.
Le but du serveur et de gérer les articles et les catégories d'une entreprise.
Pour simplifier notre cas nous allons travailler sur une base de mémoire H2.

<p align="middle">
  <img src="https://user-images.githubusercontent.com/65272079/154544290-0b1e2183-bcb0-4c8b-a714-eb3953e3c987.png" height="300px"/>
</p>

## Application

### Page des catégories

Les 4 catégories de l'application sont :

<p align="middle">
  <img src="https://user-images.githubusercontent.com/65272079/154689407-ad26fd8f-c041-4eb7-8926-d859f6e1feb3.png" height="100px"/>
  <img src="https://user-images.githubusercontent.com/65272079/154689309-2ecb179a-455b-4652-8007-e9bbfc3232ff.png" height="100px"/>
</p>
<p align="middle">
  <img src="https://user-images.githubusercontent.com/65272079/154689339-1bce103e-acb7-480c-a21c-d56cd29bc34a.png" height="100px"/>
  <img src="https://user-images.githubusercontent.com/65272079/154689364-8c7a6feb-9964-4149-b553-2e8e5c73a5d5.png" height="100px"/>
</p>

On affiche une liste des différents articles pour chaque catégorie dans le tableau. L'application calcule aussi le nombre d'articles ainsi que la somme des prix unitaires.

<p align="middle">
  <img src="https://user-images.githubusercontent.com/65272079/154689234-ac95abe6-e60d-49a8-8865-199c20e83b4e.png" height="500px"/>
  <img src="https://user-images.githubusercontent.com/65272079/154689136-066b1555-7509-4792-a16e-10b5e9b3d92e.png" height="500px"/>
  <img src="https://user-images.githubusercontent.com/65272079/154689179-64c452a9-1667-4d5c-bdae-649ad0d41ad6.png" height="500px"/>
</p>

### Page pour ajouter un article

On peut ajouter un article en cliquant sur le bouton « ajouter un article », puis on se dirige vers une nouvelle page. On mentionne le nom et le prix de l’article ajouté. L’article s’ajoute dans le tableau de la catégorie.

<p align="middle">
  <img src="https://user-images.githubusercontent.com/65272079/154691468-39a003fe-6516-4630-b5c1-c3ca2ef908f5.png" height="500px"/>
  <img src="https://user-images.githubusercontent.com/65272079/154691585-6d36efb1-59fd-435d-8d21-657f7c617416.png" height="500px"/>
  <img src="https://user-images.githubusercontent.com/65272079/154691663-c4807c18-8c4f-481d-93d2-dbe8a00ea422.png" height="500px"/>
</p>


