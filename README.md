<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Site Offline</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #004aad;
            color: white;
            padding: 20px;
            text-align: center;
        }

        nav {
            background-color: #ddd;
            padding: 10px;
            text-align: center;
        }

        nav a {
            margin: 0 15px;
            color: #333;
            text-decoration: none;
            font-weight: bold;
        }

        main {
            padding: 20px;
        }

        section {
            margin-bottom: 40px;
        }

        .galeria img {
            width: 200px;
            margin: 10px;
            border-radius: 8px;
        }

        form {
            max-width: 400px;
            margin: auto;
        }

        input, textarea {
            width: 100%;
            padding: 10px;
            margin: 8px 0;
            border-radius: 4px;
            border: 1px solid #ccc;
        }

        button {
            background-color: #004aad;
            color: white;
            padding: 10px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }

        .redes p {
            text-align: center;
        }

        footer {
            background-color: #004aad;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 40px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bem-vindo ao Meu Site Offline</h1>
    </header>

    <nav>
        <a href="#inicio">Início</a>
        <a href="#sobre">Sobre</a>
        <a href="#galeria">Galeria</a>
        <a href="#contato">Contato</a>
    </nav>

    <main>
        <section id="inicio">
            <h2>Olá!</h2>
            <p>Este é um site simples que funciona completamente offline.</p>
        </section>

        <section id="sobre">
            <h2>Sobre</h2>
            <p>Este site não depende de internet para carregar imagens ou recursos externos.</p>
        </section>

        <section id="galeria" class="galeria">
            <h2>Galeria de Imagens</h2>
            <img src="https://i.postimg.cc/hPGbTXVx/IMG-20250322-055133214-BURST006.jpg"width="200"height="300" alt="Imagem 1">
            <img src="https://i.postimg.cc/vZvtbm5P/Screenshot-20250510-143222.png" alt="Imagem 2">
            <img src="https://i.postimg.cc/76533Mdc/Screenshot-20250505-131015.png" alt="Imagem 3">
        </section>

        <section id="contato">
            <h2>Fale Conosco</h2>
            <form>
                <input type="text" placeholder="Seu nome" required>
                <input type="email" placeholder="Seu email" required>
                <textarea placeholder="Sua mensagem" rows="5" required></textarea>
                <button type="submit">Enviar</button>
            </form>
        </section>

        <section class="redes">
            <h2>Redes Sociais</h2>
            <p>(Links desativados offline — substitua com seus perfis reais)</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Meu Site. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
