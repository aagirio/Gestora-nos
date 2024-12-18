<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Página profissional de Gestora de Negócios da NOS Empresas">
    <title>Gestora de Negócios - NOS Empresas</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #1E1E1E;
            color: #fff;
            text-align: center;
            padding: 20px 0;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
            padding: 10px;
        }
        nav a {
            color: #fff;
            padding: 10px 20px;
            text-decoration: none;
            font-size: 1.1em;
            margin: 0 15px;
        }
        nav a:hover {
            background-color: #555;
        }
        .container {
            width: 80%;
            margin: 30px auto;
        }
        .section {
            margin-bottom: 40px;
        }
        .section h2 {
            font-size: 2em;
            margin-bottom: 10px;
            color: #1E1E1E;
        }
        .service-list, .faq-list {
            list-style: none;
            padding: 0;
        }
        .service-list li, .faq-list li {
            margin-bottom: 15px;
            font-size: 1.1em;
        }
        .service-list li::before, .faq-list li::before {
            content: "•";
            margin-right: 10px;
            color: #1E1E1E;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        .contact-form button {
            background-color: #1E1E1E;
            color: #fff;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .contact-form button:hover {
            background-color: #555;
        }
        .social-links a {
            margin: 0 10px;
            font-size: 1.5em;
            color: #1E1E1E;
            text-decoration: none;
        }
        .social-links a:hover {
            color: #555;
        }
        footer {
            text-align: center;
            background-color: #333;
            color: #fff;
            padding: 20px 0;
            margin-top: 40px;
        }
    </style>
</head>
<body>

<header>
    <h1>Gestora de Negócios - NOS Empresas</h1>
</header>

<nav>
    <a href="#servicos">Serviços</a>
    <a href="#faq">Perguntas Frequentes</a>
    <a href="#contacto">Contacto</a>
    <a href="#redes-sociais">Redes Sociais</a>
</nav>

<div class="container">

    <!-- Seção de Serviços -->
    <div id="servicos" class="section">
        <h2>Serviços</h2>
        <ul class="service-list">
            <li>Consultoria empresarial e soluções de telecomunicações</li>
            <li>Planeamento estratégico para otimização de processos</li>
            <li>Gestão de projetos tecnológicos e implementação de infraestruturas</li>
            <li>Apoio na transformação digital para empresas</li>
        </ul>
    </div>

    <!-- Seção de Perguntas Frequentes -->
    <div id="faq" class="section">
        <h2>Perguntas Frequentes</h2>
        <ul class="faq-list">
            <li><strong>Como posso entrar em contacto?</strong><br> Pode preencher o formulário de contacto abaixo ou enviar um email diretamente.</li>
            <li><strong>Quais os serviços mais procurados?</strong><br> Consultoria empresarial, otimização de processos e transformação digital.</li>
            <li><strong>Como faço para contratar um serviço?</strong><br> Basta preencher o formulário de contacto ou enviar um pedido via redes sociais.</li>
        </ul>
    </div>

    <!-- Seção de Contacto -->
    <div id="contacto" class="section">
        <h2>Contacto</h2>
        <p>Preencha o formulário abaixo para entrar em contacto ou discutir os serviços oferecidos.</p>
        <form class="contact-form" action="mailto:email@exemplo.com" method="POST" enctype="multipart/form-data">
            <input type="text" name="nome" placeholder="Seu nome" required>
            <input type="email" name="email" placeholder="Seu email" required>
            <textarea name="mensagem" rows="5" placeholder="Sua mensagem" required></textarea>
            <button type="submit">Enviar</button>
        </form>
    </div>

    <!-- Seção de Redes Sociais -->
    <div id="redes-sociais" class="section">
        <h2>Redes Sociais</h2>
        <div class="social-links">
            <a href="https://www.linkedin.com/in/seuperfil" target="_blank">LinkedIn</a>
            <a href="https://www.twitter.com/seuperfil" target="_blank">Twitter</a>
            <a href="https://www.instagram.com/seuperfil" target="_blank">Instagram</a>
        </div>
    </div>

</div>

<footer>
    <p>&copy; 2024 Gestora de Negócios - NOS Empresas. Todos os direitos reservados.</p>
</footer>

</body>
</html>
