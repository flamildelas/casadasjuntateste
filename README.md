<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Juntas de Vedações Mecânicas</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
            background-color: #f4f4f4;
        }
        header {
            background-color: #003366;
            color: white;
            padding: 1rem 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
            display: flex;
            justify-content: center;
        }
        nav ul li {
            margin: 0 15px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        section {
            padding: 2rem;
            max-width: 1200px;
            margin: 0 auto;
        }
        .products {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        .product {
            background-color: white;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            padding: 1rem;
            width: calc(33% - 20px);
            box-sizing: border-box;
        }
        .product img {
            max-width: 100%;
            height: auto;
        }
        footer {
            background-color: #003366;
            color: white;
            text-align: center;
            padding: 1rem 0;
            position: absolute;
            bottom: 0;
            width: 100%;
        }
        @media (max-width: 768px) {
            .product {
                width: calc(50% - 20px);
            }
        }
        @media (max-width: 480px) {
            .product {
                width: 100%;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Juntas de Vedações Mecânicas</h1>
        <nav>
            <ul>
                <li><a href="#about">Sobre Nós</a></li>
                <li><a href="#products">Produtos</a></li>
                <li><a href="#contact">Contato</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>Sobre Nós</h2>
        <p>Bem-vindo à nossa empresa especializada em juntas de vedações mecânicas. Oferecemos uma ampla gama de produtos de alta qualidade para atender às suas necessidades de vedação e garantir a eficiência de suas operações.</p>
    </section>

    <section id="products">
        <h2>Produtos</h2>
        <div class="products">
            <div class="product">
                <img src="https://via.placeholder.com/300x200" alt="Produto 1">
                <h3>Junta de Vedação A</h3>
                <p>Descrição detalhada do produto A.</p>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/300x200" alt="Produto 2">
                <h3>Junta de Vedação B</h3>
                <p>Descrição detalhada do produto B.</p>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/300x200" alt="Produto 3">
                <h3>Junta de Vedação C</h3>
                <p>Descrição detalhada do produto C.</p>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Contato</h2>
        <p>Para mais informações sobre nossos produtos e serviços, entre em contato conosco:</p>
        <address>
            <p>Email: <a href="casadasjuntasmanaus@gmail.com">contato@exemplo.com</a></p>
            <p>Telefone: +55 (11) 1234-5678</p>
            <p>Endereço: Av. Tefé, 37, Manaus, AM, Brasil</p>
        </address>
    </section>

    <footer>
        <p>&copy; 2024 Juntas de Vedações Mecânicas. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
