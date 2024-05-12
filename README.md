# Booki
### OpenClassrooms P3 - Création de la page d'accueil d'une agence de voyage avec HTML & CSS

**Booki** est un **site Internet** qui permet aux usagers de **trouver des hébergements** et des activités dans la ville de leur choix.
L'objectif est d'**intégrer l'interface** du site avec du code **HTML et CSS**, à partir de maquettes Figma.

Mon site est visible sur : [Booki](https://nour86.github.io/Ohmyfood/)

## Spécifications fonctionnelles
* Les usagers pourront **rechercher des hébergements dans la ville de leur choix** avec un champ de recherche, dans lequel ils peuvent saisir une ville *(recherche non fonctionnelle – première version pour valider l'interface)*

* **"Hébergements"** et **"Activités"**, situés sur le **menu** dans l'en-tête, sont des **liens**. Ils mènent respectivement vers la section "Hébergements à Marseille" et "Activités à Marseille".

* **Chaque carte d'hébergement** ou **d'activité** est **cliquable** dans son intégralité.

* Les hébergements pourront être **filtrés** par thématiques, comme le budget ou l'ambiance. Les filtres changent de **couleur** au **survol** de la souris. *(filtres non fonctionnels – première version pour valider l'interface)*

## Spécifications techniques
* Trois **maquettes** ont été réalisées : **desktop**, **tablette** et **mobile**.
* Les **breakpoints** ont été définis tel quels:
  * \> 1024px pour les écrans d'ordinateur
  * \>= 768 px pour les tablettes
  * \< 768px pour les téléphones portables
* **Largeur maximum** de **1440px**
* **Largeur minimum** de **320px** *(en-deça, le comportement n'est pas garanti)*
* L'intégration a d'abord été réalisée pour les ordinateurs (**desktop-first**), puis les tablettes et enfin les téléphones, en utilisant les **Media Queries**.
* Les icônes proviennent de la bibliothèque [Font Awesome](https://fontawesome.com/docs/web/setup/get-started)
* Les couleurs de la charte sont le **bleu (#0065FC)**, le **bleu clair (#DEEBFF)** et le **gris** pour le
fond **(#F2F2F2)**.
* La police du site est [Raleway](https://fonts.google.com/specimen/Raleway)
* La mise en page est réalisée avec **Flexbox**
* Utilisation des **balises sémantiques** : *header*, *nav*, *h1/h2/h3*, *main*, *section*, *article* et *footer*
* Le code passe les **validateurs W3C** [HTML](https://validator.w3.org/) et [CSS](https://jigsaw.w3.org/css-validator/)

## Tester le projet

Clonez le projet
```terminal
git clone https://github.com/nour86/Ohmyfood.git
```
Installez les dépendances
```terminal
npm install
```
Et lancez le serveur !
```terminal
npm start
```
