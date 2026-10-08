<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>APP MADRID 365 — Aplicaciones, software e innovación</title>

<meta
    name="description"
    content="APP MADRID 365"
>

<style>

/* =========================================================
   APP MADRID 365
   DISEÑO AUTÓNOMO
   Sin imágenes externas
   Sin recursos externos
   ========================================================= */

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
}

body {
    background: #08090c;
    color: #f4f4f2;
    font-family: Arial, Helvetica, sans-serif;
    overflow-x: hidden;
}


/* =========================================================
   HERO
   ========================================================= */

.hero {
    position: relative;
    min-height: 100vh;
    overflow: hidden;

    /*
       Fondo gris oscuro con una fuente de luz azul muy suave.
       El gris sigue siendo el color dominante.
    */

    background:
        radial-gradient(
            ellipse 70% 55% at 50% 8%,
            rgba(70, 130, 205, .13) 0%,
            rgba(70, 130, 205, .07) 22%,
            rgba(70, 130, 205, .025) 42%,
            transparent 68%
        ),

        radial-gradient(
            ellipse 90% 45% at 50% 68%,
            rgba(165, 170, 180, .13),
            transparent 60%
        ),

        linear-gradient(
            180deg,
            #07090c 0%,
            #0b0e13 35%,
            #10141a 68%,
            #15191f 100%
        );
}


/*
   Haz de luz azul.
   Parece una fuente de luz situada encima de Madrid.
*/

.hero::after {
    content: "";

    position: absolute;

    width: 85vw;
    height: 75vh;

    top: -28vh;
    left: 50%;

    transform:
        translateX(-50%)
        rotate(0deg);

    background:
        radial-gradient(
            ellipse at center,
            rgba(80, 145, 220, .13) 0%,
            rgba(80, 145, 220, .07) 24%,
            rgba(80, 145, 220, .025) 48%,
            transparent 72%
        );

    filter: blur(35px);

    pointer-events: none;

    z-index: 1;
}


.hero::before {
    content: "";
    position: absolute;
    inset: 0;

    opacity: .065;

    background-image:
        radial-gradient(
            rgba(255,255,255,.9) .5px,
            transparent .5px
        );

    background-size: 7px 7px;

    pointer-events: none;

    z-index: 2;
}


/* =========================================================
   NAVEGACIÓN
   ========================================================= */

nav {
    position: absolute;

    top: 0;
    left: 0;

    width: 100%;

    padding: 30px 5vw;

    display: flex;
    align-items: center;
    justify-content: space-between;

    z-index: 50;
}

.logo {
    font-size: 15px;
    font-weight: bold;
    letter-spacing: 4px;
}

.logo span {
    opacity: .35;
}

.nav-right {
    display: flex;
    align-items: center;
    gap: 35px;
}

.menu {
    display: flex;
    gap: 35px;
}

.menu a {
    color: #fff;
    text-decoration: none;

    font-size: 10px;
    letter-spacing: 3px;
    text-transform: uppercase;

    opacity: .5;

    transition: opacity .3s ease;
}

.menu a:hover {
    opacity: 1;
}


/* =========================================================
   IDIOMAS
   ========================================================= */

.language-switch {
    display: flex;
    align-items: center;
    gap: 9px;

    font-size: 10px;
    letter-spacing: 2px;

    text-transform: uppercase;
}

.language-switch button {
    border: 0;
    background: transparent;

    color: rgba(255,255,255,.35);

    font-family: Arial, Helvetica, sans-serif;

    font-size: 10px;
    letter-spacing: 2px;

    cursor: pointer;

    padding: 3px;

    transition:
        color .25s ease,
        opacity .25s ease;
}

.language-switch button:hover {
    color: white;
}

.language-switch button.active {
    color: white;
}

.language-separator {
    color: rgba(255,255,255,.18);
}


/* =========================================================
   TEXTO PRINCIPAL
   ========================================================= */

.content {
    position: relative;

    z-index: 20;

    padding:
        19vh
        7vw
        0;

    max-width: 1050px;
}

.kicker {
    margin-bottom: 30px;

    font-size: 10px;
    letter-spacing: 6px;

    text-transform: uppercase;

    color: rgba(255,255,255,.45);
}

h1 {
    font-size: clamp(
        70px,
        12vw,
        175px
    );

    line-height: .78;

    letter-spacing: -8px;

    font-weight: 800;
}

