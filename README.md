<!DOCTYPE html>
<html lang="pt-pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MetaPub | Domine o Digital</title>
    <style>
        :root {
            --primary: #2563eb;
            --dark: #1e293b;
            --light: #f8fafc;
            --accent: #0ea5e9;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: var(--light);
            color: var(--dark);
            line-height: 1.6;
        }

        /* Hero Section */
        header {
            background: linear-gradient(135deg, #1e293b 0%, #0f172a 100%);
            color: white;
            padding: 80px 20px;
            text-align: center;
        }

        .container {
            max-width: 1100px;
            margin: 0 auto;
        }

        h1 {
            font-size: 3rem;
            margin-bottom: 20px;
            background: linear-gradient(to right, #60a5fa, #0ea5e9);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .description {
            font-size: 1.2rem;
            max-width: 700px;
            margin: 0 auto 30px;
            color: #cbd5e1;
        }

        .cta-button {
            display: inline-block;
            background-color: var(--primary);
            color: white;
            padding: 15px 35px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: bold;
            transition: transform 0.3s ease;
            box-shadow: 0 4px 15px rgba(37, 99, 235, 0.4);
        }

        .cta-button:hover {
            transform: translateY(-3px);
            background-color: #1d4ed8;
        }

        /* Benefícios */
        .features {
            padding: 80px 20px;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
        }

        .feature-card {
            background: white;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 10px 20px rgba(0,0,0,0.05);
            text-align: center;
        }

        .feature-card h3 {
            margin-bottom: 15px;
            color: var(--primary);
        }

        /* Prova Social */
        .social-proof {
            background-color: #f1f5f9;
            padding: 60px 20px;
            text-align: center;
        }

        .stats {
            display: flex;
            justify-content: center;
            gap: 50px;
            margin-top: 30px;
            flex-wrap: wrap;
        }

        .stat-item h2 {
            font-size: 2.5rem;
            color: var(--dark);
        }

        /* Footer / Final CTA */
        footer {
            padding: 60px 20px;
            text-align: center;
            background: white;
        }

        .contact-info {
            margin-top: 20px;
            font-weight: bold;
            font-size: 1.1rem;
        }

        @media (max-width: 768px) {
            h1 { font-size: 2rem; }
        }
    </style>
</head>
<body>

    <header>
        <div class="container">
            <p style="text-transform: uppercase; letter-spacing: 2px; color: var(--accent); margin-bottom: 10px;">MetaPub Agência Digital</p>
            <h1>Transforme cliques em clientes com anúncios de alta performance</h1>
            <p class="description">Escalamos o seu negócio através de estratégias personalizadas de tráfego pago nas maiores plataformas do mundo.</p>
            <a href="https://wa.me/258852377698" class="cta-button">Quero Vender Mais Agora</a>
        </div>
    </header>

    <section class="container features">
        <div class="feature-card">
            <h3>Alcance Global</h3>
            <p>Colocamos a sua marca onde o seu cliente está, seja no Instagram, Facebook ou Google.</p>
        </div>
        <div class="feature-card">
            <h3>Público Qualificado</h3>
            <p>Não apenas visitas, mas pessoas prontas para comprar o seu produto ou serviço.</p>
        </div>
        <div class="feature-card">
            <h3>ROI Otimizado</h3>
            <p>Foco total no retorno do seu investimento com relatórios de performance semanais.</p>
        </div>
    </section>

    <section class="social-proof">
        <div class="container">
            <h2>Resultados que falam por nós</h2>
            <div class="stats">
                <div class="stat-item">
                    <h2>+50</h2>
                    <p>Clientes Satisfeitos</p>
                </div>
                <div class="stat-item">
                    <h2>100%</h2>
                    <p>Foco em Conversão</p>
                </div>
                <div class="stat-item">
                    <h2>24/7</h2>
                    <p>Suporte Especializado</p>
                </div>
            </div>
        </div>
    </section>

    <footer>
        <div class="container">
            <h2>Pronto para elevar o nível do seu negócio?</h2>
            <p>Fale diretamente com um especialista da MetaPub.</p>
            <br>
            <a href="https://wa.me/258852377698" class="cta-button">Enviar Mensagem no WhatsApp</a>
            <p class="contact-info">Contacto: 852377698</p>
        </div>
    </footer>

</body>
</html># Landing-page-
Landing page para agência de publicidade digital 
