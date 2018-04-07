# TP7 Angular-Js
TP7 de SIR, Le but de ce TP est de construire à partir de vos compétences en AngularJS une interface Web pour votre application développée en Java côté serveur.  <br />
portant sur les technologies suivantes:
Front-end:
- Yeoman et son générateur de projet angularjs
- AngularJS
- Bower
- npm (NodeJS)

Back-end:
- Jersey ou JAX-RS pour architecture Java REST
- Hibernate (JPA) pour l'utilisation d'une base de données

## Installation

1) Cloner le projet.
2) Importer les dépendences et construire le projet:  <br />
   > ``` cd path-to-workspace/tpangular``` <br />
   > ``` npm install ``` <br />
   > ``` bower install ```  <br />
3) Modifier le fichier **persistence.xml** pour qu'il corresponde à votre base de données.
4) Exécuter **tpangular/test/java/fr/istic/sir/jpa/JpaTest.java** pour alimenter la base de données.


## Lancement

### Partie serveur (back-end)
- Serveur Tomcat 7 :
  > ``` Tp2_4 Sir run ``` <br />
  > ``` mvn tomcat7:run```

### Partie Client (front-end)
Dans un autre terminal:
- Serveur web Grunt: 
   > ``` cd path-to-workspace/tpangular``` <br />
   > ``` grunt serve```


## API REST

La racine est */*.

| Method     | URL | Action   |
| :------- | ----: | :---: |
| GET    | /homes  |  affiche toutes les maisons   |
| DELETE    | /homes/{id}  |  supprime une maison   |
| POST    | /homes  |  ajoute une maison   |
| GET    | /persons  |  affiche toutes les personnes   |
| DELETE    | /persons/{id}  |  supprime une personne   |
| POST    | /persons  |  ajoute une personne   |
| GET    | /devices  |  affiche tous les devices   |
| DELETE    | /devices/{id}  |  supprime un device   |
| POST    | /devices  |  ajoute un device   |