h1 span {
    display: block;
}

.subtitle {
    max-width: 550px;

    margin-top: 42px;

    font-size: 18px;

    line-height: 1.7;

    color: rgba(255,255,255,.58);
}

.cta {
    display: inline-block;

    margin-top: 35px;

    padding: 15px 28px;

    border: 1px solid
        rgba(255,255,255,.25);

    color: white;

    text-decoration: none;

    font-size: 10px;

    letter-spacing: 3px;

    text-transform: uppercase;

    transition:
        background .3s ease,
        color .3s ease,
        border-color .3s ease;
}

.cta:hover {
    background: #fff;
    color: #08090c;
    border-color: #fff;
}


/* =========================================================
   BRILLO
   ========================================================= */

.city-glow {
    position: absolute;

    width: 90vw;
    height: 45vh;

    left: 50%;
    bottom: 8%;

    transform: translateX(-50%);

    background:
        radial-gradient(
            ellipse,
            rgba(175,185,200,.14) 0%,
            rgba(100,140,185,.035) 38%,
            transparent 70%
        );

    filter: blur(25px);

    z-index: 2;
}


/*
   Luz azul vertical muy sutil.
   Da la sensación de que el cielo ilumina la ciudad.
*/

.city-glow::after {
    content: "";

    position: absolute;

    width: 45%;
    height: 120%;

    left: 27%;
    top: -25%;

    background:
        linear-gradient(
            180deg,
            rgba(70,135,210,.07),
            rgba(70,135,210,.025),
            transparent
        );

    filter: blur(35px);

    transform: perspective(400px) rotateX(12deg);

    opacity: .8;
}


/* =========================================================
   RED TECNOLÓGICA
   ========================================================= */

.network {
    position: absolute;

    inset: 0;

    z-index: 4;

    pointer-events: none;

    opacity: .22;
}

.network-line {
    position: absolute;

    height: 1px;

    background:
        linear-gradient(
            90deg,
            transparent,
            rgba(145,180,215,.55),
            transparent
        );

    transform-origin: left center;
}

.node {
    position: absolute;

    width: 4px;
    height: 4px;

    border-radius: 50%;

    background: rgba(190,215,240,.9);

    box-shadow:
        0 0 12px rgba(100,170,235,.75);

    animation:
        pulse 3s infinite ease-in-out;
}

@keyframes pulse {

    0%,100% {
        opacity: .25;
        transform: scale(.7);
    }

    50% {
        opacity: 1;
        transform: scale(1.3);
    }
}


/* =========================================================
   SKYLINE
   ========================================================= */

.skyline {
    position: absolute;

    left: 0;
    bottom: -1px;

    width: 100%;

    height: 57vh;

    z-index: 8;

    overflow: visible;
}

.building {
    fill:
        rgba(8,10,14,.96);

    stroke:
        rgba(220,220,220,.38);

    stroke-width:
        1.2;
}

.pencil {
    fill: none;

    stroke:
        rgba(225,225,225,.35);

    stroke-width:
        1;

    stroke-linecap: round;
}

.pencil-soft {
    fill: none;

    stroke:
        rgba(210,210,210,.18);

    stroke-width:
        .7;

    stroke-linecap: round;
}


/* =========================================================
   DATOS INFERIORES
   ========================================================= */

.bottom-info {
    position: absolute;

    bottom: 28px;

    left: 5vw;
    right: 5vw;

    z-index: 30;

    display: flex;

    justify-content: space-between;

    font-size: 9px;

    letter-spacing: 3px;

    text-transform: uppercase;

    color:
        rgba(255,255,255,.35);
}


/* =========================================================
   SEGUNDA SECCIÓN
   ========================================================= */

.intro {
    position: relative;

    min-height: 75vh;

    padding:
        140px 10vw;

    background:
        #f1f0ec;

    color:
        #151619;
}

.intro small {
    display: block;

    margin-bottom: 30px;

    font-size: 10px;

    letter-spacing: 5px;

    text-transform: uppercase;

    opacity: .45;
}

.intro h2 {
    max-width: 950px;

    font-size:
        clamp(40px, 7vw, 100px);

    line-height: .95;

    letter-spacing: -4px;

    font-weight: 700;
}

.intro p {
    max-width: 650px;

    margin-top: 45px;

    font-size: 18px;

    line-height: 1.8;

    color:
        rgba(20,20,20,.62);
}


