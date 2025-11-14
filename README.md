<!DOCTYPE html>
<html lang="pl">
<head>
<meta charset="UTF-8">
<title>Moja Strona PKP</title>

<style>
    body {
        margin: 0;
        background-color: #022f0f;
        font-family: Arial, sans-serif;
        color: #d6e6d6;
    }

    /* MENU GÓRNE */
    nav {
        background-color: #003b12;
        border-bottom: 3px solid #00280c;
        padding: 5px 20px;
        display: flex;
        align-items: center;
        gap: 20px;
        font-size: 18px;
        font-weight: bold;
    }

    nav a {
        color: #e2ffe2;
        text-decoration: none;
        padding: 6px 10px;
    }
    nav a:hover {
        background-color: #00551c;
    }

    /* LAYOUT GŁÓWNY – DWA PANELE */
    .container {
        display: flex;
        padding: 20px 40px;
    }

    .left {
        width: 65%;
    }

    .right {
        width: 30%;
        background-color: #00350f;
        padding: 15px;
        margin-left: 20px;
        border-left: 3px solid #00511a;
    }

    h1 {
        font-size: 36px;
        font-weight: bold;
        color: #c9d9c9;
    }

    h2 {
        font-size: 26px;
        margin-top: 30px;
        color: #e8ffe8;
    }

    ul {
        margin-top: 10px;
    }

    li {
        margin-bottom: 10px;
    }

    a {
        color: #7bcf7b;
    }

    .photo-header {
        width: 100%;
        height: 150px;
        background-image: url("twoje_zdjecie.jpg"); /* podmień */
        background-size: cover;
        background-position: center;
        border-bottom: 4px solid #004519;
    }

</style>
</head>
<body>

<!-- DUŻE ZDJĘCIE NA GÓRZE -->
<div class="photo-header"></div>

<!-- MENU -->
<nav>
    <a href="#">Strona główna</a>
    <a href="#">Opisy wagonów</a>
    <a href="#">Składy pociągów</a>
    <a href="#">Galeria</a>
    <a href="#">Artykuły</a>
    <a href="#">Inne</a>
</nav>

<div class="container">

    <!-- LEWA STRONA -->
    <div class="left">
        <h1>Moja strona PKP</h1>

        <p>Witaj! Ta strona jest poświęcona historii taboru kolejowego, składom pociągów oraz ciekawym materiałom dla pasjonatów PKP i kolei europejskich.</p>
        
        <h2>Aktualności</h2>
        <ul>
            <li><b>13.11.2025</b> — Aktualizacja galerii wagonów polskich.</li>
            <li><b>28.10.2025</b> — Dodano składy pociągów z lat 90.</li>
            <li><b>12.10.2025</b> — Nowe opisy wagonów 111A/112A.</li>
            <li><b>30.09.2025</b> — Fotorelacja z targów TRAKO.</li>
        </ul>
    </div>

    <!-- PRAWA KOLUMNA (panel jak na vagonWEB) -->
    <div class="right">
        <h2>Nowe składy 2025</h2>
        <ul>
            <li><a href="#">TLK 35170</a></li>
            <li><a href="#">IC 4500</a></li>
            <li><a href="#">EIP 1800</a></li>
            <li><a href="#">R 60900</a></li>
        </ul>

        <h2>Realne składy</h2>
        <ul>
            <li><a href="#">Os 46026</a></li>
            <li><a href="#">IR 50646</a></li>
            <li><a href="#">R 55720</a></li>
        </ul>
    </div>

</div>

</body>
</html>
