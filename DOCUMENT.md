---
# Practica Git/Github
---

###     1. Creo un directori de treball anomenat /DiariVostreNom/ en el directori de l'usuari. 

###   2. Inicialitzar el repositori buit.

![](https://i.imgur.com/4XOvC4J.png)

![](https://i.imgur.com/HGVjDRD.png)

###     3. Crear l'arxiu index.html 

###    4. Afegir l'estructura bàsica

:::info
<!DOCTYPE HTML>
<html>
<head> 

</head>
<body>

</body>
</html>
:::

![](https://i.imgur.com/yt0XWaf.png)

### 5. Crear un commit indicant que es crea l'esquelet bàsic del index.html 

![](https://i.imgur.com/2iqIsrf.png)

### 6. Afegir el contingut al head, entre <head> i </head>.

:::info
<meta charset="UTF-8" />
<title></title>
<link rel="stylesheet" type="text/css" href="style.css" />
<! --[if IE]>
<script src="http://html5shiv.googlecode.com/svn/trunk/html5.js"></script>
<![endif] -->
:::

### 7. Crear un commit indicant que s'afegeix la capçalera del index.html

![](https://i.imgur.com/OJIlNSU.png)

### 8. Afegir el contingut al body, entre <body> i </body>

:::info
<header>
<h1>Diari de Vostre Nom</h1>
</header>

<aside>
<p></p>
</aside>

<section>

</section>

<footer>
<p>&copy; 2012 - dissenyat per <a href="http://www.ciclesbalaguer.com" title="DiariVostreNom">VostreNom</a></p>
</footer>
:::

### 9. Crear un commit indicant que s'afegeix l'estructura bàsica del body. 

![](https://i.imgur.com/4d3Op0x.png)


### 10. Crear un repositori en GitHub que s’anomeni RemoteDiariVostreNom (exemple RemoteDiariEduardo)

![](https://i.imgur.com/jde8oE5.png)


### 11. Assignar al vostre repostiorio global el remot

:::info
Executar:
    1. git remote
    2. git remote add origin https://VOSTRE-REPOSITORI.git
    3. git remote -v
    4. Pujar amb un push tota el que heu fet a la branca master del remot.
:::

:::info
Executar:
1.	git push -o origin --all
2.	Veure Github
3.	git push -o origin --tags
4.	Veure Github
:::

![](https://i.imgur.com/JdE3yOC.png)

--- 

### 1. Afegir el contingut de section, entre section i section ( la idea és afegir al menys tres posts en la zona d’articles del vostre document). Podeu afegir notícies, articles etc...

### 2. Crear un commit indicant que s'afegeix tota l'estructura de la zona de posts.

![](https://i.imgur.com/xESKNN0.png)

### 3. Crear un arxiu style.css.

### 4. Afegir la següent informació.

:::info
html {
margin: 0;
padding: 0;
}
body {
width: 940px; 
margin: 0 acte;
font: 10pt/1.5em Helvetica,"Helvetica neue", Arial, sans-serif;
 }
:::

### 5. Crear un commit indicant que s'afegeixen les CSS d'html i de body. 

![](https://i.imgur.com/ame8Gfq.png)

### 6. Afegir la següent informació.

:::info
header,section,article,aside,footer{ 
display: block;
}

 aside {
 	float: left; width: 470px;
min-height: 480px;
background: url(logo.png) center top no-repeat;
margin: 0 0 20px 0;
}
:::

### 7. Crear un commit indicant que s'afegeixen les CSS de diversos elements HTML5: header, section, article, aside i footer. 

![](https://i.imgur.com/ZRJbjM5.png)

### 8. Afegir en el directori arrel de projecte el logotip que apareixerà en la barra lateral esquerra: logo.png ( podeu ficar la imatge que vulgueu)

![](https://i.imgur.com/Sm92c19.png)

### 9. Crear un commit indicant que s'afegeix el logotip del Vostre Diari. 

![](https://i.imgur.com/XUDhiFM.png)

### 10. Afegir la següent informació.

:::info
section {
float: right; width: 428px;
padding-left: 20px; margin: 0 0 20px 0px;
//border-left: 1px dotted #000;
}

section h2 {
font: 14pt Helvetica,"Helvetica neue", Arial, sans-serif; 
font-weight: lighter;
text-transform: uppercase; 
color: #493831;
padding-bottom: 10px; 
margin: 0;
}
:::

### 11. Crear un commit indicant que s'afegeixen les CSS de section.

![](https://i.imgur.com/HYnByBP.png)

### 12. Afegir la següent informació.

:::info
footer{
clear:both !important; 
width:940px;
height: 100px; 
padding: 10px; 
color:#200f08 ;
//border-top: 1px dotted #000; 
background:#fff;
}
:::

### 13. Crear un commit indicant que s'afegeixen les CSS del footer.

![](https://i.imgur.com/6dbL68T.png)

### 14. Afegir la següent informació.

:::info 
h1 {
font: 32pt Helvetica,"Helvetica neue", Arial, sans-serif; 
text-align: center;
text-transform: uppercase; 
color: #000;
padding-top: 30px ;
text-shadow: 1px 1px 2px #fff;
}
a:hover {
border-bottom:1px dotted #d2543c;
}

a img {
border:none;
}
:::

### 15. Crear un commit indicant que s'afegeixen les CSS de l'H1 i dels enllaços. 

![](https://i.imgur.com/mIGvhds.png)

### 16. Actualitzar la pàgina remota de forma regular fent amb l'ordre push. 
git push [nom-remot][nomeni-branca] ( és possible que tingueu que pujar mes d'una branca en algun moment de la practica)

![](https://i.imgur.com/plgVmBH.png)

### 17. Crear una etiqueta de v1.0

![](https://i.imgur.com/QAyg5WA.png)

### 18. Crear una branca “develop”.

![](https://i.imgur.com/eT0ekwb.png)

### 19. En aquesta branca de desenvolupament anem a realitzar diverses tasques: 

### 20. Crear un directori de images i moure allí el logotip logo.png.

![](https://i.imgur.com/GJrbQhh.png)

### 21. Crear un commit indicant que es mou el logotip a la carpeta images.

![](https://i.imgur.com/Rx9OYSH.png)

### 22. Crear un directori de CSS i moure allí les CSS style.css.

![](https://i.imgur.com/j8Y9gg7.png)

### 23. Crear un commit indicant que es mou la CSS a la carpeta CSS.

![](https://i.imgur.com/p9uNu7b.png)

### 24. Canviar les referències a la CSS en el index.htm i al logotip logo.png en la CSS.

### 25. Crear un commit indicant que es canvien les referències a les CSS i a les imatges al reorganitzar-les en directoris.

![](https://i.imgur.com/mg5PNrQ.png)

### 26. Actualitzar la pàgina remota de forma regular fent amb l'ordre push.

### 27. Anar al vostre repositori en Github.com i comprovar que ho teniu idèntic al vostre repositori local.

![](https://i.imgur.com/yVqNWKb.png)

---

# A GITHUB.COM:

### 28. Crear una branca “bugfix” a partir de la “master” per resoldre una sèrie de modificacions.

![](https://i.imgur.com/wbPv4yG.png)

### 29. Treure els comentaris en les CSS de les dues vores (comencen per //border ).

### 30. Crear un commit indicant que introdueixen les vores en la barra dreta i en el footer.

![](https://i.imgur.com/S6Pr5yc.png)

### 31. Introduir com a títol “Diari de Vostre Nom”.

### 32. Crear un commit indicant que s'introdueix el títol a la pàgina.

![](https://i.imgur.com/ucp0qbC.png)

### 33. Canviar 2012 per 2018 en el footer. Treure (c).

### 34. Crear un commit indicant que es realitzen petits ajustos en el footer. 

![](https://i.imgur.com/lwOsOkl.png)

### 35. Crear una etiqueta de v1.1

![](https://i.imgur.com/VFNUXhX.png)

### 36. Portar aquests canvis a la branca “master” ( realitzar un merge).

![](https://i.imgur.com/HaR0ZVo.png)

### 37. Esborrar la branca “bugfix”.

![](https://i.imgur.com/lIbHZEk.png)

### 38. Portar els canvis de la branca “develop” a la branca “master”. Resoldre els conflictes, si hi hagués. 

### 39. Crear una etiqueta de v1.2

![](https://i.imgur.com/oTYHaRP.png)


### 40. Afegir fitxer DOCUMENT.MD amb tota la pràctica, captura de pantalla, explicacions etc…També en Markdown. ( en github). Podeu triar entre elaborar-lo en local i pujar-ho a github ( ex: drag and drop) o treballar directament en l'editor de Github.

![](https://user-images.githubusercontent.com/71660913/96883879-293afb00-1481-11eb-8bbf-6f300d854277.png)
