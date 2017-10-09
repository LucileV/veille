# flexbox

## Mise en page avec flexbox

### Un conteneur, des éléments

+1 Il faut définir un conteneur et placer à l'intérieur plusieurs éléments.

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

#### aligner horizontalement : justify content

+1
