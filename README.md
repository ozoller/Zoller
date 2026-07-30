<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>eZoller GmbH – Digitale Zollarabwicklung & Logistik</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header class="navbar">
        <div class="container nav-container">
            <a href="#" class="logo">eZoller<span>GmbH</span></a>
            <nav>
                <ul class="nav-links" id="navLinks">
                    <li><a href="#home">Startseite</a></li>
                    <li><a href="#services">Dienstleistungen</a></li>
                    <li><a href="#about">Über uns</a></li>
                    <li><a href="#contact" class="btn-nav">Kontakt</a></li>
                </ul>
            </nav>
            <button class="burger" id="burger" aria-label="Menü öffnen">
                <div class="line"></div>
                <div class="line"></div>
                <div class="line"></div>
            </button>
        </div>
    </header>

    <section id="home" class="hero">
        <div class="container hero-content">
            <h1>Ihre Zolldeklaration. Einfach. Digital. Zuverlässig.</h1>
            <p>Die eZoller GmbH optimiert Ihre internationalen Handelsprozesse mit modernen und rechtssicheren Digitallösungen.</p>
            <a href="#contact" class="btn-primary">Jetzt Beratung anfordern</a>
        </div>
    </section>

    <section id="services" class="services">
        <div class="container">
            <h2>Unsere Dienstleistungen</h2>
            <div class="cards-grid">
                <div class="card">
                    <h3>Import- & Exportabwicklung</h3>
                    <p>Reibungslose Zollarabwicklung für Ihre Wareneinfuhr und -ausfuhr nach aktuellen Compliance-Standards.</p>
                </div>
                <div class="card">
                    <h3>Digitales Zollmanagement</h3>
                    <p>Automatisierte Schnittstellen und Prozesse zur Minimierung von Standzeiten und Bürokratie.</p>
                </div>
                <div class="card">
                    <h3>Zollberatung & Audit</h3>
                    <p>Strategische Beratung zur Optimierung von Abgaben, Tarifierung und Freihandelsabkommen.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="about" class="about">
        <div class="container">
            <h2>Über eZoller GmbH</h2>
            <p>Als erfahrener Partner im internationalen Handel verbinden wir tiefgreifendes Zoll-Know-how mit modernen digitalen Technologien. Unser Ziel ist es, globale Lieferketten effizienter und transparenter zu gestalten.</p>
        </div>
    </section>

    <section id="contact" class="contact">
        <div class="container">
            <h2>Kontaktieren Sie uns</h2>
            <form id="contactForm" class="contact-form">
                <div class="form-group">
                    <label for="name">Name</label>
                    <input type="text" id="name" required placeholder="Ihr Name">
                </div>
                <div class="form-group">
                    <label for="email">E-Mail</label>
                    <input type="email" id="email" required placeholder="ihre.adresse@firma.de">
                </div>
                <div class="form-group">
                    <label for="message">Nachricht</label>
                    <textarea id="message" rows="5" required placeholder="Wie können wir Ihnen helfen?"></textarea>
                </div>
                <button type="submit" class="btn-primary">Nachricht senden</button>
            </form>
        </div>
    </section>

    <footer>
        <div class="container footer-content">
            <p>&copy; 2026 eZoller GmbH. Alle Rechte vorbehalten.</p>
            <div class="footer-links">
                <a href="#">Impressum</a>
                <a href="#">Datenschutz</a>
            </div>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
