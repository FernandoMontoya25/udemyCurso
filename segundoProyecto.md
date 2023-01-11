> # Tecnologias usadas HTML - CSS
> ## Codigo html - index - nosotros - productos
- Index.html
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Staatliches&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="./css/styles.css">
    <title>FrontEnd Store</title>
</head>
<body>
    <header class="header">
        <a href="./index.html">
            <img class="header__logo" src="./img/logo.png" alt="Logotipo">
        </a>
    </header>
    <nav class="navegacion">
        <a class="navegacion__enlace navegacion__enlace--activo" href="./index.html">Tienda</a>
        <a class="navegacion__enlace" href="./nosotros.html">Nosotros</a>
    </nav>

    <main class="contenedor">
        <h1>Nuestros Productos</h1>
        <div class="grid">
            <div class="producto">
                <a href="./producto.html">
                    <img class="producto__imagen" src="./img/1.jpg" alt="imagen_camisa">
                    <div class="producto__informacion">
                        <p class="producto__nombre">VueJS</p>
                        <p class="producto__precio">$25</p>
                    </div>
                </a>
            </div>
            <div class="producto">
                <a href="./producto.html">
                    <img class="producto__imagen" src="./img/2.jpg" alt="imagen_camisa">
                    <div class="producto__informacion">
                        <p class="producto__nombre">AngularJS</p>
                        <p class="producto__precio">$25</p>
                    </div>
                </a>
            </div>
            <div class="producto">
                <a href="./producto.html">
                    <img class="producto__imagen" src="./img/3.jpg" alt="imagen_camisa">
                    <div class="producto__informacion">
                        <p class="producto__nombre">ReactJS</p>
                        <p class="producto__precio">$25</p>
                    </div>
                </a>
            </div>
            <div class="producto">
                <a href="./producto.html">
                    <img class="producto__imagen" src="./img/4.jpg" alt="imagen_camisa">
                    <div class="producto__informacion">
                        <p class="producto__nombre">Redux</p>
                        <p class="producto__precio">$25</p>
                    </div>
                </a>
            </div>
            <div class="producto">
                <a href="./producto.html">
                    <img class="producto__imagen" src="./img/5.jpg" alt="imagen_camisa">
                    <div class="producto__informacion">
                        <p class="producto__nombre">NodeJS</p>
                        <p class="producto__precio">$25</p>
                    </div>
                </a>
            </div>
            <div class="producto">
                <a href="./producto.html">
                    <img class="producto__imagen" src="./img/6.jpg" alt="imagen_camisa">
                    <div class="producto__informacion">
                        <p class="producto__nombre">SASS</p>
                        <p class="producto__precio">$25</p>
                    </div>
                </a>
            </div>
            <div class="producto">
                <a href="./producto.html">
                    <img class="producto__imagen" src="./img/7.jpg" alt="imagen_camisa">
                    <div class="producto__informacion">
                        <p class="producto__nombre">HTML5</p>
                        <p class="producto__precio">$25</p>
                    </div>
                </a>
            </div>
            <div class="producto">
                <a href="./producto.html">
                    <img class="producto__imagen" src="./img/8.jpg" alt="imagen_camisa">
                    <div class="producto__informacion">
                        <p class="producto__nombre">Github</p>
                        <p class="producto__precio">$25</p>
                    </div>
                </a>
            </div>
            <div class="producto">
                <a href="./producto.html">
                    <img class="producto__imagen" src="./img/9.jpg" alt="imagen_camisa">
                    <div class="producto__informacion">
                        <p class="producto__nombre">bulmaCSS</p>
                        <p class="producto__precio">$25</p>
                    </div>
                </a>
            </div>
            <div class="producto">
                <a href="./producto.html">
                    <img class="producto__imagen" src="./img/10.jpg" alt="imagen_camisa">
                    <div class="producto__informacion">
                        <p class="producto__nombre">typeScript</p>
                        <p class="producto__precio">$25</p>
                    </div>
                </a>
            </div>
            <div class="producto">
                <a href="./producto.html">
                    <img class="producto__imagen" src="./img/11.jpg" alt="imagen_camisa">
                    <div class="producto__informacion">
                        <p class="producto__nombre">Drupal</p>
                        <p class="producto__precio">$25</p>
                    </div>
                </a>
            </div>
            <div class="producto">
                <a href="./producto.html">
                    <img class="producto__imagen" src="./img/12.jpg" alt="imagen_camisa">
                    <div class="producto__informacion">
                        <p class="producto__nombre">JavaScript</p>
                        <p class="producto__precio">$25</p>
                    </div>
                </a>
            </div>
            <div class="producto">
                <a href="./producto.html">
                    <img class="producto__imagen" src="./img/13.jpg" alt="imagen_camisa">
                    <div class="producto__informacion">
                        <p class="producto__nombre">VS</p>
                        <p class="producto__precio">$25</p>
                    </div>
                </a>
            </div>
            <div class="producto">
                <a href="./producto.html">
                    <img class="producto__imagen" src="./img/14.jpg" alt="imagen_camisa">
                    <div class="producto__informacion">
                        <p class="producto__nombre">WordPress</p>
                        <p class="producto__precio">$25</p>
                    </div>
                </a>
            </div>
            <div class="grafico grafico--camisas"></div>
            <div class="grafico grafico--node"></div>
        </div>
    </main>

    <footer class="footer">
        <p class="footer__texto">Front End Store - Todos los derechos Reservados 2022.</p>
    </footer>
