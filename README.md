<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Estatísticas das Coletas de Resíduos Sólidos em Itajaí - 2023</title>
    <style>
        body {
            font-family: 'Roboto', Arial, sans-serif;
            background-color: #e8ecef;
            color: #2d3748;
            margin: 0;
            padding: 40px;
            display: flex;
            flex-direction: column;
            align-items: center;
            line-height: 1.5;
        }
        .container {
            max-width: 1000px;
            width: 100%;
            background-color: #ffffff;
            padding: 40px;
            border-radius: 12px;
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15);
            text-align: center;
        }
        h1 {
            color: #1a3c34;
            font-size: 2.8em;
            margin-bottom: 15px;
            font-weight: 700;
        }
        .subtitle {
            font-size: 1.3em;
            color: #4a5568;
            margin-bottom: 30px;
            font-style: italic;
        }
        p {
            font-size: 1.15em;
            line-height: 1.8;
            margin-bottom: 25px;
            color: #4a5568;
            text-align: justify;
        }
        iframe {
            border: none;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            margin-top: 20px;
        }
        .links-container {
            margin-top: 40px;
            display: flex;
            justify-content: center;
            gap: 30px;
        }
        .link-item a {
            color: #2b6cb0;
            text-decoration: none;
            font-weight: 600;
            font-size: 1.1em;
            padding: 10px 20px;
            border: 2px solid #2b6cb0;
            border-radius: 8px;
            transition: all 0.3s ease;
        }
        .link-item a:hover {
            background-color: #2b6cb0;
            color: #ffffff;
            text-decoration: none;
        }
        .footer {
            margin-top: 40px;
            font-size: 0.9em;
            color: #718096;
            text-align: center;
        }
        .highlight {
            color: #276749;
            font-weight: bold;
        }
        @media (max-width: 768px) {
            .container {
                padding: 20px;
            }
            h1 {
                font-size: 2em;
            }
            .subtitle {
                font-size: 1.1em;
            }
            .links-container {
                flex-direction: column;
                gap: 15px;
            }
        }
    </style>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
</head>
<body>
    <div class="container">
        <h1>Estatísticas das Coletas de Resíduos Sólidos em Itajaí - 2023</h1>
        <p class="subtitle">Análise de Dados para Gestão Sustentável de Resíduos Urbanos</p>
        <p>Este painel interativo apresenta uma análise detalhada das coletas de resíduos sólidos realizadas na cidade de Itajaí ao longo do ano de 2023. Os dados compilados oferecem <span class="highlight">insights valiosos</span> sobre padrões de geração, coleta e destinação de resíduos, contribuindo para a formulação de políticas públicas voltadas à sustentabilidade e à gestão ambiental eficiente.</p>
        <iframe title="Relatório de Gestão de Resíduos - Itajaí 2023" width="100%" height="700"
                src="https://app.powerbi.com/view?r=eyJrIjoiNmE5Mjg0MzYtOGEwMy00NTQwLTk4N2ItZmZmOWY5N2MxNDA1IiwidCI6ImQwOTEwZmZkLThhMzctNGJkYi1iYTY1LTdkMmQwZWI1N2RlOSIsImMiOjR9"
                frameborder="0" allowFullScreen="true">
        </iframe>
    </div>
    <div class="links-container">
        <div class="link-item">
            <a href="https://www.figma.com/design/EYpnCF1nQVx4IImnt07TWi/Figma-HOW-IX?node-id=0-1&t=njW2rhOe8SPFUSLk-1" target="_blank">Protótipo no Figma</a>
        </div>
        <div class="link-item">
            <a href="https://handonworkix.atlassian.net/jira/software/projects/SCRUM/boards/1/backlog?atlOrigin=eyJpIjoiNGZlY2EwNmRjZmUyNDY2MzgxYTc4NDMwYTg0YTJjMmEiLCJwIjoiaiJ9" target="_blank">Quadro no Jira</a>
        </div>
    </div>
    <div class="footer">
        <p>Desenvolvido para fins acadêmicos e de pesquisa em gestão de resíduos sólidos urbanos.</p>
    </div>
</body>
</html>
