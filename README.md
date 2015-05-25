# Calorie_Challenge_FR
Traduction en Français du jeu "Calorie Challenge" de Concept 2 pour les ergomètres

Ce repertoire sert à expliquer et demonstrer comment adapter et traduire le jeu C2 Calorie Challenge en français.

#Son#
Les fichiers son du jeu sont stockés dans le repertoire : 
> Concept2\C2CalorieChallenge\sounds

et sont : 

* chompchompchomp.wav -> 2 sec
* grubsup2.wav -> 6 sec
* toobad2.wav -> 4 sec
* welcomeminusUSB.wav -> 7 sec
* welcomeplusUSB.wav -> 11 sec
* welldone1.wav -> 4 sec
* whileyousetupthegame2.wav -> 5 sec

#Images#
Les images sont stockées dans les sous-dossiers de :
> Concept2\C2CalorieChallenge\images

Elles sont de largeur de 1024 pixels (différentes hauteurs) et de format .jpg.

Par défaut les noms des aliments sont : bagel, banana, fries, jbaby, jcake, pizza, salad, sausage.

#Fichier de paramétrage XML#
La configuration et incorporation des images se font via le fichier **fooditems.xml** qui se trouve directement dans le dossier 
> Concept2\C2CalorieChallenge

La structure est : 

`<C2CalorieChallenge>`

`  <challenge>`

`    <food>Jelly Baby</food>`

`    <calories>20</calories>`

`    <time>120</time>`

`    <graphic>images/jbaby/jbaby.jpg</graphic>`

`    <event target="1"   type="image" action="images/jbaby/jbaby1.jpg"></event>`

`    <event target="2"   type="image" action="images/jbaby/jbaby2.jpg"></event>`

`    <event target="3"   type="image" action="images/jbaby/jbaby3.jpg"></event>`

`    <event target="5"   type="image" action="images/jbaby/jbaby4.jpg"></event>`

`    <event target="6"   type="image" action="images/jbaby/jbaby5.jpg"></event>`

`    <event target="7"   type="image" action="images/jbaby/jbaby6.jpg"></event>`

`    <event target="8"   type="image" action="images/jbaby/jbaby7.jpg"></event>`

`    <event target="10"  type="image" action="images/jbaby/jbaby8.jpg"></event>`

`    <event target="11"  type="image" action="images/jbaby/jbaby9.jpg"></event>`

`    <event target="13"  type="image" action="images/jbaby/jbaby10.jpg"></event>`

`    <event target="14"  type="image" action="images/jbaby/jbaby11.jpg"></event>`

`    <event target="15"  type="image" action="images/jbaby/jbaby12.jpg"></event>`

`    <event target="17"  type="image" action="images/jbaby/jbaby13.jpg"></event>`

`    <event target="18"  type="image" action="images/jbaby/jbaby14.jpg"></event>`

`    <event target="20"  type="image" action="images/jbaby/jbaby15.jpg"></event>`

`  </challenge>`


`  <challenge>......`

`</C2CalorieChallenge>`