/* =========================================================
   SECCIÓN GLOBAL
   ========================================================= */

.global {
    min-height: 80vh;

    padding:
        130px 8vw;

    background:
        #0b0d11;

    color: white;
}

.global-label {
    font-size: 10px;

    letter-spacing: 5px;

    text-transform: uppercase;

    opacity: .4;
}

.global h2 {
    margin-top: 30px;

    font-size:
        clamp(45px, 8vw, 120px);

    line-height: .9;

    letter-spacing: -5px;
}

.global-text {
    max-width: 600px;

    margin-top: 45px;

    font-size: 18px;

    line-height: 1.8;

    color: rgba(255,255,255,.55);
}


/* =========================================================
   FOOTER
   ========================================================= */

footer {
    padding:
        35px 5vw;

    background: #050609;

    border-top:
        1px solid rgba(255,255,255,.08);

    display: flex;

    justify-content: space-between;

    font-size: 9px;

    letter-spacing: 3px;

    text-transform: uppercase;

    color:
        rgba(255,255,255,.3);
}


/* =========================================================
   RESPONSIVE
   ========================================================= */

@media(max-width: 750px) {

    nav {
        padding: 22px 6vw;
    }

    .menu {
        display: none;
    }

    .nav-right {
        gap: 0;
    }

    .content {
        padding:
            20vh 7vw 0;
    }

    h1 {
        letter-spacing: -5px;
    }

    .subtitle {
        font-size: 15px;
    }

    .skyline {
        height: 40vh;
    }

    .bottom-info {
        font-size: 7px;
        letter-spacing: 2px;
    }

    .intro,
    .global {
        padding:
            100px 8vw;
    }

    footer {
        flex-direction: column;
        gap: 15px;
    }

    .hero::after {
        width: 120vw;
        height: 70vh;
    }
}

</style>
</head>


<body>


<!-- =====================================================
     PORTADA
     ===================================================== -->

<section class="hero">


<nav>

    <div class="logo">
        APP MADRID <span>365</span>
    </div>


    <div class="nav-right">

        <div class="menu">

            <a href="#madrid"
               data-es="Madrid"
               data-en="Madrid">
                Madrid
            </a>

            <a href="#global"
               data-es="Aplicaciones"
               data-en="Apps">
                Aplicaciones
            </a>

        </div>


        <!-- CAMBIO DE IDIOMA -->

        <div class="language-switch">

            <button
                id="esButton"
                class="active"
                onclick="changeLanguage('es')">

                ES

            </button>

            <span class="language-separator">
                /
            </span>

            <button
                id="enButton"
                onclick="changeLanguage('en')">

                EN

            </button>

        </div>

    </div>

</nav>



<!-- =====================================================
     RED TECNOLÓGICA
     ===================================================== -->

<div class="network">

    <div class="node"
         style="left:12%;top:22%">
    </div>

    <div class="node"
         style="left:28%;top:16%">
    </div>

    <div class="node"
         style="left:46%;top:28%">
    </div>

    <div class="node"
         style="left:63%;top:14%">
    </div>

    <div class="node"
         style="left:79%;top:25%">
    </div>

    <div class="node"
         style="left:90%;top:12%">
    </div>


    <div class="network-line"
         style="
         left:12%;
         top:22%;
         width:22%;
         transform:rotate(-5deg);
         ">
    </div>

    <div class="network-line"
         style="
         left:28%;
         top:16%;
         width:23%;
         transform:rotate(18deg);
         ">
    </div>

    <div class="network-line"
         style="
         left:46%;
         top:28%;
         width:22%;
         transform:rotate(-20deg);
         ">
    </div>

    <div class="network-line"
         style="
         left:63%;
         top:14%;
         width:20%;
         transform:rotate(20deg);
         ">
    </div>

</div>



<!-- =====================================================
     TEXTO PRINCIPAL
     ===================================================== -->

