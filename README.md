<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lendário Studio - LuanGalaxy A Lenda</title>
    <style>
        :root {
            --primary-color: #6a0dad; /* Roxo temático do LuanGalaxy */
            --bg-color: #0a0a0a;
            --card-bg: #1a1a1a;
            --text-color: #ffffff;
            --accent-color: #ff0055;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-color);
            margin: 0;
            padding: 0;
        }

        header {
            background: linear-gradient(rgba(0,0,0,0.8), transparent);
            padding: 20px 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: fixed;
            width: 90%;
            z-index: 1000;
        }

        .logo {
            font-size: 1.8rem;
            font-weight: bold;
            color: var(--primary-color);
            text-transform: uppercase;
            letter-spacing: 2px;
        }

        .hero {
            height: 60vh;
            background: linear-gradient(to bottom, rgba(10,10,10,0.1), #0a0a0a), 
                        url('https://i.ytimg.com/vi/T629vDMgxf8/maxresdefault.jpg');
            background-size: cover;
            background-position: center;
            display: flex;
            flex-direction: column;
            justify-content: center;
            padding: 0 5%;
        }

        .hero h1 {
            font-size: 3.5rem;
            margin-bottom: 10px;
            text-shadow: 2px 2px 10px rgba(0,0,0,0.8);
        }

        .container {
            padding: 40px 5%;
        }

        .section-title {
            border-left: 5px solid var(--primary-color);
            padding-left: 15px;
            margin-bottom: 30px;
            font-size: 1.5rem;
        }

        .movie-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 25px;
        }

        .episode-card {
            background: var(--card-bg);
            border-radius: 10px;
            overflow: hidden;
            transition: transform 0.3s;
            border: 1px solid #333;
        }

        .episode-card:hover {
            transform: scale(1.03);
            border-color: var(--primary-color);
        }

        .video-container {
            position: relative;
            padding-bottom: 56.25%; /* 16:9 */
            height: 0;
        }

        .video-container iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
        }

        .info {
            padding: 20px;
        }

        .info h3 {
            margin-top: 0;
            color: var(--primary-color);
        }

        .badge {
            background: var(--primary-color);
            padding: 3px 8px;
            border-radius: 4px;
            font-size: 0.8rem;
            margin-bottom: 10px;
            display: inline-block;
        }

        .production-info {
            background: #252525;
            padding: 10px;
            border-radius: 5px;
            font-size: 0.9rem;
            margin-top: 15px;
            border-left: 3px solid var(--accent-color);
        }

        footer {
            text-align: center;
            padding: 40px;
            background: #000;
            margin-top: 50px;
            color: #666;
        }
    </style>
</head>
<body>

    <header>
        <div class="logo">Lendário Studio</div>
    </header>

    <section class="hero">
        <span class="badge">Série Completa</span>
        <h1>LuanGalaxy: A Lenda</h1>
        <p>Acompanhe a saga épica de Luan contra o seu maior inimigo em Minecraft.</p>
    </section>

    <div class="container">
        <h2 class="section-title">Episódios Disponíveis</h2>
        
        <div class="movie-grid">
            
            <div class="episode-card">
                <div class="video-container">
                    <iframe src="https://www.youtube.com/embed/T629vDMgxf8" frameborder="0" allowfullscreen></iframe>
                </div>
                <div class="info">
                    <h3>Episódio 1: O Retorno</h3>
                    <p><strong>Descrição:</strong> Luan Galaxy foi preso em uma prisão de Bedrock pelo seu reverso. Ele precisa de ajuda antes que o tempo acabe!</p>
                    <div class="production-info">
                        <strong>Produção:</strong> Lendário Studio Filmes <br>
                        <strong>Direção:</strong> LuanGalaxy
                    </div>
                </div>
            </div>

            <div class="episode-card">
                <div class="video-container">
                    <iframe src="https://www.youtube.com/embed/QzDVjwbGgWM" frameborder="0" allowfullscreen></iframe>
                </div>
                <div class="info">
                    <h3>Episódio 2: Prisão Perigosa</h3>
                    <p><strong>Descrição:</strong> A prisão se tornou mais perigosa. Com guardas e apenas pão para sobreviver, o canal corre o risco de ser deletado.</p>
                    <div class="production-info">
                        <strong>Produção:</strong> Lendário Studio Filmes <br>
                        <strong>Efeitos:</strong> Equipe Lendário
                    </div>
                </div>
            </div>

            <div class="episode-card">
                <div class="video-container">
                    <iframe src="https://www.youtube.com/embed/1Co3vSUKFbE" frameborder="0" allowfullscreen></iframe>
                </div>
                <div class="info">
                    <h3>Episódio 3: O Domínio do Reverso</h3>
                    <p><strong>Descrição:</strong> O Luan Galaxy Reverso revela seus planos maléficos e as mudanças que fará no canal sob seu novo domínio.</p>
                    <div class="production-info">
                        <strong>Produção:</strong> Lendário Studio Filmes <br>
                        <strong>Roteiro:</strong> LuanGalaxy
                    </div>
                </div>
            </div>

            <div class="episode-card">
                <div class="video-container">
                    <iframe src="https://www.youtube.com/embed/aKG4CIE1ZT8" frameborder="0" allowfullscreen></iframe>
                </div>
                <div class="info">
                    <h3>Episódio Final: A Grande Fuga</h3>
                    <p><strong>Descrição:</strong> Usando uma picareta esquecida e habilidades de parkour sobre lava, Luan tenta recuperar sua liberdade.</p>
                    <div class="production-info">
                        <strong>Produção:</strong> Lendário Studio Filmes <br>
                        <strong>Finalização:</strong> LuanGalaxy Pro
                    </div>
                </div>
            </div>

        </div>
    </div>

    <footer>
        &copy; 2026 Lendário Studio Filmes. Todos os direitos reservados aos criadores.
    </footer>

</body>
</html>
