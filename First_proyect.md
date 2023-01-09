> ###Pagina de referencia link(https://proyectohtmlcss12.netlify.app/)

> # Codigo html
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.googleapis.com"><link rel="preconnect" href="https://fonts.gstatic.com" crossorigin><link href="https://fonts.googleapis.com/css2?family=Krub:wght@400;700&display=swap" rel="stylesheet">
    <link rel="preload" href="./css/style.css" as="style">
    <link rel="stylesheet" href="./css/style.css">
    <title>Diseño Freelancer</title>
</head>
<body>
    <header>
        <h1 class="titulo">Fernando Montoya <span>Freelancer</span></h1>
    </header>

    <div class="nav-bg">
        <nav class="navegacion-principal contenedor">
            <a href="#">Inicio</a>
            <a href="#">Nosotros</a>
            <a href="#">Clientes</a>
            <a href="#">Contactos</a>
        </nav>
    </div>
    
    <section class="hero">
        <div class="contenido-hero">
            <h2>Diseño y Desarrollo Web <span>Freelancer</span></h2>

            <div class="ubicacion">
                <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-map-pin" width="88" height="88" viewBox="0 0 24 24" stroke-width="1" stroke="#c9de00" fill="none" stroke-linecap="round" stroke-linejoin="round">
                    <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                    <circle cx="12" cy="11" r="3" />
                    <path d="M17.657 16.657l-4.243 4.243a2 2 0 0 1 -2.827 0l-4.244 -4.243a8 8 0 1 1 11.314 0z" />
                </svg>
                <p>Celaya, Guanajuato.</p>
            </div>

            <a class="boton" href="#">Contactar</a>
        </div>
    </section>

    <main class="contenedor sombra">
        <h2>Mis servicios</h2>
        <div class="servicios">
            <section class="servicio">
                <div class="iconos">
                    <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-palette" width="40" height="40" viewBox="0 0 24 24" stroke-width="1" stroke="#ff4500" fill="none" stroke-linecap="round" stroke-linejoin="round">
                        <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                        <path d="M12 21a9 9 0 1 1 0 -18a9 8 0 0 1 9 8a4.5 4 0 0 1 -4.5 4h-2.5a2 2 0 0 0 -1 3.75a1.3 1.3 0 0 1 -1 2.25" />
                        <circle cx="7.5" cy="10.5" r=".5" fill="currentColor" />
                        <circle cx="12" cy="7.5" r=".5" fill="currentColor" />
                        <circle cx="16.5" cy="10.5" r=".5" fill="currentColor" />
                    </svg>
                </div>
                <h3>Diseño Web</h3>
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Corporis esse dolorem tenetur iure eum</p>
            </section>
            <section class="servicio">
                <div class="iconos">
                    <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-brand-android" width="40" height="40" viewBox="0 0 24 24" stroke-width="1" stroke="#ff4500" fill="none" stroke-linecap="round" stroke-linejoin="round">
                        <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                        <line x1="4" y1="10" x2="4" y2="16" />
                        <line x1="20" y1="10" x2="20" y2="16" />
                        <path d="M7 9h10v8a1 1 0 0 1 -1 1h-8a1 1 0 0 1 -1 -1v-8a5 5 0 0 1 10 0" />
                        <line x1="8" y1="3" x2="9" y2="5" />
                        <line x1="16" y1="3" x2="15" y2="5" />
                        <line x1="9" y1="18" x2="9" y2="21" />
                        <line x1="15" y1="18" x2="15" y2="21" />
                    </svg>
                    <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-apple" width="40" height="40" viewBox="0 0 24 24" stroke-width="1" stroke="#ff4500" fill="none" stroke-linecap="round" stroke-linejoin="round">
                        <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                        <circle cx="12" cy="14" r="7" />
                        <path d="M12 11v-6a2 2 0 0 1 2 -2h2v1a2 2 0 0 1 -2 2h-2" />
                        <path d="M10 10.5c1.333 .667 2.667 .667 4 0" />
                    </svg>
                </div>
                <h3>Aplicaciones Web</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sint, id provident. Ut porro laudantium</p>
            </section>
            <section class="servicio">
                <div class="iconos">
                    <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-brand-mastercard" width="40" height="40" viewBox="0 0 24 24" stroke-width="1" stroke="#ff4500" fill="none" stroke-linecap="round" stroke-linejoin="round">
                        <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                        <circle cx="14" cy="12" r="3" />
                        <path d="M12 9.765a3 3 0 1 0 0 4.47" />
                        <rect x="3" y="5" width="18" height="14" rx="2" />
                    </svg>
                </div>
                <h3>E-Commerce</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Deleniti ut deserunt, facere dicta rem dolorum! Eos, ratione</p>
            </section>
        </div>
        
        <section>
            <h2>Contacto</h2>
            <form class="formulario">
                <fieldset>
                    <legend>Contactame llenando los campos</legend>
                    <div class="contenedor-campos">
                        <div class="campo">
                            <label for="">Nombre</label>
                            <input class="input-text" type="text" placeholder="Escribe tu nombre">
                        </div>
                        <div class="campo">
                            <label for="">Telefono</label>
                            <input class="input-text" type="number" placeholder="Escribe tu telefono">
                        </div>
                        <div class="campo">
                            <label for="">Correo</label>
                            <input class="input-text" type="email" placeholder="Correo">
                        </div>
                        <div class="campo">
                            <label for="">Mensaje</label>
                            <textarea class="input-text"></textarea>
                        </div>
                    </div>
                    <div class="alinear-derecha">
                        <input class="w-100" type="submit" value="Enviar">
                    </div>
    
                </fieldset>
            </form>
        </section>
    </main>
    
    <footer class="footer">
        <p>Todos los derechos reservados. Fernando Montoya Freelancer</p>
    </footer>
