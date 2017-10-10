# flexbox

## Mise en page avec flexbox

### Un conteneur, des éléments

1. Il faut définir un conteneur et placer à l'intérieur plusieurs éléments.

![flexbox container](images/flexbox_conteneur.png)

    <div id="containeur">
      <div class="element">Elément 1</div>
      <div class="element">Elément 2</div>
      <div class="element">Elément 3</div>
    </div>
![sans flex](images/sansFlex.png)    

#### Rajoutons du flex
dans le css on cible le parent (le container)
    #container{
      display:flex;
    }
![avec flex](images/avecFlex.png)

2. Les exemples
  + Dossier flexbox-playground pour tester en direct
  + Le fichier index.html :exemple simple
  + Liens/cours en ligne :
    + [S'entrainer avec une grenouille](http://flexboxfroggy.com/)
    + [Guide Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
    + [Cours de openclassrooms](https://openclassrooms.com/courses/apprenez-a-creer-votre-site-web-avec-html5-et-css3/la-mise-en-page-avec-flexbox)
    + [w3schools](https://www.w3schools.com/css/css3_flexbox.asp)
    + [codepen](https://codepen.io/enxaneta/pen/adLPwv?q=flexbox&limit=all&type=type-pens)
