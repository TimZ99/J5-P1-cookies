# J5-P1-cookies
Deze website is gemaakt voor de eerste periode informatica van jaar 5.

De website is gemaakt met [Bootstrap (3.3.5)](https://getbootstrap.com).

## Menu item toevoegen
```html
<li class="">  
<a class="page-scroll" href="#   vul hier het ID van de <section> in   " style="color: #FFFFFF">   Vul hier in wat er in de menu balk als naam moet staan.   </a> 
</li>
   ```
## Section (nieuw kopje) toevoegen
```html
<section id="   Vul hier het nieuwe id van de section in (als er een knop in de navigatiebalk staat die naar dezze section verwijst moet het id ook daar worden ingevuld   " class="container content-section">
<div class="row">
<div class="col-lg-8 col-lg-offset-2">
<br><br>
<h2>typ hier de titel</h2>
<p style="text-align: justify;">
Typ hier de tekst.
</p>

</div>
</div>
</section>
```

## Style
De pagina is in 12 verticale vakken verdeeld.
```html
<div class="col-xs-12 col-sm-12 col-lg-12">
</div>
```
**Dit betekend:**

col-xs-12, op telefoon 12 vakjes breed, dus volledige breedte.

col-sm-12, op tablet 12 vakjes breed, dus volledige breedte.

col-lg-12, op computer 12 vakjes breed, dus volledige breedte.

Door het getal aan te passen kan de breedte van de div aangepast worden. 


### Voorbeeld
```html
<div class="col-xs-12 col-sm-12 col-lg-12">
    <div class="col-xs-12 col-sm-6 col-lg-6">
    </div>
    <div class="col-xs-12 col-sm-6 col-lg-6">
    </div>
</div>
```
Bij bovenstaande voorbeeld zitten er in de div nog 2 div's. Deze div's zijn vullen op de computer en op de tablet de helft van de div waar ze instaan. Op telefoon komen de 2 div onder elkaar te staan en vullen ze de gehele breedte, dit om te zorgen dat de inhoud van de div goed zichtbaar blijft op kleine apparaten.
