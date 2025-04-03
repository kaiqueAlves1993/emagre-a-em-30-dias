<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Emagreça em 30 Dias - O Guia Definitivo</title>
    <style>
        :root {
            --primary: #e74c3c;
            --secondary: #2c3e50;
            --accent: #27ae60;
            --light: #f8f9fa;
            --dark: #333;
        }
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: var(--dark);
            max-width: 1000px;
            margin: 0 auto;
            padding: 0 20px;
        }
        header {
            text-align: center;
            padding: 40px 0;
            margin-bottom: 30px;
            background: linear-gradient(135deg, var(--primary), var(--secondary));
            color: white;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }
        h1 {
            font-size: 2.8em;
            margin-bottom: 10px;
            text-shadow: 1px 1px 3px rgba(0,0,0,0.3);
        }
        .subtitle {
            font-size: 1.3em;
            font-weight: 300;
        }
        h2 {
            color: var(--primary);
            border-left: 5px solid var(--primary);
            padding-left: 15px;
            margin-top: 40px;
        }
        .hero-image {
            max-width: 100%;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
            margin: 30px 0;
        }
        .urgency-banner {
            background-color: var(--primary);
            color: white;
            padding: 15px;
            text-align: center;
            border-radius: 5px;
            margin: 30px 0;
            font-weight: bold;
            animation: pulse 2s infinite;
        }
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.02); }
            100% { transform: scale(1); }
        }
        .benefits-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin: 30px 0;
        }
        .benefit-card {
            background-color: white;
            border-radius: 8px;
            padding: 20px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
            border-top: 4px solid var(--accent);
        }
        .benefit-card h3 {
            color: var(--secondary);
            margin-top: 0;
        }
        .price-box {
            background-color: var(--secondary);
            color: white;
            padding: 30px;
            text-align: center;
            border-radius: 10px;
            margin: 40px 0;
            position: relative;
            overflow: hidden;
        }
        .price-box::before {
            content: "";
            position: absolute;
            top: -10px;
            right: -10px;
            width: 100px;
            height: 100px;
            background-color: var(--primary);
            transform: rotate(45deg);
            z-index: 0;
        }
        .old-price {
            text-decoration: line-through;
            font-size: 1.2em;
            opacity: 0.8;
        }
        .new-price {
            font-size: 2.5em;
            font-weight: bold;
            margin: 10px 0;
        }
        .installments {
            font-size: 1.1em;
        }
        .cta-button {
            display: inline-block;
            background-color: var(--accent);
            color: white;
            padding: 18px 40px;
            text-decoration: none;
            font-weight: bold;
            border-radius: 50px;
            margin: 20px 0;
            font-size: 1.2em;
            transition: all 0.3s;
            box-shadow: 0 4px 0 rgba(39, 174, 96, 0.4);
            text-transform: uppercase;
            letter-spacing: 1px;
        }
        .cta-button:hover {
            background-color: #2ecc71;
            transform: translateY(-3px);
            box-shadow: 0 7px 0 rgba(39, 174, 96, 0.4);
        }
        .testimonials {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin: 40px 0;
        }
        .testimonial {
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
            position: relative;
        }
        .testimonial::before {
            content: """;
            font-size: 80px;
            color: var(--primary);
            opacity: 0.2;
            position: absolute;
            top: -20px;
            left: 10px;
        }
        .testimonial-author {
            font-weight: bold;
            color: var(--secondary);
            margin-top: 15px;
            display: block;
        }
        .bonuses {
            background-color: var(--light);
            padding: 30px;
            border-radius: 10px;
            margin: 40px 0;
        }
        .bonus-item {
            display: flex;
            align-items: center;
            margin-bottom: 20px;
        }
        .bonus-icon {
            background-color: var(--primary);
            color: white;
            width: 40px;
            height: 40px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-right: 15px;
            flex-shrink: 0;
            font-weight: bold;
        }
        .guarantee-badge {
            display: flex;
            align-items: center;
            justify-content: center;
            background-color: var(--light);
            padding: 20px;
            border-radius: 10px;
            margin: 40px 0;
            text-align: center;
        }
        .guarantee-badge img {
            margin-right: 20px;
            max-width: 100px;
        }
        .faq {
            margin: 40px 0;
        }
        .faq-item {
            margin-bottom: 15px;
            border-bottom: 1px solid #eee;
            padding-bottom: 15px;
        }
        .faq-question {
            font-weight: bold;
            color: var(--secondary);
            margin-bottom: 10px;
        }
        footer {
            text-align: center;
            margin-top: 50px;
            padding: 20px;
            font-size: 0.9em;
            color: #7f8c8d;
            border-top: 1px solid #eee;
        }
        @media (max-width: 768px) {
            h1 {
                font-size: 2em;
            }
            .subtitle {
                font-size: 1.1em;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>EMAGREÇA EM 30 DIAS</h1>
        <p class="subtitle">O Método Cientificamente Comprovado Para Perder Peso Sem Passar Fome</p>
    </header>

    <div style="text-align: center;">
        <img src="https://images.unsplash.com/photo-1535914254981-b5012eebbd15" alt="Transformação corporal" class="hero-image">
    </div>

    <div class="urgency-banner">
        ATENÇÃO: OFERTA POR TEMPO LIMITADO - GARANTA SEU EBOOK HOJE COM 50% DE DESCONTO!
    </div>

    <h2>O Que Você Vai Aprender Neste Guia Completo</h2>
    
    <div class="benefits-grid">
        <div class="benefit-card">
            <h3>Plano Alimentar Detalhado</h3>
            <p>Descubra exatamente o que comer em cada refeição para acelerar seu metabolismo e queimar gordura de forma eficiente.</p>
        </div>
        <div class="benefit-card">
            <h3>Treinos Eficientes</h3>
            <p>Exercícios que você pode fazer em casa ou na academia para maximizar a queima de gordura em apenas 20-30 minutos por dia.</p>
        </div>
        <div class="benefit-card">
            <h3>Controle Hormonal</h3>
            <p>Aprenda a regular seus hormônios para reduzir o acúmulo de gordura e controlar a fome emocional.</p>
        </div>
        <div class="benefit-card">
            <h3>Mindset Vencedor</h3>
            <p>Técnicas psicológicas comprovadas para manter a motivação e superar recaídas durante os 30 dias.</p>
        </div>
        <div class="benefit-card">
            <h3>Receitas Poderosas</h3>
            <p>Mais de 50 receitas deliciosas e fáceis que aceleram o emagrecimento e saciam sua fome.</p>
        </div>
        <div class="benefit-card">
            <h3>Monitoramento de Progresso</h3>
            <p>Sistemas práticos para acompanhar seus resultados e ajustar sua estratégia quando necessário.</p>
        </div>
    </div>

    <div class="price-box">
        <p>De <span class="old-price">R$97,00</span> por apenas</p>
        <p class="new-price">R$47,00</p>
        <p class="installments">ou 12x de R$4,90 no cartão</p>
        <a href="#comprar" class="cta-button">QUERO MEU EBOOK AGORA!</a>
    </div>

    <h2>Histórias Reais de Transformação</h2>
    
    <div class="testimonials">
        <div class="testimonial">
            "Depois de anos tentando emagrecer sem sucesso, finalmente consegui perder 7kg em 30 dias seguindo o método à risca. Minha autoestima nunca esteve tão alta!"
            <span class="testimonial-author">- Ana Clara, 32 anos</span>
        </div>
        <div class="testimonial">
            "O que mais me impressionou foi como consegui emagrecer sem passar fome. As receitas são deliciosas e os exercícios cabem na minha rotina corrida. Perdi 5kg e ganhei muita energia!"
            <span class="testimonial-author">- Carlos Eduardo, 41 anos</span>
        </div>
        <div class="testimonial">
            "Comprei vários ebooks antes, mas este foi o único que realmente me mostrou um caminho claro. Em um mês reduzi 8cm de cintura e finalmente me sinto bem com meu corpo!"
            <span class="testimonial-author">- Juliana Santos, 28 anos</span>
        </div>
    </div>

    <h2>Bônus Exclusivos (Limitados)</h2>
    
    <div class="bonuses">
        <div class="bonus-item">
            <div class="bonus-icon">1</div>
            <div>
                <strong>Guia de Exercícios em Casa (20 minutos por dia)</strong> - Treinos eficientes que não exigem equipamentos para você fazer no conforto do seu lar.
            </div>
        </div>
        <div class="bonus-item">
            <div class="bonus-icon">2</div>
            <div>
                <strong>Lista de Compras Saudáveis</strong> - Um planejamento completo do que comprar no mercado para manter sua dieta sem complicações.
            </div>
        </div>
        <div class="bonus-item">
            <div class="bonus-icon">3</div>
            <div>
                <strong>Acesso ao Grupo VIP</strong> - Suporte diário em nosso grupo exclusivo no WhatsApp com nutricionistas e outros participantes.
            </div>
        </div>
    </div>

    <div class="guarantee-badge">
        <img src="https://via.placeholder.com/100x100" alt="Garantia">
        <div>
            <h3>Garantia Incondicional de 7 Dias</h3>
            <p>Se por qualquer motivo você não ficar 100% satisfeito(a) com o conteúdo, basta nos enviar um email dentro de 7 dias e devolveremos todo seu dinheiro sem questionamentos.</p>
        </div>
    </div>

    <h2>Perguntas Frequentes</h2>
    
    <div class="faq">
        <div class="faq-item">
            <div class="faq-question">Preciso fazer exercícios pesados para ter resultados?</div>
            <p>Não! O método foi desenvolvido para pessoas com diferentes níveis de condicionamento físico. Você pode adaptar os exercícios conforme sua capacidade atual.</p>
        </div>
        <div class="faq-item">
            <div class="faq-question">Vou precisar comprar alimentos caros ou difíceis de encontrar?</div>
            <p>Absolutamente não. Todas as receitas utilizam ingredientes comuns que você encontra em qualquer mercado, sem produtos milagrosos ou importados.</p>
        </div>
        <div class="faq-item">
            <div class="faq-question">Como receberei o ebook após a compra?</div>
            <p>Imediatamente após a confirmação do pagamento, você receberá um email com o link para download do ebook em PDF, que pode ser lido em qualquer dispositivo.</p>
        </div>
        <div class="faq-item">
            <div class="faq-question">E se eu não conseguir seguir o plano à risca?</div>
            <p>O método foi criado para ser flexível. Mesmo que você não consiga seguir 100%, ainda terá resultados significativos. Além disso, nosso grupo de suporte está sempre disponível para ajudar.</p>
        </div>
    </div>

    <h2 id="comprar">Não Adie Sua Transformação!</h2>
    <p>A cada dia que você espera, está perdendo tempo precioso que poderia estar mais perto do corpo dos seus sonhos. Seu futuro mais saudável começa AGORA!</p>

    <div class="price-box">
        <p>Oferta válida por tempo limitado</p>
        <p class="new-price">R$47,00</p>
        <p class="installments">ou 12x de R$4,90 no cartão</p>
        <a href="#comprar" class="cta-button">SIM, QUERO EMAGRECER AGORA!</a>
    </div>

    <footer>
        <p>© 2023 Emagreça em 30 Dias | Todos os direitos reservados</p>
        <p><a href="#">Termos de Uso</a> | <a href="#">Política de Privacidade</a> | <a href="#">Contato</a></p>
        <p><small>Este produto não substitui o acompanhamento de um profissional de saúde. Os resultados podem variar de acordo com cada indivíduo.</small></p>
    </footer>
</body>
</html>
