# LM
## Estructura mínima de una web  
```html
<!DOCTYPE html>
	<html>
	<head>
		<title></title>
	</head>
	<body>
  
	</body>
	</html>
```
  ## Explica las 3 fromas de usar CSS en  HTML  
  
//CSS interno
```html
<style type="text/CSS">
```
//CSS externo
```html
<link rel="stylesheet" type="text/css" href="index.css" />
```
//CSS embebido
```html
<p>¡Hola <span style="color:#FF0000">amigo lector</span>!</
```
## Crea una lista sense irdenar amb 5 ingredients d'una recepta de cuina  
```html
<!DOCTYPE html>
<html>
	<head>
		<title>Receta Rubén</title>
	</head>
	<body>
		<ul>
			<li>Solomillo(230g)</li>
			<li>Conejo(176g)</li>
			<li>Redondo de ternera(13g)</li>
			<li>Albondigas(199g)</li>
			<li>Solomillo de cerdo(55g)</li>
		</ul>
	</body>
</html>
```
## Com es pot incluir javascript en HTML  
```html
<script type="text/javascript">
            function alerta() {
                alert('hola mundo!');
```
## Quina diferencia hi ha entre una classe i un ID  

Que el ID es un elemento unic  i en la classe podem aplicar a mes de una.
El ID es posa aixi:<div id "unico">Hola</div>
#unico {
}
La classe es posa  aixi:
<span class="classy">aço es un span<span>ç
.classy{
}

## Código para hacer un enlace a otra página y que esta se abra en una nueva ventana  
```html
<a>...</a>
<a href="enlacepagina.html">Enlace a otra página</a
```
## ¿Qué son las pseudoclases?, pon ejemplos.  

Las Pseudo clases permiten seleccionar  elementos aplicando criterios que no  es posible extreurer directament a partir del codig font.
Estos se componen de  normal: El seu estat es nromal, visited: Cuan ya hem visitat el link al que fa rederencia,hover:Cuan tenim el cursor situat damunt de ell,active: quan hem fet click sobre ell.

## Explica el modelo de caja de CSS (margin, border y padding)  

cada elemento se representa como una caja rectangular, con su contenido, padding (espacio interior), borde y margen construidos uno sobre otro .

## Explica que son los selectores de CSS y pon ejemplos  
Els selectors ens permeten elegir al element o elements als que volem aplicar certes regles de presentació. De este mode podem donar estil a tots els elements HTML que vulgam de la nostra pagina. Hi ha 5 seceltors basics de CSS.

Selectro Universal
El selector universal es repensenta el *
```html
*{
color: red
}
```

Selector de elements, etiquetes o tipos
El selector de elements selcciona aquells elements que la seua etiqueta HTML coincideix amb el selector.
```html
h2{
color: vermell;
}
```

Selector de idenificador
Es representa amb #
```html
#principal {
color: red;
}
Es selecionenn aquells elements que els seus atributs coincideixen en el ID en el selector.

Selector de classe
Es selecciona en un (.)
```html
.principal {
color:red;
}
`` `
Seleciona els seus elements que el seu atribut classe coincideixen en el selector indicat.

Selector descendent
El selector descendent es representa concatenant dos selectors seguits.
`` `html
.contenedor p{
color:red;
}
Seleciona aquells elements que es troben dins de altres elements.
