<!DOCTYPE html>
<html lang="sr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aleksa Nenadic</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #000;
            color: #fff;
            line-height: 1.6;
        }

        header {
            background: linear-gradient(135deg, #000 0%, #1a1a1a 100%);
            padding: 60px 20px;
            text-align: center;
            border-bottom: 3px solid #fff;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
        }

        h1 {
            font-size: 3em;
            margin-bottom: 10px;
            font-weight: 700;
            letter-spacing: 2px;
        }

        .subtitle {
            font-size: 1.3em;
            color: #ccc;
            margin-bottom: 20px;
        }

        .section {
            margin: 40px 0;
            padding: 30px;
            background-color: #0f0f0f;
            border-left: 4px solid #fff;
        }

        .section h2 {
            font-size: 2em;
            margin-bottom: 20px;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        .info-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin: 20px 0;
        }

        .info-item {
            background-color: #1a1a1a;
            padding: 20px;
            border: 1px solid #333;
        }

        .info-label {
            color: #999;
            font-size: 0.9em;
            text-transform: uppercase;
            letter-spacing: 1px;
            margin-bottom: 8px;
        }

        .info-value {
            font-size: 1.2em;
            font-weight: 600;
            word-break: break-word;
        }

        .contact-item {
            margin: 15px 0;
            padding: 15px;
            background-color: #1a1a1a;
            border-left: 3px solid #fff;
        }

        .contact-label {
            color: #999;
            font-size: 0.85em;
            text-transform: uppercase;
            margin-bottom: 5px;
        }

        .contact-value {
            font-size: 1.1em;
            font-weight: 500;
        }

        .hobby-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 15px;
            margin: 20px 0;
        }

        .hobby-item {
            background-color: #1a1a1a;
            padding: 20px;
            border: 2px solid #fff;
            text-align: center;
        }

        .hobby-item h3 {
            margin-bottom: 10px;
            font-size: 1.3em;
        }

        .hobby-item p {
            color: #bbb;
            font-size: 0.95em;
        }

        .profile-image {
            max-width: 70%;
            height: auto;
            border: 3px solid #fff;
            margin: 30px 0;
            display: block;
            margin-left: auto;
            margin-right: auto;
        }

        nav {
            display: flex;
            justify-content: center;
            gap: 30px;
            margin-top: 20px;
            padding-top: 20px;
            border-top: 1px solid #444;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            font-size: 1em;
            font-weight: 500;
            letter-spacing: 1px;
            text-transform: uppercase;
            padding: 10px 15px;
            border: 2px solid transparent;
            transition: all 0.3s ease;
        }

        nav a:hover {
            border: 2px solid #fff;
            padding: 10px 20px;
        }

        .marquee {
            background-color: #1a1a1a;
            border: 2px solid #fff;
            padding: 20px 0;
            overflow: hidden;
            margin: 40px 0;
        }

        .marquee-content {
            display: flex;
            animation: scroll-left 35s linear infinite;
            white-space: nowrap;
            font-size: 1.5em;
            font-weight: 600;
            letter-spacing: 2px;
            padding: 0 50px;
        }

        @keyframes scroll-left {
            0% {
                transform: translateX(100%);
            }
            100% {
                transform: translateX(-100%);
            }
        }

        footer {
            text-align: center;
            padding: 40px 20px;
            border-top: 3px solid #fff;
            color: #999;
            margin-top: 60px;
        }

        @media (max-width: 768px) {
            h1 {
                font-size: 2em;
            }

            .section {
                padding: 20px;
            }

            .section h2 {
                font-size: 1.5em;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>ALEKSA NENADIC</h1>
        <p class="subtitle">16 godina • Arilje</p>
        <nav>
            <a href="#about">O meni</a>
            <a href="#contact">Kontakt</a>
        </nav>
    </header>

    <div class="marquee">
        <div class="marquee-content">
             ALEKSA NENADIC          |          II4          |          INFORMATIČKA GIMNAZIJA          |          ARILJE          |          TRČANJE          |          LOTR & HOBBIT          |          
        </div>
    </div>

    <div class="container">
        <!-- O meni sekcija -->
        <section id="about" class="section">
            <h2>O meni</h2>
            <p>
                Učenik drugog razreda informatičke gimnazije "Sveti Sava" u Pozezi. Bavim se trčanjem i aktivno pratim kinematografiju i литературу, posebno fantastičnu.
            </p>
        </section>

        <!-- Osnovne informacije -->
        <section class="section">
            <h2>Osnovne informacije</h2>
            <div class="info-grid">
                <div class="info-item">
                    <div class="info-label">Puno ime</div>
                    <div class="info-value">Aleksa Nenadic</div>
                </div>
                <div class="info-item">
                    <div class="info-label">Razred</div>
                    <div class="info-value">II4</div>
                </div>
                <div class="info-item">
                    <div class="info-label">Škola</div>
                    <div class="info-value">Gimnazija "Sveti Sava" - Pozega</div>
                </div>
                <div class="info-item">
                    <div class="info-label">Datum rođenja</div>
                    <div class="info-value">29.12.2009.</div>
                </div>
                <div class="info-item">
                    <div class="info-label">Godina</div>
                    <div class="info-value">16 godina</div>
                </div>
                <div class="info-item">
                    <div class="info-label">Grad</div>
                    <div class="info-value">Arilje</div>
                </div>
            </div>
        </section>

        <!-- Kontakt -->
        <section id="contact" class="section">
            <h2>Kontakt</h2>
            <div class="contact-item">
                <div class="contact-label">Telefon</div>
                <div class="contact-value">0677633962</div>
            </div>
            <div class="contact-item">
                <div class="contact-label">Email</div>
                <div class="contact-value">aleksa.nenadic.09@gmail.com</div>
            </div>
        </section>

        <!-- Hobi - Trčanje -->
        <section class="section">
            <h2>Moji interesi</h2>
            
            <img src="aleksa.jpg.jpg" alt="Aleksa Nenadic running" class="profile-image">
            
            <h3 style="margin-top: 20px; margin-bottom: 15px;">Trčanje</h3>
            <div class="hobby-item">
                <h3>Polumaraton</h3>
                <p>Osobni rekord: <strong>1:30:11</strong></p>
            </div>

            <h3 style="margin-top: 25px; margin-bottom: 15px;">Omiljeni žanrovi</h3>
            <div class="hobby-container">
                <div class="hobby-item">
                    <h3>🖤 Horror</h3>
                </div>
                <div class="hobby-item">
                    <h3>🌌 Sci-Fi</h3>
                </div>
                <div class="hobby-item">
                    <h3>⚔️ Action</h3>
                </div>
            </div>

            <h3 style="margin-top: 25px; margin-bottom: 15px;">Omiljene knjige i serijale</h3>
            <div class="hobby-container">
                <div class="hobby-item">
                    <h3>Gospodar Prstenova</h3>
                    <p>J.R.R. Tolkien</p>
                </div>
                <div class="hobby-item">
                    <h3>Hobit</h3>
                    <p>J.R.R. Tolkien</p>
                </div>
            </div>
        </section>
    </div>

    <footer>
        <p>&copy; 2026 Aleksa Nenadic | Sva prava zadržana</p>
    </footer>
</body>
</html>