</body>
</html>
```
- Nosotros
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Staatliches&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="./css/styles.css">
    <title>FrontEnd Store</title>
</head>
<body>
    <header class="header">
        <a href="./index.html">
            <img class="header__logo" src="./img/logo.png" alt="Logotipo">
        </a>
    </header>
    <nav class="navegacion">
        <a class="navegacion__enlace" href="./index.html">Tienda</a>
        <a class="navegacion__enlace navegacion__enlace--activo" href="./nosotros.html">Nosotros</a>
    </nav>

    <main class="contenedor">
        <h1>Sobre Nosotros</h1>
        <div class="contenedorNosotros">
            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Consequuntur nihil mollitia recusandae sapiente eum voluptatem aliquid provident, corrupti maxime excepturi modi, dicta a nulla quos tenetur animi. Error, iusto reiciendis.
            </p>
            <img src="./img/nosotros.jpg" alt="nosotros">
        </div>
        <h2 class="titulo__nosotros">Por que comprar con nosotros</h2>
        <div class="contenedorArticles">
            <div>
                <img src="./icons/icono_1.png" alt="">
                <h3>El mejor precio</h3>
                <p class="styleParrafo">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Nam vitae reiciendis minima suscipit neque ducimus aut at vel.</p>
            </div>
            <div>
                <img src="./icons/icono_2.png" alt="">
                <h3>Para devs</h3>
                <p class="styleParrafo">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Nam vitae reiciendis minima suscipit neque ducimus aut at vel.</p>
            </div>
            <div>
                <img src="./icons/icono_3.png" alt="">
                <h3>Envio gratis</h3>
                <p class="styleParrafo">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Nam vitae reiciendis minima suscipit neque ducimus aut at vel.</p>
            </div>
            <div>
                <img src="./icons/icono_4.png" alt="">
                <h3>La mejor calidad</h3>
                <p class="styleParrafo">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Nam vitae reiciendis minima suscipit neque ducimus aut at vel.</p>
            </div>
        </div>
    </main>

    <footer class="footer">
        <p class="footer__texto">Front End Store - Todos los derechos Reservados 2022.</p>
    </footer>
</body>
</html>
```
- Producto
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Staatliches&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="./css/styles.css">
    <title>FrontEnd Store</title>
</head>
<body>
    <header class="header">
        <a href="./index.html">
            <img class="header__logo" src="./img/logo.png" alt="Logotipo">
        </a>
    </header>
    <nav class="navegacion">
        <a class="navegacion__enlace" href="./index.html">Tienda</a>
        <a class="navegacion__enlace" href="./nosotros.html">Nosotros</a>
    </nav>

    <main class="contenedor">
        <h1>React JS</h1>
        <div class="camisa">
            <img src="./img/3.jpg" alt="imagen_producto" class="camisa__imagen">

            <div class="camisa__contenido">
                <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Aspernatur error, quas dignissimos architecto itaque pariatur! Eos labore impedit veniam alias maxime! Eaque repudiandae libero expedita harum aut atque natus ipsum!</p>
                <form class="formulario">
                    <select class="formulario__campo">
                        <option disabled selected>Seleccionar talla</option>
                        <option value="">Chica</option>
                        <option value="">Mediana</option>
                        <option value="">Grande</option>
                    </select>
                    <input class="formulario__campo" type="number" placeholder="Cantidad" min="1" max="25" step="2">
                    <input class="formulario__submit" type="submit" value="Agregar al carrito">
                </form>
            </div>
        </div>
    </main>

    <footer class="footer">
        <p class="footer__texto">Front End Store - Todos los derechos Reservados 2022.</p>
    </footer>
