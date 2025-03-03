# CSS
!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portal de Notícias</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background-color: #f4f4f4;
        }

        header {
            background: #333;
            color: white;
            padding: 15px 0;
            text-align: center;
        }

        nav {
            display: flex;
            justify-content: center;
            gap: 20px;
            background: #444;
            padding: 10px;
        }

        nav a {
            color: white;
            text-decoration: none;
            padding: 8px 16px;
        }

        nav a:hover {
            background: #666;
            border-radius: 5px;
        }

        .container {
            max-width: 1000px;
            margin: 20px auto;
            padding: 20px;
            background: white;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }

        .news-item {
            background: #fff;
            padding: 15px;
            border-radius: 5px;
            box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);
        }

        .news-item h2 {
            font-size: 18px;
            margin-bottom: 10px;
        }

        .news-item p {
            font-size: 14px;
            color: #555;
        }
    </style>
</head>
<body>
    <header>
        <h1>Portal de Notícias</h1>
    </header>
    <nav>
        <a href="#">Início</a>
        <a href="#">Entretenimento</a>
        <a href="#">Tecnologia</a>
        <a href="#">Esportes</a>
        <a href="#">Política</a>
    </nav>
    <div class="container">
        <h2>Últimas Notícias</h2>
        <div class="grid">
            <div class="news-item">
                <h2>Entretenimento: Novo filme é sucesso de bilheteria</h2>
                <p>O mais recente lançamento de Hollywood bate recordes de arrecadação.</p>
            </div>
            <div class="news-item">
                <h2>Tecnologia: Novo smartphone revolucionário</h2>
                <p>O modelo mais recente traz inovação e funcionalidades inéditas.</p>
            </div>
            <div class="news-item">
                <h2>Esportes: Campeonato em reta final</h2>
                <p>Times se enfrentam na última rodada para decidir o campeão.</p>
            </div>
        </div>
    </div>
</body>
</html>
