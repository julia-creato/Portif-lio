# Portif-lio
Portifólio pessoal com meus projetos 
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Portfólio</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #1e1e2f, #2e2e3f);
            color: #fff;
            min-height: 100vh;
            overflow-x: hidden;
            padding: 20px;
        }

        header {
            text-align: center;
            margin-bottom: 40px;
            animation: fadeIn 2s ease;
        }

        header h1 {
            font-size: 3em;
            color: #00d4ff;
        }

        header p {
            font-size: 1.2em;
            color: #ccc;
        }

        section {
            max-width: 800px;
            margin: 0 auto 60px;
            animation: slideUp 1.5s ease;
        }

        h2 {
            border-left: 4px solid #00d4ff;
            padding-left: 10px;
            margin-bottom: 20px;
            color: #00d4ff;
        }

        .project {
            background: #2b2b3b;
            padding: 20px;
            border-radius: 8px;
            margin-bottom: 20px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.3);
            transition: transform 0.3s;
        }

        .project:hover {
            transform: translateY(-5px);
        }

        footer {
            text-align: center;
            font-size: 0.9em;
            color: #aaa;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(-20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        @keyframes slideUp {
            from { opacity: 0; transform: translateY(40px); }
            to { opacity: 1; transform: translateY(0); }
        }
    </style>
</head>
<body>
    <header>
        <h1>Meu Portfólio</h1>
        <p>Desenvolvedor Front-End | Projetos com dedicação e criatividade</p>
    </header>

    <section>
        <h2>Projetos</h2>

        <div class="project">
            <h3>Projeto 1 - Landing Page</h3>
            <p>Uma landing page moderna e responsiva para apresentação de serviços.</p>
        </div>

        <div class="project">
            <h3>Projeto 2 - Portfólio Pessoal</h3>
            <p>Este próprio portfólio que você está visualizando, feito com animações e design limpo.</p>
        </div>

        <div class="project">
            <h3>Projeto 3 - Loja Virtual</h3>
            <p>Protótipo de uma loja virtual com carrinho de compras e layout responsivo.</p>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 - Meu Portfólio. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
