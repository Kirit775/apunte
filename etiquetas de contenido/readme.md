# Apuntes 3
> 28/06/2023
---
* **Etiquetas de contenido**
* **Formularios**
## Etiquetas de contenido

``` html
<!-- las etiquetas de contenido son al etiquetas con importancia semantica para almacenar información-->

    <!-- la etiqueta nav es para las sección de navegacion donde puedes poner lo de inicio/productos/contacto etc.-->
    <nav>
        <a href="a" >ir a youtube</a>
        <a href="a">ir a twitter</a>
    </nav>

    <!-- section es para definir alguna sección dentro de nuestro documento-->
    <section> <h2>sobre nosotros</h2></section>
    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ea, libero?</p>


    <!-- header encapsula la navegación logo etc-->
    <header>
        <a href="a">navegacion</a>
        <h2>Bienvenido a mi página</h2>
    </header>

    <!-- solo hay un main por documento-->
    <main><h2>contenido principal</h2></main>

    <!-- footer es el pie de página para colocar los derechos de autor -->
    <footer><small>Pie de página</small> </footer>

    <!-- aside se usa generalmente para las barras laterales de los blogs-->
    <aside>
        <article>
            <h3>articulos relacionados</h3>
            <p>descripcion del articulo</p>
            <a href="a">ir a articulo</a>
        </article>
    </aside>

    <!-- los divs son contenedores de datos peo no tiene peso semantico en el documento-->
    <div>
        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Vitae, est.</p>
    </div>

```
---
## Formularios

``` html
<!-- los name es el atributo como identificador para luego llamarlo con javascript-->

    <!-- el atributo minlength es para delimitar cuantos caracteres pondra el usario-->

    <!-- maxlength es para el maximo de caracteres-->


    <!-- action es el atributo que determina a donde se manda la información-->
    <form>
        <!-- en los form van input que son donde colocaremos información, datos, nombres etc.-->

        <!-- ingresa un nombre-->

        <!-- label es para conectarlo con un input, el input tiene que tener el un id y en el label el for tiene que tener el id del input-->

        <label for="nombre">Ingresa el nombre</label>

        <br>
        
        <!-- required es el atributo que indica que es obligatorio llenar el input para enviar el formulario-->

        <!-- el placeholder es para poner que quiero que ingrese el usuario-->

        <!-- lso input es donde se pide información al usuario-->
        <input type="text"  placeholder="Ingresa tu nombre" required id="nombre">

        <br><br>
        <!-- ingresa tu email-->
        <label for="email">Ingresa el email</label>

        <br>

        <input type="email"  placeholder="Ingresa tu email" required id="email">

        <br><br>
        
        
        <h3>Elije tu pais</h3>
        <!-- select es para dar distintas opciones de seleccionar e el formulario-->
        <select>
            <!-- option es para las opciones dentro del select-->
            <option value="MX">México</option>
            <option value="ARG">Argentina</option>
            <option value="BR">Brasil</option>
            <!--  el atributo selected es la opcion ya predefinida-->
            <option value="NO" selected>Otro</option>
        </select>
        <!-- que horario quieres-->
        <h3>Elije tu horario</h3>
        <label>
            <input type="radio" name="horario">Matutino
        </label>
        <label>
            <input type="radio" name="horario">Nocturno
        </label>
        <label>
            <input type="radio" name="horario">Mixto
        </label>

        <br>

        <label >
            <input type="color"> ingrese color
        </label>
        <!-- Acepta términos y condiciones-->
        <h3>Acepta terminos</h3>
        <label>
            <input type="checkbox">Acepta terminos y condiciones
        </label>
        <br><br>

        <input type="submit"  >
        <!-- input type reset es para que reinicie valores de los campos ed los input-->
        <input type="reset" value="Reiniciar valores">

    </form>
```
