# Apunte 1

> 27/06/2023
---
* **Etiqueta navegación**
* **Listas**
* **Headings**
* **Imagenes**
* **Semanticas**


## etiqueta de navegación
---

```html
<nav>
        <a href="a" >ir a youtube</a>
        <a href="a">ir a twitter</a>
    </nav>
<!-- se crean menu de navegacion con etiquetas de listas no ordenadas-->
    <ul>
        <li><a href="">youtube</a></li>
        <li><a href="">face</a></li>
        <li><a href="">tiwtter</a></li>
    </ul>
    <!-- el href es donde se colocan los enlaces y  el target:_blank e spara que se habra en otra pestaña del navegador-->
    <a href="https://www.youtube.com/watch?v=aFpns1de-Hk&t=1406s" target="_blank">Video del curso que tomé</a>
```

## listas ordenadas
---
```html
<ol>
        <li>Michael Jordan
            <ul>Handles</ul>
            <ul>Mentality</ul>
            <ul>Consistent</ul>
        </li>
        <li>Allen Iverson</li>
        <li>Kyrie Irving</li>
    </ol>
```
## Listas no ordenadas
---
``` html
<!-- ul es para lista no ordenadas por que no la ordena por numeros -->

    <h2>Proyectos de vida</h2>
    <ul> <!-- dentro de cada ul o ol tiene que ir los items li -->
        <li>Libertad financiera</li>
        <li>Riqueza</li>
        <li>paz</li>
    </ul>
```
## Etiquetas de titulos
---

``` html
<h1> Mejores jugadores de basket </h1>
    <!-- solo debe de haber un h1 en toda la documentación y es la más importante jerarquicamente-->

    <h2>Michael Jordan</h2>
    <!--etiqueta <p> es parrafos-->
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Maiores, aut.</p>
    <h2>Kobe Bryant</h2>
    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sapiente, quod.</p>
    <h2>Allen Iverson</h2>
    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Molestias, sit?</p>
    <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Officiis vel quas assumenda optio, numquam qui itaque expedita voluptate ad maxime doloremque, totam, nesciunt quasi asperiores libero? Corporis mollitia dolor velit!
    </p>
```
## Etiquetas semanticas
---

``` html
<!-- em es una etiqueta para posicionamento o CEO en los navegadores-->
    <em> "em" etiqueta semantica o con mayor peso, se convierte en palabras claves pero se pone en italica, solo que se puede cambiar en css</em>
    <p>Se pueden conbinar etiquetas p y em <em>para poner palabras clave entre texto</em></p>

    <!--span es una etiqueta contenedor-->
    <p> la etiqueta span es un contenedor de elementos en linea <span>para luego darles estilo o etc.</span></p>

    <!-- la b es para negritas-->
    <b>B es una etiqueta para poner negritas</b>
    <!--la etiqueta mark resalta por su relevancia-->
    <mark>hola</mark>
    <!--stronge es lo mismo que b pero es semantica a diferencia que b-->
    <strong>Strong da importancia a negritas</strong>
    <!-- small puede servir para los textos de copyrigth y derechos de autor o sin relevancia-->
    <p>la etiqueta <small>small es para quitar importancia a un texto</small></p>
    <!-- cite es para citar en el texto-->
    <p>"Un ganador es solo un perdedor que jamas se rindió. <cite>Michael Jordan</cite></p>

```
## Imagenes
---
```html
<!-- img es para colocar imagenes-->

<!-- el src es donde se ocloca la direccion url de la imagen o el nomrbe del archivo -->

<!-- el atributo alt es para poner el texto que describe la imagen, funciona para el SEO -->

    <img src="coffee.JPG" alt="cafe">
    
    <img src="https://es.wikipedia.org/wiki/Caf%C3%A9" alt="cafe">
    
    <!-- Los elementos svg son imagenes vectoriales para paginas web-->

    <img src="undraw_appreciation_275g.svg" alt="cafe">

```
