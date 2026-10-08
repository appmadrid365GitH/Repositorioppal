```html
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<meta name="description"
content="APPMADRID365 — talento, software e innovación nacidos en Madrid.">

<title>APPMADRID365 — Madrid Tech Talent</title>

<style>

/* =========================================================
   APPMADRID365
   Apps · Software · Innovación
   ========================================================= */

:root {
    --fondo: #b7b8b9;
    --fondo-claro: #c4c5c6;
    --negro: #090909;
    --gris: #353535;
    --blanco: #f4f4f2;
    --linea: rgba(0,0,0,.30);
}

* {
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
}

body {
    margin: 0;
    background: var(--fondo);
    color: var(--negro);
    font-family: Arial, Helvetica, sans-serif;
    overflow-x: hidden;
}


/* =========================================================
   TEXTURA DE PAPEL
   ========================================================= */

body::before {
    content: "";
    position: fixed;
    inset: 0;
    pointer-events: none;
    z-index: 10;

    background-image:
        repeating-linear-gradient(
            0deg,
            rgba(0,0,0,.018) 0px,
            rgba(0,0,0,.018) 1px,
            transparent 1px,
            transparent 4px
        );

    opacity: .35;
}


/* =========================================================
   CONTENEDOR
   ========================================================= */

.wrap {
    position: relative;
    z-index: 2;
}


/* =========================================================
   CABECERA
   ========================================================= */

header {
    min-height: 88vh;

    display: flex;
    flex-direction: column;
    justify-content: space-between;

    padding: 30px 6vw 0;

    position: relative;
}


/* =========================================================
   NAVEGACIÓN
   ========================================================= */

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;

    gap: 20px;
}

.logo {
    font-size: 14px;

    letter-spacing: .22em;

    font-weight: 800;
}

.lang button {
    border: 1px solid var(--negro);

    background: transparent;

    padding: 8px 13px;

    margin-left: 5px;

    cursor: pointer;

    font-weight: 700;

    transition: .2s;
}

.lang button.active,
.lang button:hover {
    background: var(--negro);
    color: var(--blanco);
}


/* =========================================================
   HERO
   ========================================================= */

.hero {
    max-width: 1180px;

    width: 100%;

    margin: auto;

    padding: 70px 0 30px;
}

.kicker {
    font-size: 13px;

    text-transform: uppercase;

    letter-spacing: .25em;

    font-weight: 700;

    margin-bottom: 24px;
}


/* =========================================================
   LOGOTIPO PRINCIPAL
   SIN ANIMACIÓN
   ========================================================= */

h1 {
    margin: 0;

    font-size: clamp(58px, 12vw, 170px);

    line-height: .78;

    letter-spacing: -.075em;

    font-weight: 900;
}

h1 span {
    display: inline-block;
}


/* =========================================================
   TEXTO HERO
   ========================================================= */

.hero-sub {
    margin: 40px 0 0;

    max-width: 650px;

    font-size: clamp(20px, 2.4vw, 31px);

    line-height: 1.18;

    font-weight: 500;
}

.hero-sub strong {
    font-weight: 900;
}


/* =========================================================
   SCROLL
   ========================================================= */

.scroll {
    font-size: 11px;

    letter-spacing: .2em;

    text-transform: uppercase;

    padding-bottom: 25px;
}


/* =========================================================
   SKYLINE
   DIBUJO A LÁPIZ
   ========================================================= */

.skyline {
    height: 310px;

    position: relative;

    overflow: hidden;

    background:
        linear-gradient(
            to bottom,
            rgba(255,255,255,.05),
            rgba(0,0,0,.06)
        );

    border-top: 1px solid var(--line);
}


/*
   Papel y lápiz.
   Varias líneas superpuestas crean el aspecto
   imperfecto de un dibujo realizado a mano.
*/

.skyline svg {
    position: absolute;

    bottom: -2px;

    left: 0;

    width: 100%;

    height: 100%;
}


/* Línea principal */

.building-main {
    fill: none;

    stroke: #111;

    stroke-width: 2.4;

    stroke-linecap: round;

    stroke-linejoin: round;
}


/* Líneas secundarias */

.building-light {
    fill: none;

    stroke: #222;

    stroke-width: 1.2;

    stroke-linecap: round;

    opacity: .55;
}


/* Línea de lápiz más fina */

.pencil {
    fill: none;

    stroke: #111;

    stroke-width: .8;

    stroke-linecap: round;

    opacity: .45;
}


/* =========================================================
   SECCIONES
   ========================================================= */

section {
    padding: 100px 6vw;

    border-top: 1px solid var(--line);
}


/* =========================================================
   GRID
   ========================================================= */

.grid {
    max-width: 1180px;

    margin: auto;

    display: grid;

    grid-template-columns: 1fr 1.5fr;

    gap: 70px;
}


/* =========================================================
   NUMERACIÓN
   ========================================================= */

.number {
    font-size: 12px;

    letter-spacing: .2em;

    font-weight: 800;
}


/* =========================================================
   TÍTULOS
   ========================================================= */

h2 {
    margin: 0;

    font-size: clamp(40px, 6vw, 82px);

    line-height: .92;

    letter-spacing: -.055em;
}


/* =========================================================
   TEXTO
   ========================================================= */

.copy {
    font-size: 20px;

    line-height: 1.55;

    max-width: 700px;
}


/* =========================================================
   TARJETAS
   ========================================================= */

.cards {
    max-width: 1180px;

    margin: 65px auto 0;

    display: grid;

    grid-template-columns: repeat(3, 1fr);

    border-top: 1px solid var(--negro);
}

.card {
    padding: 28px 25px 35px 0;

    border-right: 1px solid var(--line);

    margin-right: 25px;
}

.card:last-child {
    border-right: 0;
}

.card h3 {
    font-size: 24px;

    margin: 0 0 15px;
}

.card p {
    line-height: 1.55;

    margin: 0;

    color: var(--gris);
}


/* =========================================================
   SECCIÓN OSCURA
   ========================================================= */

.big {
    min-height: 72vh;

    display: flex;

    align-items: center;

    background: #090909;

    color: #eee;

    position: relative;

    overflow: hidden;
}


/* Gran número decorativo */

.big::after {
    content: "365";

    position: absolute;

    right: -3vw;

    bottom: -14vw;

    font-size: 38vw;

    font-weight: 900;

    letter-spacing: -.1em;

    color: #171717;

    z-index: 0;
}

.big .grid {
    position: relative;

    z-index: 1;
}

.big .number {
    color: #aaa;
}

.big h2 {
    max-width: 650px;
}


/* =========================================================
   ETIQUETA
   ========================================================= */

.outline {
    margin-top: 30px;

    display: inline-block;

    border: 1px solid #aaa;

    padding: 14px 18px;

    color: #eee;

    font-size: 12px;

    letter-spacing: .12em;

    text-transform: uppercase;
}


/* =========================================================
   FOOTER
   ========================================================= */

footer {
    padding: 35px 6vw;

    display: flex;

    justify-content: space-between;

    gap: 30px;

    font-size: 11px;

    letter-spacing: .1em;

    text-transform: uppercase;
}


/* =========================================================
   RESPONSIVE
   ========================================================= */

@media (max-width: 800px) {

    header {
        min-height: 88vh;

        padding: 22px 5vw 0;
    }

    .grid {
        grid-template-columns: 1fr;

        gap: 35px;
    }

    .cards {
        grid-template-columns: 1fr;
    }

    .card {
        border-right: 0;

        border-bottom: 1px solid var(--line);

        margin: 0;

        padding: 28px 0;
    }

    .card:last-child {
        border-bottom: 0;
    }

    section {
        padding: 75px 5vw;
    }

    .skyline {
        height: 210px;
    }

    footer {
        flex-direction: column;
    }
}

</style>
</head>


<body>


<div class="wrap">


<!-- =====================================================
     CABECERA
     ===================================================== -->

<header>


<nav>

    <div class="logo">
        APP MADRID 365
    </div>


    <div class="lang">

        <button
            id="es"
            class="active">
            ES
        </button>

        <button
            id="en">
            EN
        </button>

    </div>

</nav>


<main class="hero">


<div
    class="kicker"
    data-es="Tecnología · talento · innovación"
    data-en="Technology · talent · innovation">

    Tecnología · talento · innovación

</div>


<h1 aria-label="APPMADRID365">

    <span>A</span><span>P</span><span>P</span><span>M</span><span>A</span><span>D</span><span>R</span><span>I</span><span>D</span><span>3</span><span>6</span><span>5</span>

</h1>


<p
    class="hero-sub"
    data-es="El talento madrileño <strong>crea software para el mundo.</strong>"
    data-en="Madrid's talent <strong>builds software for the world.</strong>">

    El talento madrileño
    <strong>crea software para el mundo.</strong>

</p>


</main>


<div
    class="scroll"
    data-es="Descubre la nueva Madrid tecnológica ↓"
    data-en="Discover the new technological Madrid ↓">

    Descubre la nueva Madrid tecnológica ↓

</div>


</header>



<!-- =====================================================
     SKYLINE DE MADRID
     DIBUJADO A MANO
     ===================================================== -->

<div class="skyline">


<svg
    viewBox="0 0 1600 310"
    preserveAspectRatio="none"
    aria-label="Dibujo arquitectónico del skyline de Madrid">


<!-- =================================================
     SIL
