# E<!DOCTYPE html>
<html lang="de">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>East-Bikes - GTA Motorradshop</title>
    <style>
        * {
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: url('images/gta-background.jpg') no-repeat center center fixed;
            background-size: cover;
            color: #fff;
        }

        header {
            position: sticky;
            top: 0;
            background: rgba(0, 0, 0, 0.8);
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 10px 20px;
            z-index: 1000;
        }

        .logo-container {
            display: flex;
            align-items: center;
        }

        .logo {
            width: 50px;
            margin-right: 10px;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 10px;
            padding: 5px 10px;
            transition: 0.3s;
            border-radius: 5px;
        }

        nav a:hover {
            background: #e60000;
        }

        .hero {
            text-align: center;
            padding: 100px 20px;
            background: rgba(0, 0, 0, 0.6);
        }

        .hero h2 {
            font-size: 3em;
            color: #e60000;
        }

        .button {
            display: inline-block;
            margin-top: 20px;
            padding: 10px 20px;
            background: #e60000;
            color: #fff;
            text-decoration: none;
            border-radius: 5px;
            transition: 0.3s;
        }

        .button:hover {
            background: #ff1a1a;
            transform: scale(1.05);
        }

        .shop-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            padding: 20px;
        }

        .item {
            background: rgba(34, 34, 34, 0.8);
            border-radius: 10px;
            overflow: hidden;
            transition: 0.3s;
            text-align: center;
        }

        .item:hover {
            transform: scale(1.03);
            box-shadow: 0 0 10px #e60000;
        }

        .item img {
            width: 100%;
            height: 150px;
            object-fit: cover;
        }

        .item button {
            background: #e60000;
            border: none;
            color: #fff;
            padding: 10px;
            width: 90%;
            margin: 10px;
            border-radius: 5px;
            cursor: pointer;
            transition: 0.3s;
        }

        .item button:hover {
            background: #ff1a1a;
        }

        table {
            width: 100%;
            background: rgba(34, 34, 34, 0.8);
            border-collapse: collapse;
            margin-top: 20px;
        }

        th, td {
            padding: 10px;
            border: 1px solid #555;
        }

        footer {
            text-align: center;
            margin-top: 30px;
            padding: 20px;
            background: rgba(0, 0, 0, 0.8);
        }
    </style>
</head>

<body>
    <header>
        <div class="logo-container">
            <img src="images/east-bikes-logo.png" alt="East-Bikes Logo" class="logo">
            <h1>East-Bikes</h1>
        </div>
        <nav>
            <a href="#motorräder">Motorräder</a>
            <a href="#roller">Roller</a>
            <a href="#quads">Quads</a>
            <a href="#preise">Preise</a>
            <a href="#kontakt">Kontakt</a>
        </nav>
    </header>

    <section class="hero">
        <h2>Willkommen bei East-Bikes</h2>
        <p>Dein GTA 5 Motorradshop mit den besten Bikes, Scootern & Quads</p>
        <a href="#motorräder" class="button">Shop starten</a>
    </section>

    <section id="motorräder">
        <h2>Motorräder</h2>
        <div class="shop-grid">
            <div class="item">
                <img src="images/motorrad1.jpg" alt="Motorrad 1">
                <h3>Motorrad 1</h3>
                <p>Leistungsstark und stylisch.</p>
                <button>100.000 GTA$</button>
            </div>
            <div class="item">
                <img src="images/motorrad2.jpg" alt="Motorrad 2">
                <h3>Motorrad 2</h3>
                <p>Schnell & wendig.</p>
                <button>150.000 GTA$</button>
            </div>
        </div>
    </section>

    <section id="roller">
        <h2>Roller</h2>
        <div class="shop-grid">
            <div class="item">
                <img src="images/roller1.jpg" alt="Roller 1">
                <h3>Roller 1</h3>
                <p>Stadttauglicher Scooter.</p>
                <button>50.000 GTA$</button>
            </div>
        </div>
    </section>

    <section id="quads">
        <h2>Quads</h2>
        <div class="shop-grid">
            <div class="item">
                <img src="images/quad1.jpg" alt="Quad 1">
                <h3>Quad 1</h3>
                <p>Offroad Monster.</p>
                <button>120.000 GTA$</button>
            </div>
        </div>
    </section>

    <section id="preise">
        <h2>Preistabelle</h2>
        <table>
            <tr><th>Fahrzeug</th><th>Preis</th></tr>
            <tr><td>Motorrad 1</td><td>100.000 GTA$</td></tr>
            <tr><td>Motorrad 2</td><td>150.000 GTA$</td></tr>
            <tr><td>Roller 1</td><td>50.000 GTA$</td></tr>
            <tr><td>Quad 1</td><td>120.000 GTA$</td></tr>
        </table>
        <a href="downloads/preisliste.pdf" class="button" download>Preisliste Download</a>
    </section>

    <footer id="kontakt">
        <p>© 2025 East-Bikes | Kontakt: kontakt@east-bikes.com</p>
    </footer>
</body>

</html>
astBikes
