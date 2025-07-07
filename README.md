<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Portfólio Pessoal</title>
    <link rel="stylesheet" href="pessoalportifolio.css">
</head>
<body>
    <!-- Menu  -->
    <nav>
        <ul>
            <li><a href="#sobre">Sobre Mim</a></li>
            <li><a href="#formacao">Formação</a></li>
            <li><a href="#portfolio">Portfólio</a></li>
            <li><a href="#contato">Contato</a></li>
        </ul>
    </nav>

    <!-- Sobre Mim -->
    <section id="sobre">
        <h1>Sobre Mim</h1>
        <p>Me chamo Alan, 8 anos trabalhando na área de logística em uma empresa do setor de defensivo agricola. no momento estou procurando conhecimento na área de desenvolvimento e análise de sistemas na Instituição Uninter.
        Meus hobbies é ler livros, uma caminhada e o melhor para esquecer dos problemas do mundo é meu videogame.</p>
    
    </section>

    <section id="formacao">
        <h1>Formação Acadêmica</h1>
        <h3> desenvolvimento e análise de sistemas - cursando</h3>
        <p>Uniter - Conclusão para 2028</p>
        <p>Prime  - Power BI, curso on line de 40 hrs conclusao prev. 08/2025
        <p>Inovatech - Gestão sistema ERP e WMS - finalizado em 07/2022.</p>
        
    <h3>Idiomas</h3>
        <ul>
            <li>Inglês: intermediário</li>
            <li>Espanhol: básico</li>
        </ul>
    </section>

    <section id="portfolio">
        <h1>Meu Portfólio</h1>
        
        <div class="projeto">
            <h3>Projeto 1</h3>
            <p>Em construção.<p> Link da twich está abaixo, algums vezes realizo algumas trasmissões de jogatinas com amigos.</p></p>
            <a href="#" target="_blank"> <a href="https://www.twitch.tv/alanmartins2285">
                <img src="site/img/twich.png"></a>
        </div>
    </section>

    <!-- Contato -->
    <section id="contato">
        <h1>Entre em Contato</h1>
        <form>
            <label for="nome">Nome:</label>
            <input type="text" id="nome" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" required>
            
            <label for="mensagem">Mensagem:</label>
            <textarea id="mensagem" rows="5" required></textarea>
            
            <button type="submit">Enviar Mensagem</button>
        </form>
    </section>
</body>
</html>
