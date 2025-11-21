<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Portfolio BTS SIO option SISR — administration systèmes et réseaux, cybersécurité, virtualisation.">
    <title>Portfolio BTS SIO SISR</title>
    <style>
        :root {
            --bg: #f5f5f5;
            --primary: #1e3a5f;
            --dark: #14253d;
            --card: #ffffff;
            --text: #333;
        }
        html, body {
            height: 100%;
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
            background: var(--bg);
            color: var(--text);
        }

        .skip-link {
            position: absolute;
            left: -999px;
            top: auto;
            width: 1px;
            height: 1px;
            overflow: hidden;
        }
        .skip-link:focus {
            left: 1rem;
            top: 1rem;
            width: auto;
            height: auto;
            padding: 0.5rem;
            background: #fff;
            border: 2px solid var(--primary);
            z-index: 100;
        }

        header {
            background: var(--primary);
            padding: 40px 20px;
            text-align: center;
            color: white;
        }

        header h1 {
            font-size: 2.2rem;
            margin: 0;
        }

        nav {
            background: var(--dark);
            padding: 12px;
        }

        nav ul {
            margin: 0;
            padding: 0;
            list-style: none;
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
        }

        nav li {
            margin: 6px 12px;
        }

        nav a {
            color: white;
            text-decoration: none;
            font-size: 1rem;
        }

        nav a:hover,
        nav a:focus {
            text-decoration: underline;
        }

        main {
            max-width: 900px;
            margin: 30px auto;
            padding: 0 15px;
        }

        section.card {
            background: var(--card);
            padding: 25px;
            border-radius: 8px;
            box-shadow: 0 0 8px rgba(0,0,0,0.07);
            margin-bottom: 20px;
        }

        h2 {
            color: var(--primary);
        }

        .project {
            border-left: 5px solid var(--primary);
            padding-left: 15px;
            margin-bottom: 12px;
        }

        footer {
            background: var(--dark);
            padding: 20px;
            text-align: center;
            color: white;
            margin-top: 40px;
        }

        /* Responsive tweaks */
        @media (max-width: 480px) {
            header h1 { font-size: 1.5rem; }
            nav a { font-size: 0.95rem; }
        }
    </style>
</head>
<body>
    <a class="skip-link" href="#main">Aller au contenu</a>

    <header>
        <h1>Portfolio BTS SIO SISR</h1>
        <p>Site web professionnel hébergé sur GitHub Pages</p>
    </header>

    <nav aria-label="Navigation principale">
        <ul>
            <li><a href="#presentation">Présentation</a></li>
            <li><a href="#competences">Compétences</a></li>
            <li><a href="#projets">Projets</a></li>
            <li><a href="#veille">Veille</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <main id="main">
        <section id="presentation" class="card">
            <h2>Présentation</h2>
            <p>Bonjour, je suis <strong>[Ton Nom]</strong>, étudiant en BTS Services Informatiques aux Organisations, option SISR.
            Je suis passionné par l'administration des systèmes et réseaux, la cybersécurité et la virtualisation.</p>
        </section>

        <section id="competences" class="card">
            <h2>Compétences</h2>
            <ul>
                <li>Windows Server (AD, DNS, DHCP, GPO)</li>
                <li>Linux (Ubuntu, Debian)</li>
                <li>Réseaux : VLAN, routage, firewall</li>
                <li>Virtualisation : VMware, Proxmox</li>
                <li>Supervision : Centreon, Grafana</li>
                <li>Scripts Bash / PowerShell</li>
                <li>Support utilisateur & ITIL (GLPI)</li>
            </ul>
        </section>

        <section id="projets" class="card">
            <h2>Projets</h2>

            <div class="project">
                <h3>Déploiement d'un Active Directory</h3>
                <p>Installation, configuration et gestion d'un AD DS avec DNS, DHCP, OU et GPO.</p>
            </div>

            <div class="project">
                <h3>Supervision d'un réseau avec Centreon</h3>
                <p>Configuration d'hôtes, analyse d'indicateurs (CPU, RAM, services), alertes par mail.</p>
            </div>

            <div class="project">
                <h3>Mise en place d'un serveur Web Linux</h3>
                <p>Installation Apache/PHP/MySQL, configuration SSL, durcissement SSH, pare-feu UFW.</p>
            </div>
        </section>

        <section id="veille" class="card">
            <h2>Veille Technologique</h2>
            <p><strong>Thème :</strong> [ex : Cybersécurité des infrastructures]</p>
            <p><strong>Outils :</strong> Google Alerts, RSS, Zataz, ANSSI, CertFR.</p>
            <p><strong>Résumé :</strong> Analyse des nouvelles menaces réseau et impacts sur les entreprises.</p>
        </section>

        <section id="contact" class="card">
            <h2>Contact</h2>
            <p>Email : <strong>ton.email@example.com</strong></p>
            <p>GitHub : <a href="https://github.com/tonpseudo" target="_blank" rel="noopener noreferrer">github.com/tonpseudo</a></p>
            <p>LinkedIn : <a href="#" target="_blank" rel="noopener noreferrer">Ton Profil LinkedIn</a></p>
        </section>
    </main>

    <footer>
        © 2025 - Portfolio BTS SIO SISR
    </footer>
</body>
</html>
