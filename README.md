<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NONÔ_BRAZUKAS</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }
        header {
            background-color: #007BFF;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: space-around;
            background-color: #0056b3;
            padding: 10px;
        }
        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        main {
            padding: 20px;
        }
        .product {
            border: 1px solid #ccc;
            border-radius: 10px;
            padding: 10px;
            background-color: white;
            margin-bottom: 20px;
        }
        .product img {
            max-width: 100%;
            border-radius: 10px;
        }
        .product h2 {
            color: #007BFF;
        }
        footer {
            background-color: #0056b3;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>NONÔ_BRAZUKAS</h1>
    </header>
    <nav>
        <a href="#products">Produtos</a>
        <a href="#reviews">Avaliações</a>
        <a href="#blog">Blog</a>
        <a href="#contact">Contato</a>
    </nav>
    <main>
        <section id="products">
            <h2>Produtos</h2>
            <div class="product">
                <img src="produto1.jpg" alt="Produto 1">
                <h2>Produto 1</h2>
                <p>Descrição detalhada do produto 1.</p>
                <button>Adicionar ao carrinho</button>
            </div>
            <div class="product">
                <img src="produto2.jpg" alt="Produto 2">
                <h2>Produto 2</h2>
                <p>Descrição detalhada do produto 2.</p>
                <button>Adicionar ao carrinho</button>
            </div>
        </section>
        <section id="reviews">
            <h2>Avaliações</h2>
            <p>Aqui estarão as avaliações dos clientes.</p>
        </section>
        <section id="blog">
            <h2>Blog</h2>
            <p>Aqui estarão as notícias e novidades.</p>
        </section>
        <section id="contact">
            <h2>Contato</h2>
            <p>Aqui estarão as informações de contato.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Loja de Eletrônicos. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
