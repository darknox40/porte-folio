# porte-folio
 http://90.54.64.253:5500
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Expertise Sécurité Hospitalière</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
    <style>
        :root {
            --primary: #005f73;
            --secondary: #0a9396;
            --accent: #ee9b00;
            --dark: #001219;
            --light: #e9d8a6;
            --danger: #ae2012;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #f8f9fa;
            color: #333;
            line-height: 1.7;
        }

        .security-container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem;
        }

        header {
            background: linear-gradient(135deg, var(--primary), var(--secondary));
            color: white;
            padding: 3rem 2rem;
            text-align: center;
            border-radius: 0 0 20px 20px;
            margin-bottom: 3rem;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
            position: relative;
            overflow: hidden;
        }

        header::after {
            content: "";
            position: absolute;
            bottom: 0;
            left: 0;
            width: 100%;
            height: 5px;
            background: var(--accent);
        }

        h1 {
            font-size: 2.8rem;
            margin-bottom: 1rem;
        }

        .tagline {
            font-size: 1.2rem;
            opacity: 0.9;
            max-width: 800px;
            margin: 0 auto;
        }

        .security-badge {
            display: inline-block;
            background-color: var(--danger);
            color: white;
            padding: 0.5rem 1rem;
            border-radius: 50px;
            font-weight: bold;
            margin-top: 1.5rem;
            font-size: 0.9rem;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.2);
        }

        .expertise-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 2rem;
            margin: 3rem 0;
        }

        .expertise-card {
            background: white;
            border-radius: 12px;
            padding: 2rem;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
            transition: transform 0.3s, box-shadow 0.3s;
            border-left: 5px solid var(--accent);
        }

        .expertise-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.1);
        }

        .expertise-card h2 {
            color: var(--primary);
            margin-bottom: 1rem;
            display: flex;
            align-items: center;
            gap: 0.8rem;
        }

        .expertise-card h2 i {
            color: var(--accent);
            font-size: 1.5rem;
        }

        .task-list {
            list-style-type: none;
        }

        .task-item {
            padding: 0.8rem 0;
            border-bottom: 1px dashed #eee;
            display: flex;
            align-items: flex-start;
            gap: 0.8rem;
        }

        .task-item:last-child {
            border-bottom: none;
        }

        .task-item i {
            color: var(--secondary);
            margin-top: 0.3rem;
        }

        .achievements {
            background: linear-gradient(135deg, var(--dark), var(--primary));
            color: white;
            padding: 3rem 2rem;
            border-radius: 20px;
            margin: 4rem 0;
            position: relative;
            overflow: hidden;
        }

        .achievements::before {
            content: "";
            position: absolute;
            top: 0;
            right: 0;
            width: 150px;
            height: 150px;
            background: radial-gradient(circle, rgba(238,155,0,0.2) 0%, rgba(238,155,0,0) 70%);
        }

        .achievements h2 {
            font-size: 2rem;
            margin-bottom: 1.5rem;
            position: relative;
            display: inline-block;
        }

        .achievements h2::after {
            content: "";
            position: absolute;
            bottom: -10px;
            left: 0;
            width: 80px;
            height: 4px;
            background: var(--accent);
            border-radius: 2px;
        }

        .stats-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }

        .stat-item {
            text-align: center;
            padding: 1.5rem;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 10px;
            backdrop-filter: blur(5px);
        }

        .stat-number {
            font-size: 2.5rem;
            font-weight: bold;
            color: var(--accent);
            margin-bottom: 0.5rem;
        }

        footer {
            text-align: center;
            padding: 2rem;
            color: #666;
            font-size: 0.9rem;
        }

        @media (max-width: 768px) {
            h1 {
                font-size: 2rem;
            }
            
            .expertise-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="security-container">
        <header>
            <h1><i class="fas fa-shield-alt"></i>M'es Service Hospitalière LADOIS Noa</h1>
            <p class="tagline">Gestion avancée des systèmes d'information et protection des données sensibles en milieu hospitalier</p>
            <div class="security-badge">Apprentissage : Bien</div>
        </header>

        <div class="expertise-grid">
            <div class="expertise-card">
                <h2><i class="fas fa-user-shield"></i> Gestion des Accès</h2>
                <ul class="task-list">
                    <li class="task-item">
                        <i class="fas fa-check-circle"></i>
                        <span>Configuration et gestion des habilitations du personnel</span>
                    </li>
                    <li class="task-item">
                        <i class="fas fa-check-circle"></i>
                        <span>Mise en place d'un système d'authentification forte à 2 facteurs</span>
                    </li>
                    <li class="task-item">
                        <i class="fas fa-check-circle"></i>
                        <span>Metre un mot de passe au BIOS d'une machine</span>
                    </li>
                    <li class="task-item">
                        <i class="fas fa-check-circle"></i>
                        <span>Gestion des sessions utilisateurs</span>
                    </li>
                </ul>
            </div>


            <div class="expertise-card">
                <h2><i class="fas fa-tools"></i> Interventions Techniques</h2>
                <ul class="task-list">
                    <li class="task-item">
                        <i class="fas fa-check-circle"></i>
                        <span>Préparation et déploiement de postes TicTacPhone sécurisés</span>
                    </li>
                    <li class="task-item">
                        <i class="fas fa-check-circle"></i>
                        <span>Diagnostic et résolution des pannes réseau mineur</span>
                    </li>
                    <li class="task-item">
                        <i class="fas fa-check-circle"></i>
                        <span>Contrôle et mise à jour des politiques de sécurité</span>
                    </li>
                    <li class="task-item">
                        <i class="fas fa-check-circle"></i>
                        <span>Remplassage d'écran, clavier, souri</span>
                    </li>
                </ul>
            </div>
        </div>

        <div class="achievements">
            <h2>Réalisations Clés</h2>
            <p>Au cours de mes missions en établissement hospitalier, j'ai mis en œuvre des solutions de sécurité avancées permettant de protéger les données sensibles tout en maintenant une accessibilité optimale pour le personnel médical.</p>
            
            <div class="stats-grid">
                <div class="stat-item">
                    <div class="stat-number">100%</div>
                    <div>Des ports USB sécurisés</div>
                </div>
                <div class="stat-item">
                    <div class="stat-number">24/7</div>
                    <div>Surveillance des accès avec les logiciels</div>
                </div>
                <div class="stat-item">
                    <div class="stat-number">40</div>
                    <div>Postes TicTacPhone déployés</div>
                </div>
                <div class="stat-item">
                    <div class="stat-number">0</div>
                    <div>Incident majeur depuis mise en œuvre</div>
                </div>
            </div>
        </div>

        <footer>
            <p>2025 - LADOIS Noa</p>
           
        </footer>
    </div>
</body>
</html>