</body>
</html>
```

> ## Codigo CSS
```css
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
:root {
    --primario: #9c27b0;
    --primarioOscuro: #891190;
    --secundario: #ffce00;
    --secundarioOscuro: rgb(233,287,2);
    --blanco: #fff;
    --negro: #000;

    --fuentePrincipal: 'Staatliches', cursive;
}
/*Globales*/
html{
    font-size: 62.5%; /*rem*/
}
body{
    background-color: var(--primario);
    font-size: 1.6rem;
    line-height: 1.5;
}
p{
    font-size: 1.8rem;
    font-family: Arial, Helvetica, sans-serif;
    color: var(--blanco);
}
a{
    text-decoration: none;
}
img{
    max-width: 100%;
}
.contenedor{
    max-width: 120rem;
    margin: 0 auto;
}
h1,h2,h3{
    text-align: center;
    color: var(--secundario);
    font-family: var(--fuentePrincipal);
}
h1{
    font-size: 4rem;
}
h2{
    font-size: 3.2rem;
}
h3{
    font-size: 2.4rem;
}
/*Footer*/
.footer{
    background-color: var(--primarioOscuro);
    padding: 1rem 0;
    margin-top: 2rem;
}
.footer__texto{
    font-family: var(--fuentePrincipal);
    text-align: center;
    font-size: 2.2rem;
}
/*header*/
.header{
    display: flex;
    justify-content: center;
}
.header__logo{
    margin: 3rem 0;
}
.navegacion{
    background-color: var(--primarioOscuro);
    padding: 1rem 0;
    display: flex;
    justify-content: center;
    gap: 2rem; /*Separacion del contenido*/
}
.navegacion__enlace{
    font-family: var(--fuentePrincipal);
    color: var(--blanco);
    font-size: 3rem;
}
.navegacion__enlace--activo, 
.navegacion__enlace:hover{
    color: var(--secundario);
}
/*Grid*/
.grid{
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 2rem;
    /* column-gap: 2rem;
    row-gap: 2rem; */
}
/*Producto*/
.producto{
    background-color: var(--primarioOscuro);
    padding: 1rem;
}
.producto__imagen{
    width: 100%;
}
.producto__nombre{
    font-size: 4rem;
}
.producto__precio{
    font-size: 2.8rem;
    color: var(--secundario);
}
.producto__nombre, 
.producto__precio {
    font-family: var(--fuentePrincipal);
    text-align: center;
}
/*Grafico*/
.grafico{
    min-height: 30rem;
    background-size: cover;
    background-repeat: no-repeat;
}
.grafico--camisas{
    grid-column: 1 / 3;
    grid-row: 2 / 3;
    background-image: url(/segundoProyecto/img/img/grafico1.jpg);
}
.grafico--node{
    background-image: url(/segundoProyecto/img/img/grafico2.jpg);
    grid-column: 1 / 3;
    grid-row: 8 / 9;
}
/*Nosotros*/
.contenedorNosotros{
    display: grid;

}
.contenedorNosotros p{
    margin-bottom: 1rem;
    text-align: center;
    margin: 2rem;
}
.contenedorNosotros img{
    margin: 0 auto;
    grid-row: 1 / 2;
}
.titulo__nosotros{
    margin: 2rem 5rem;
}
/*section nosotros*/
.contenedorArticles{
    text-align: center;
}
.styleParrafo{
    width: 375px;
    margin: 0 auto;
}

/*Producto*/
.camisa {
    display: grid;
    gap: 2rem;
}
.camisa img{
    width: 100%;
}
.formulario {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 1rem;
}
.formulario__campo {
    border: 1rem solid var(--primarioOscuro);
    background-color: transparent;
    color: var(--negro);
    text-align: center;
    font-family: Arial, Helvetica, sans-serif;
    padding: 1rem;
    appearance: none;
    font-weight: bold;
}
.formulario__submit {
    background-color: var(--secundario);
    border: none;
    font-size: 2rem;
    font-family: var(--fuentePrincipal);
    padding: 2rem;
    border-radius: 1rem;
    transition: background-color .3s ease;
    grid-column: 1 / 3;
    margin: 0 1rem;
}
.formulario__submit:hover{
    cursor: pointer;
    background-color: var(--secundarioOscuro);
}

/*medias queries*/
@media (min-width: 768px) {
    .grid{
        grid-template-columns: repeat(3, 1fr);
    }
    .grafico--node{
        grid-column: 2 / 4;
        grid-row: 5 / 6;
    }
    .camisa {
        display: grid;
        grid-template-columns: repeat(2, 2fr);
    }
}
@media (min-width: 1200px) {
    .contenedorNosotros {
        display: flex;
        align-items: center;
    }
    .contenedorArticles {
        display: grid;
        grid-template-columns: repeat(4, 1fr);
    }
    .styleParrafo{
        width: auto;
    }
}
```




