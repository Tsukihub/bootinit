
Skip to content
This repository

    Pull requests
    Issues
    Gist

    @Tsukihub

0
0

    0

Tsukihub/bootinit
Code
Issues 0
Pull requests 0
Projects 0
Wiki
Pulse
Graphs
Settings
bootinit/bootstrap.md
f6ab2e7 on 13 Jan
@Tsukihub Tsukihub notice pas finie
160 lines (117 sloc) 4.56 KB

http://www.opentuto.com/installation-de-bootstrap-3/
http://www.opentuto.com/premiere-page-html-avec-bootstrap-3/
http://www.opentuto.com/comprendre-le-concept-de-grille-dans-le-webdesign/
http://www.opentuto.com/creer-page-web-multigrille-bootstrap-3/
http://www.opentuto.com/decaler-les-elements-dune-grille/ http://www.opentuto.com/imbriquer-plusieurs-grilles-dans-bootstrap-3/
http://www.opentuto.com/imbriquer-plusieurs-grilles-dans-bootstrap-3/
http://www.opentuto.com/laffichage-multiligne-dans-bootstrap-3/
http://www.opentuto.com/afficher-cacher-du-contenu-bootstrap-3-en-fonction-du-support/
http://www.opentuto.com/typographie-titres-et-paragraphes/
http://www.opentuto.com/les-messages-dinformation-dans-bootstrap-3/
http://www.opentuto.com/les-icones-bootstrap-3/
Bootstrap fichiers à disposition sur le cloud.
.min.css ficher optimisé avec espace retirés
on ne modifie pas bootstrap
créer feuille de style pour ne pas perdre ses modif à la maj
fichier jquery au dessous boot
fichier js en dessous
js perso en dessous
idem pour css qui se réalise aussi dans l'ordre
plugin avec sublime txt autocomplémentation de bootstrap

12 colonnes
une ligne div de classe .row
gutter x 11 espace plus ou moins grand défini automatiquement par bootstrap
23 espaces
la div prendra 8 colonnes sans toucher au css

disposition

<div class="row">  
<div class="col-md-x"></div>  
<div class="col-md-y"></div>  
</div>  

où x+y=12 pour rester sur même ligne, sinon passe automatiquement à la ligne
changer nb col func taille screen

<div class="col-md-10 col-sm-8 col-xs-6"> ... </div>  

md: medium
sm: small
xs: extra small
lg: large
espacer de x col

génère un espace de deux colonnes

quand on spécifie une talle en col ou % on part toujours de 12 ou 100% = parent

on le touche pas au postionnement sur la feuille de style perso
changer ordre

.col-md-push-* et .col-md-pull-*
affichage multiligne

dans div row quand >12 col à la ligne auto
masquer afficher

visible.x hidden.x

où x est : md: medium
sm: small
xs: extra small
lg: large
bordure

<div class="col-md-4 col-xs-6 bordure"> 

align txt

<p class="text-left"
<p class="text-center">
<p class="text-right">

citation

<blockquote> 
"Identify your problems but give your power and energy to solutions." 
<small>Tony Robbins</small> 
</blockquote>

alt tag
contenu dans titi cadre

<div class="well .well-sm">Nullam ultricies ligula vehicula, laoreet urna pharetra, aliquam dui. Vestibulum sit amet venenatis mauris.</div>

text gras

<p class="lead">

messages info

<p class="text-muted">   Classe muted - Gris</p> 
<p class="text-primary"> Classe primary - Bleu pâle</p> 
<p class="text-success"> Classe success - Vert</p> 
<p class="text-info">    Classe info - Bleu</p> 
<p class="text-warning"> Classe warning - Orange</p> 
<p class="text-danger">  Classe danger - Rouge</p>

alt tag

Bandeau d’alerte - la classe success

Bandeau d’alerte - la classe info

Bandeau d’alerte - la classe warning

Bandeau d’alerte - la classe danger

alt tag

rq: js dans head et body essayer de comprendre pk
Badges

<a href="#">Messages non lus<span class="badge">2</span></a>

modifier .badge ds css boot to edit badge's style
icones

<h1><span class="glyphicon glyphicon-arrow-right"></span> Les  ic&ocirc;nes </h1> 

<h1><span class="glyphicon glyphicon-envelope"></span> Contact </h1> 

<p><span class="glyphicon glyphicon-home"></span> Accueil</p>     

<span class="label label-primary"><span class="glyphicon glyphicon-comment"></span> 3 commentaires</span>     </br></br>

<button class="btn btn-warning"><span class="glyphicon  glyphicon-shopping-cart"></span> Ajouter au panier</button>    </br></br>

<p class="text-warning lead"><span class="glyphicon  glyphicon-warning-sign"></span> Classe warning</p>

Réseaux sociaux: ==============================================

qui se link

<link href="css/bootstrap.css" rel="stylesheet"> 
<!-- Chargement de la feuille de style Font Awesome (font-awesome.min.css).-->
<link href="css/font-awesome.min.css" rel="stylesheet">

    Contact GitHub API Training Shop Blog About 

    © 2017 GitHub, Inc. Terms Privacy Security Status Help 