<div class="content">

    <div
        class="kicker"
        data-es="Madrid · Europa · Tecnología"
        data-en="Madrid · Europe · Technology">

        Madrid · Europa · Tecnología

    </div>


    <h1>

        <span>MADRID</span>

        <span
            data-es="CONSTRUYE."
            data-en="BUILDS.">

            CONSTRUYE.

        </span>

    </h1>


    <p
        class="subtitle"
        data-es="
        Una ciudad conectada con la economía
        digital mundial. Aplicaciones, software
        e innovación desde Madrid hacia el mundo.
        "
        data-en="
        A city connected to the world's
        digital economy. Applications,
        software and innovation
        from Madrid to the world.
        ">

        Una ciudad conectada con la economía
        digital mundial. Aplicaciones, software
        e innovación desde Madrid hacia el mundo.

    </p>


    <a
        class="cta"
        href="#madrid"
        data-es="Descubre Madrid →"
        data-en="Explore Madrid →">

        Descubre Madrid →

    </a>

</div>


<div class="city-glow"></div>



<!-- =====================================================
     SKYLINE
     ===================================================== -->

<svg
    class="skyline"
    viewBox="0 0 1600 600"
    preserveAspectRatio="none"
    xmlns="http://www.w3.org/2000/svg">


    <path
        class="building"
        d="
        M0 600
        L0 455
        L65 455
        L65 410
        L125 410
        L125 470
        L180 470
        L180 380
        L240 380
        L240 445
        L300 445
        L300 350
        L360 350
        L360 600
        Z"
    />


    <path
        class="building"
        d="
        M350 600
        L350 420
        L385 420
        L385 350
        L425 350
        L425 395
        L470 395
        L470 325
        L520 325
        L520 600
        Z"
    />


    <path
        class="building"
        d="
        M515 600
        L515 270
        L540 270
        L540 220
        L565 220
        L565 175
        L595 175
        L625 220
        L625 270
        L650 270
        L650 600
        Z"
    />


    <path
        class="pencil"
        d="
        M530 285 L530 570
        M548 250 L548 570
        M568 205 L568 570
        M588 205 L588 570
        M608 250 L608 570
        M630 285 L630 570
        "
    />


    <path
        class="building"
        d="
        M645 600
        L645 415
        L680 415
        L680 375
        L715 375
        L715 340
        L760 340
        L805 340
        L805 375
        L840 375
        L840 415
        L875 415
        L875 600
        Z"
    />


    <path
        class="pencil"
        d="
        M710 340
        Q760 275 810 340
        "
    />

    <path
        class="pencil-soft"
        d="
        M725 340
        Q760 300 795 340
        "
    />


    <!-- CUATRO TORRES -->

    <path
        class="building"
        d="
        M850 600
        L850 125
        L900 125
        L900 600
        Z"
    />

    <path
        class="pencil"
        d="
        M860 145 L860 570
        M875 145 L875 570
        M890 145 L890 570
        "
    />


    <path
        class="building"
        d="
        M925 600
        L925 75
        L980 75
        L980 600
        Z"
    />

    <path
        class="pencil"
        d="
        M937 100 L937 570
        M953 100 L953 570
        M969 100 L969 570
        "
    />


    <path
        class="building"
        d="
        M1005 600
        L1005 145
        L1055 145
        L1055 600
        Z"
    />

    <path
        class="pencil"
        d="
        M1016 165 L1016 570
        M1030 165 L1030 570
        M1045 165 L1045 570
        "
    />


    <path
        class="building"
        d="
        M1080 600
        L1080 105
        L1135 105
        L1135 600
        Z"
    />

    <path
        class="pencil"
        d="
        M1092 125 L1092 570
        M1107 125 L1107 570
        M1122 125 L1122 570
        "
    />


    <path
        class="building"
        d="
        M1140 600
        L1140 350
        L1190 350
        L1190 390
        L1240 390
        L1240 310
        L1300 310
        L1300 430
        L1360 430
        L1360 360
        L1420 360
        L1420 420
        L1480 420
        L1480 330
        L1530 330
        L1530 440
        L1600 440
        L1600 600
        Z"
    />


    <path
        class="pencil-soft"
        d="
        M0 500
        Q400 480 800 505
        T1600 495
        "
    />

    <path
        class="pencil"
        d="
        M0 525
        Q400 510 800 530
        T1600 515
        "
    />

</svg>



<!-- =====================================================
     INFORMACIÓN INFERIOR
     ===================================================== -->

<div class="bottom-info">

    <span>
        40.4168° N
    </span>

    <span
        data-es="MADRID · ESPAÑA"
        data-en="MADRID · SPAIN">

        MADRID · ESPAÑA

    </span>

    <span>
        365 / 365
    </span>

</div>


</section>



<!-- =====================================================
     SECCIÓN MADRID
     ===================================================== -->

