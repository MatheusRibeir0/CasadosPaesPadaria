<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        
ul.menu-bar {
            list-style-type: none;
            margin: 0;
            padding: 0;
            background-color: #ffffff;
            overflow: hidden;
            display: flex;
            justify-content: center;
            align-items: center;
        }

ul.menu-bar li a {
            display: block;
            color: rgb(0, 0, 0);
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
        }

ul.menu-bar li a:hover {
            background-color: #555;
        }

ul {
            text-align: left;
        }

h2, p {
            text-align: left;
        }

h3 {
            text-align: center;
        }

.emoji {
            font-size: 13px;
        }

.container {
            text-align: center;
            margin-top: 20px;
        }

author{
            display: inline-block;
            text-align: center;
            margin: 10px;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

.profile-image {
            border-radius: 50%;
            width: 150px;
            height: 150px;
            object-fit: cover;
        }

.author-info {
            margin-top: 10px;
            /* Espaçamento entre a imagem e o nome */
        }
    </style>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <title>Projeto HTML 2023 - Padaria Casa dos Pãezinhos</title>
</head>

<body>
    <!-- Barra de menus -->
    <ul class="menu-bar">
        <li><a href="#home">Início</a></li>
        <li><a href="#produtos">Produtos</a></li>
        <li><a href="#orcamento">Orçamento</a></li>
        <li><a href="#contatos">Contatos</a></li>
        <li><a href="#autores">Autores</a></li>
    </ul>

<div class="container my-5">
        <h1 class="text-center">Projeto HTML 2023 - Padaria Casa dos Pãezinhos</h1>

 <div class="text-center">
            <img src="https://github.com/BeatrizBonetto/projeto_html_2023/assets/142846833/488b30b8-a932-48eb-aca4-28f4c3255958"
                alt="Logo minimalista para utilização na capa do projeto" class="img-fluid">
        </div>

<div class="text-center mt-10">
            <span class="badge badge-secondary">SEJA BEM VINDO AO NOSSO SITE,</span><span
                class="badge badge-success">ESTAMOS EM DESENVOLVIMENTO
                <span class="emoji" class="badge badge-success">😀</spa>
                </span>
        </div>

<h3 class="mt-4">Objetivo do projeto</h3>
        <p>
            O objetivo principal deste projeto é criar um site simples, completo e interativo para o usuário que
            deseja realizar cotações de coffee breaks e pedidos para festas e eventos pessoais e corporativos, além
            de consultar preços de produtos pré produzidos.
        </p>

<h3 class="mt-4">Funcionalidades do projeto</h3>
        <ul>
            <li>
                O cliente poderá encontrar os telefones para contato, endereço e horário de funcionamento na aba
                "Informações".
            </li>
            <li>
                O cliente poderá entrar em contato via whatsapp clicando no ícone do whatsapp lincado a aba "<a
                    href="#informacoes">Informações</a>".
            </li>
            <li>
                O cliente poderá consultar o cardápio com os preços dos produtos na aba "<a
                    href="#produtos">Produtos</a>".
            </li>
            <li>
                O cliente poderá realizar a compra via site, colocando os produtos em seu carrinho, preenchendo seus
                dados e realizando o pedido.
            </li>
            <li>
                O cliente poderá solicitar orçamentos diferenciados preenchendo um cadastro na aba "<a
                    href="#orcamento">Orçamentos</a>".
            </li>
        </ul>

 <h2 id="informacoes">Informações</h2>
        <p>Aqui estão algumas informações da empresa.</p>

<h2 id="produtos">Produtos</h2>
        <p>Confira os nossos produtos e preços.</p>

<h2 id="orcamento">Orçamento</h2>
        <p>📧 Solicite seu orçamento via email: <a href="mailto:digiteoucrieumemail@gmail.com">Clique
                aqui</a></p>
        <p>📱 Solicite seu orçamento via Whatsapp <a href="https://wa.me/55191234567890">Clique aqui</a> para
            mais informações</p>

<h2 id="localizacao">Localização</h2>
        <p>📍 Campinas - SP</p>
    </div>

<div class="container">
        <h3 class="mt-4">Autores</h3>
        <div class="row justify-content-center">
            <div class="author">
                <a href="https://github.com/BeatrizBonetto">
                    <img src="https://avatars.githubusercontent.com/u/142846833?s=400&u=74bf2d3521a969a16d6573336e27d3830c63d048&v=4"
                        alt="Beatriz Faccioli Bonetto" class="profile-image">
                    <div class="author-info">
                        <p>Beatriz Faccioli Bonetto</p>
                        <p>Matricula: 202302381189</p>
                    </div>
                </a>
            </div>
            <div class="author">
                <a href="https://github.com/MatheusRibeiro">
                    <img src="https://github.com/MatheusRibeir0/MatheusRibeir0/blob/main/foto.jpeg?raw=true"
                        alt="Matheus Ribeiro" class="profile-image">
                    <div class="author-info">
                        <p>Matheus Ribeiro</p>
                        <p>Matricula: 202303664206</p>
                    </div>
                </a>
            </div>
            <div class="author">
                <a href="https://github.com/deividmoretto">
                    <img src="https://avatars.githubusercontent.com/u/75542165?s=400&u=1550acedc789159f7b09c6123d0bf0b6c36bf407&v=4"
                        alt="Deivid Moretto" class="profile-image">
                    <div class="author-info">
                        <p>Deivid Moretto</p>
                        <p>Matricula: 202303281579</p>
                    </div>
                </a>
            </div>
        </div>
    </div>
</body>

</html>
