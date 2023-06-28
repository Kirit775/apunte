# Apunte 2
>28/06/2023
---
* **Tablas**
* **Desplazamiento por anclas**
## Tablas en HTML
``` html
<!-- table es la etiqueta para las tablas-->
    <!-- tr o tablerow es la fila-->
    <!-- th es el encabezado de las tablas-->
    <!-- td es el contenido de las tablas-->
    <table>
        <caption>resgistro Personas</caption>
        <tr>
            <th>Nombre</th>
            <th>Edad</th>
            <th>Sexo</th>
        </tr>
        <tr>
            <td>Jordan</td>
            <td>23</td>
            <td>Masculino</td>
        </tr>
        <tr>
            <td>Allen</td>
            <td>21</td>
            <td>Masculino</td>
        </tr>
    </table>

```
---
## Desplazamiento por anclas
``` html
 <!-- id (es un identificador)debe ser distintocada id, class sr usa para luego darle estilo con css, y pueden tener más de una class-->

    <!-- https://caninclude.glitch.me/  página para saber que etiquetas puede ir dentro de cual -->

    <!-- htmlsreference.com pagina para saber cual etiqueta es de linea y y cual de bloque-->

    
    <!-- Dezplazamientos por anclas -->
    <section id="acerca_de">
        <nav>
            <a href="#acerca_de">Acerca de</a>
            <a href="#contacto">contacto</a>
            <a href="#galeria">Galeria</a>
        </nav>

        <h2>Acerda de</h2>
        <div>
            <br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
        </div>
    </section>
    <section id="contacto">
        <nav>
            <a href="#acerca_de">Acerca de</a>
            <a href="#contacto">contacto</a>
            <a href="#galeria">Galeria</a>
        </nav>

        <h2>contacto</h2>
        <div>
            <br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
        </div>
    </section>
    <section id="galeria">
        <nav>
            <a href="#acerca_de">Acerca de</a>
            <a href="#contacto">contacto</a>
            <a href="#galeria">Galeria</a>
        </nav>

        <h2>Galeria</h2>
        <div>
            <br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
        </div>
    </section>

```