</body>
</html>
```
> #Codigo CSS
```css
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
:root {
    --blanco: #fff;
    --oscuro: #21212121;
    --primario: #FFC107;
    --secundario: #0097a7;
    --gris: #757575;
}

/* Para poder usar rem */
html{
    font-size: 62.5%;
}
body{
    font-size: 16px;
    font-family: 'Krub', sans-serif;
    background-image: linear-gradient(to top, #dfe9f3 0%, var(--blanco) 100%);
}
/* Aqui acaba lo de rem*/

.sombra{
    -webkit-box-shadow: 0px 5px 15px 0px rgba(112,112,112,0.54);
    -moz-box-shadow: 0px 5px 15px 0px rgba(112,112,112,0.54);
    box-shadow: 0px 5px 15px 0px rgba(112,112,112,0.54);

    background-color: var(--blanco);
    padding: 2rem;
    border-radius: 1rem;
}

h1{
    font-size: 3.8rem;
}
h2 {
    font-size: 2.8rem;
}
h3 {
    font-size: 1.8rem;
}

h1, h2, h3 {
    text-align: center;
}

.titulo span{
    font-size: 2rem;
}

.contenedor{
    max-width: 120rem;
    margin: auto;
}

.boton {
    background-color: var(--secundario);
    color: var(--blanco);
    padding: 1rem 3rem;
    margin-top: 1rem;
    font-size: 20px;
    text-decoration: none;
    text-transform: uppercase;
    font-weight: bold;
    border-radius: .5rem;
    width: 90%;
    text-align: center;
    border: none;
}
.boton:hover{
    cursor: pointer;
}
/*Utilidades*/
.nav-bg{
    background-color: var(--secundario);
}
.w-100{
    width: 100%;
    background-color: var(--secundario);
    color: var(--blanco);
    padding: 1rem 3rem;
    margin-top: 1rem;
    font-size: 20px;
    text-decoration: none;
    text-transform: uppercase;
    font-weight: bold;
    border-radius: .5rem;
    text-align: center;
    border: none;
}
/*Finaliza utilidades*/

.navegacion-principal{
    display: flex;
    flex-direction: column;
}

.navegacion-principal a{
    color: var(--blanco);
    text-decoration: none;
    font-size: 2rem;
    font-weight: 400;
    padding: 1rem;
    display: block;
    text-align: center;
}

.navegacion-principal a:hover{
    background-color: var(--primario);
    color: black;
    font-weight: bold;
}

.hero{
    background-image: url(/proyectoFrelancer1/img/hero.jpg);
    background-repeat: no-repeat;
    background-size: cover; /*Toma todo el espacio disponible*/
    height: 450px;
    position: relative;
    margin-bottom: 2rem;
}
.contenido-hero{
    position: absolute;
    background-color: rgb( 0 0 0 / 70% ); /*Transparencia*/
    width: 100%;
    height: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}

.contenido-hero h2, .contenido-hero p{
    color: var(--blanco);
}

.ubicacion {
    display: flex;
}
.ubicacion p{
    display: flex;
    align-items: center;
}

.servicios{
    scroll-snap-align: center;
    scroll-snap-stop: always;
}

.servicio h3{
    color: var(--secundario);
    font-weight: bold;
}
.servicio .iconos{
    height: 15rem;
    width: 15rem;
    background-color: var(--primario);
    margin: auto;
    margin-bottom: 1rem;
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    border-radius: 50%;
}
/*------Formulario------*/
.formulario{
     background-color: var(--gris);
     width: min( 60rem, 100%); /*Utiliza el valor mas pequeño*/
     margin: 0 auto;
     padding: 2rem;
     border-radius: 2rem;
}
.formulario fieldset{
    border: none;
}
.formulario legend{
    text-align: center;
    font-size: 1.8rem;
    text-transform: uppercase;
    font-weight: 700;
    margin-bottom: 2rem;
    color: var(--primario);
}

.campo{
    margin-bottom: 1rem;
}
.campo label{
    color: var(--blanco);
    font-weight: bold;
    margin-bottom: .5rem;
    display: block;
}
.campo textarea{
    height: 20rem;
}
.input-text{
    width: 100%;
    border: none;
    padding: 1.5rem;
    border-radius: .5rem;
}
/*Footer*/
.footer{
    text-align: center;
    height: 4rem;
    display: flex;
    justify-content: center;
    align-items: center;
}

/*media-queries*/
@media (min-width: 768px) {
    .navegacion-principal{
        flex-direction: row;
        justify-content: space-between;
        width: auto;
    }
    .boton{
        width: auto;
    }
    .servicios{
        display: grid;
        grid-template-columns: 1fr 1fr 1fr;
        text-align: center;
        margin-top: 1rem;
        margin-bottom: 1rem;
        column-gap: 5rem; /*Separacion entre columnas*/ 
    }
    .w-100{
        width: 30%;
        margin-left: 200px;
        margin-top: 4rem;
    }
    .contenedor-campos{
        display: grid;
        grid-template-columns: 50% 50%;
        grid-template-rows: auto auto 20rem;
        column-gap: 1rem;
    }
    .campo:nth-child(3) {
        grid-column: 1 / 3;
    }
    .campo:nth-child(4) {
        grid-column: 1 / 3;
    }
}
```



 