<section
    class="intro"
    id="madrid">

    <small
        data-es="Madrid / Tecnología"
        data-en="Madrid / Technology">

        Madrid / Tecnología

    </small>


    <h2
        data-es="
        Una ciudad donde
        la tecnología se
        encuentra con el mundo.
        "
        data-en="
        A city where
        technology meets
        the world.
        ">

        Una ciudad donde
        la tecnología se
        encuentra con el mundo.

    </h2>


    <p
        data-es="
        Madrid se ha convertido en uno de los
        centros importantes de Europa para la
        tecnología, la innovación y el
        emprendimiento. Sus conexiones
        internacionales, talento y creciente
        ecosistema tecnológico conectan
        la ciudad con mercados de todo el mundo.
        "
        data-en="
        Madrid has become one of Europe's
        important centres for technology,
        innovation and entrepreneurship.
        Its international connections, talent
        and growing technology ecosystem
        connect the city with markets around the world.
        ">

        Madrid se ha convertido en uno de los
        centros importantes de Europa para la
        tecnología, la innovación y el
        emprendimiento. Sus conexiones
        internacionales, talento y creciente
        ecosistema tecnológico conectan
        la ciudad con mercados de todo el mundo.

    </p>

</section>



<!-- =====================================================
     SECCIÓN GLOBAL
     ===================================================== -->

<section
    class="global"
    id="global">

    <div
        class="global-label"
        data-es="Madrid / Conexión global"
        data-en="Madrid / Global connection">

        Madrid / Conexión global

    </div>


    <h2
        data-es="
        DESDE<br>
        MADRID<br>
        AL MUNDO.
        "
        data-en="
        FROM<br>
        MADRID<br>
        TO THE WORLD.
        ">

        DESDE<br>
        MADRID<br>
        AL MUNDO.

    </h2>


    <p
        class="global-text"
        data-es="
        Aplicaciones, software, inteligencia artificial
        e innovación están transformando
        la forma en que las ciudades y las personas
        se conectan.
        "
        data-en="
        Applications, software, artificial intelligence
        and innovation are transforming
        the way cities and people connect.
        ">

        Aplicaciones, software, inteligencia artificial
        e innovación están transformando
        la forma en que las ciudades y las personas
        se conectan.

    </p>

</section>



<!-- =====================================================
     FOOTER
     ===================================================== -->

<footer>

    <span>
        APP MADRID 365
    </span>

    <span
        data-es="MADRID · ESPAÑA"
        data-en="MADRID · SPAIN">

        MADRID · ESPAÑA

    </span>

    <span>
        © 2026
    </span>

</footer>



<script>

/* =========================================================
   CAMBIO DE IDIOMA
   ========================================================= */

function changeLanguage(language) {

    const elements =
        document.querySelectorAll("[data-es][data-en]");

    elements.forEach(function(element) {

        element.innerHTML =
            element.getAttribute(
                "data-" + language
            );

    });


    document.documentElement.lang =
        language;


    document
        .getElementById("esButton")
        .classList
        .toggle(
            "active",
            language === "es"
        );


    document
        .getElementById("enButton")
        .classList
        .toggle(
            "active",
            language === "en"
        );


    if (language === "es") {

        document.title =
            "APP MADRID 365 — Aplicaciones, software e innovación";

    } else {

        document.title =
            "APP MADRID 365 — Applications, software and innovation";

    }


    /* Guardamos el idioma elegido */

    localStorage.setItem(
        "appMadridLanguage",
        language
    );
}


/* =========================================================
   RECUPERAR IDIOMA
   ========================================================= */

document.addEventListener(
    "DOMContentLoaded",
    function() {

        const savedLanguage =
            localStorage.getItem(
                "appMadridLanguage"
            );

        if (savedLanguage) {

            changeLanguage(
                savedLanguage
            );

        }

    }
);

</script>


<script type="module" src="https://static.cloudflareinsights.com/beacon.min.js/v4bc70e2c01a94c73b74392e4234840661791215815920" integrity="sha512-L0ha0OXavK/8okipN9F8BtP84dg9DUhPERbBXzwI6dgTA55d2+yweo3pn5CSFYs45/r8md2+xvUPtTdvTNRfjA==" data-cf-beacon='{"version":"2024.11.0","token":"7d41285223a543d48165cd232af38432","r":1,"spa":2}' crossorigin="anonymous"></script>
</body>
</html>
