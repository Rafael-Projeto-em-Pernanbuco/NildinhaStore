
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>NildinhaStore</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- Google Translate -->
    <script type="text/javascript">
        function googleTranslateElementInit() {
            new google.translate.TranslateElement({pageLanguage: 'pt', includedLanguages: 'en,es,fr,it,de'}, 'google_translate_element');
        }
    </script>
    <script type="text/javascript" src="//translate.google.com/translate_a/element.js?cb=googleTranslateElementInit"></script>

    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #fff8e1;
            color: #4a1c1c;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #800000; /* Vinho */
            color: gold;
            padding: 20px;
            text-align: center;
        }
        nav {
            background-color: #b22222; /* Tom entre vinho e vermelho */
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: gold;
            margin: 0 15px;
            text-decoration: none;
        }
        section {
            padding: 20px;
        }
        .chat-buttons button {
            margin: 5px;
            padding: 10px;
            background-color: gold;
            border: none;
            cursor: pointer;
            color: #800000;
        }
        footer {
            background-color: #800000;
            color: gold;
            text-align: center;
            padding: 15px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>NildinhaStore</h1>
        <p>Localizado na Rua Vicente Ulisses, Centro, Exu-PE</p>
    </header>

    <div id="google_translate_element" style="text-align:right; margin:10px;"></div>

    <nav>
        <a href="#produtos">Anúncios de Roupas</a>
        <a href="#contato">Contatos</a>
        <a href="#registro">Registrar E-mail</a>
    </nav>

    <section id="produtos">
        <h2>Roupas à Venda</h2>
        <ul>
            <li>Vestido Floral - R$ 120,00</li>
            <li>Camisa Social Masculina - R$ 85,00</li>
            <li>Saia Jeans - R$ 90,00</li>
            <!-- Adicione mais produtos aqui -->
        </ul>
    </section>

    <section id="registro">
        <h2>Registrar seu E-mail</h2>
        <form>
            <input type="email" placeholder="Digite seu e-mail" required>
            <button type="submit">Registrar</button>
        </form>
    </section>

    <section id="mapa">
        <h2>Como Chegar</h2>
        <iframe src="https://www.google.com/maps?q=Rua+Vicente+Ulisses,+Exu-PE&output=embed" width="100%" height="300" style="border:0;" allowfullscreen></iframe>
    </section>

    <section class="chat-buttons">
        <h2>Atendimento</h2>
        <button onclick="window.open('https://wa.me/seunumerowhatsapp', '_blank')">WhatsApp</button>
        <button onclick="window.open('https://instagram.com/seuusuario', '_blank')">Instagram</button>
        <button onclick="window.open('https://facebook.com/seuusuario', '_blank')">Facebook</button>
        <button onclick="window.open('https://twitter.com/seuusuario', '_blank')">Twitter</button>
        <button onclick="window.open('https://www.kwai.com/user/seudominio', '_blank')">Kwai</button>
        <button onclick="alert('Atendimento online em breve')">Atendimento Online</button>
        <button onclick="alert('Pedidos e entregas em breve')">Pedidos e Entregas</button>
    </section>

    <footer>
        &copy; 2025 NildinhaStore - Todos os direitos reservados.
    </footer>
</body>
</html>
