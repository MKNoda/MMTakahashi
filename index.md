<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width">
        <title>MMT Milton M. Takahashi</title>
        <link rel="shortcut icon" href="Images/LOGOMMT.png" />
        <!-- Bootstrap CSS -->
        <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
        <!--Estítlo da página-->
        <link href="style.css" rel="stylesheet" type="text/css" />
        <!--Fontes-->
        <link href="https://fonts.googleapis.com/css?family=Dancing+Script|Oswald&display=swap" rel="stylesheet">
    </head>
    <body>
        <!-- Optional JavaScript -->
        <!-- jQuery first, then Popper.js, then Bootstrap JS -->
        <script src="https://code.jquery.com/jquery-3.4.1.slim.min.js" integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" crossorigin="anonymous"></script>
        <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
        <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
        <script src="script.js"></script>

        <!--Início Barra de navegação-->
        <nav class="navbar navbar-expand-md navbar-dark bg-dark sticky-top main-collor">
            <button class="navbar-toggler" data-toggle="collapse" data-target="#collapse_target">
            <span class="navbar-toggler-icon"></span>
            </button>

            <div class="collapse navbar-collapse" id="collapse_target">
            <a href="index.html" class="navbar-brand"><img src="Images/MMTLOGO.png" style="width:123.75px;height:92.75px;" alt="logo" ></a>
            <ul class="navbar-nav">
            <li class="nav-item nav-item-font"><a href="index.html" class= "nav-link">PÁGINA INICIAL</a></li>
            <!--<li class="nav-item nav-item-font"><a href="NossaEmpresa.html" class= "nav-link">NOSSA EMPRESA</a></li>
            <li class="nav-item nav-item-font"><a href="Contato.html" class= "nav-link">CONTATO</a></li> -->
            </ul>
            </div>
        </nav>
        <!--Fim da Barra de Navegação-->
        <!--Página principal-->
        <div class="wrapper-mainpage">
            <div class="content-container-mainpage">
                <div><h1 class="mainpage-title">EMPREGOS NO JAPÃO</h1></div>
                <p class="mainpage-p">
                    Confiança e compreensão mútua<br>(Trust and mutual understanding)
                </p>
            <div class="cta-button">
                <a href="#sobrenos" class="link-button"><button type="button" class="btn btn-danger"><span class="texto-botao">ENTRE EM CONTATO</span></button></a>
            </div>
            </div>
        </div>
        <!-- Fim da Página principal-->
        <!--Sobre nós-->
        <div class="wrapper-seccond-page" id="sobrenos">
            <h2 class="page-title">SOBRE NÓS</h2>
            <p class="description-second-page">
                Fundada em 2019, a empresa MMT é representante das principais empreiteiras do Japão. Oferece atendimento personalizado, em vários segmentos e em todas as regiões do Japão. 
            </p>
            <div class="container-second-page">
                <div class="flex-box-container">
                    <div class="item-box">
                    <div class="item-box-title-container"><h3 class="title-item-box title-font">MISSÃO</h3></div>
                    <!--<img class="image-item-box" src="Images/flor.png" alt="flor">-->
                    <p>
                        Contribuir para a sociedade do Vale do Paraíba servindo de ponte entre Brasil e Japão
                    </p>
                    </div>
                    <div class="item-box">
                    <div class="item-box-title-container"><h3 class="title-item-box title-font">VISÃO</h3></div>
                    <!--<img class="image-item-box" src="Images/flor.png" alt="flor">-->
                    <p class="text-color-tracker">
                        Utilização de know-how adquirido no Japão para ser referência no atendimento aos clientes.
                    </p>
                    </div>
                    <div class="item-box">
                    <div class="item-box-title-container"><h3 class="title-item-box title-font">VALORES</h3></div>
                    <!--<img class="image-item-box" src="Images/flor.png" alt="flor">-->
                    <p>
                        Transparência no atendimento e confiança dos clientes
                    </p>
                    </div>
                </div>
            </div>
            <div class="container-second-page2">
                <h2 class="page-title">NOSSOS SERVIÇOS</h2>
                <div class="flex-box-container">
                    <div class="item-box">
                    <h2 class="title-item-box title-font">Vagas</h2>
                    <p>Setores de alimentação, eletrônicos e autopeças</p>
                    </div>
                    <div class="item-box">
                    <h2 class="title-font title-item-box">Direcionamento</h2>
                    <p>Todas as regiões do Japão, dependendo das suas características e necessidades</p>
                    </div>
                </div> 
            </div>         
            <!--<img class="main-image" src="Images/bonsai.png" alt="bonsai">-->
        </div> 
        <!--Fim do Sobre nós-->
        <!--Contato-->
        <div class="container-contact">
            <h2 class="main-collor contact-title">ENTRE EM CONTATO</h2>
            <div class="contato-box">
                <form action="MAILTO:kenji.noda@hotmail.com" method="POST" enctype="text/plain">
                    <div class="column-1">
                        <div class="form-item">
                        <label for="name" class="form-text">Nome</label>
                        <input type="text" class="form-control" name="name" placeholder="Nome" id="name" required>   
                        </div>
                        <div class="form-item">
                        <label for="email" class="form-text">E-mail</label>
                        <input type="email" class="form-control" name="email" id="email" placeholder="...@hotmail.com" required>   
                        </div>
                        <div class="form-item">
                        <label for="tel" class="form-text">Telefone</label>
                        <input type="tel" class="form-control" name="tel" id="tel" placeholder="(xx)xxxxx-xxxx" required>  
                        </div>
                    </div>
                    <div class="column-2">
                        <div class="form-itemtext mensagem-box">
                        <label for="Mensagem" class="form-text">Mensagem</label>
                        <textarea type="text" name="bio" id="texto" class="form-control text-box" placeholder="Digite seu texto aqui"></textarea>
                        </div>
                    </div>
                    <div>
                    <button type="submit" class="btn btn-outline-secondary button-padding button-text">Enviar</button>                        
                    </div>
                </form>
            </div>
        </div>
        <!--Fim do Contato-->
        <!--Início do footer-->
        <div class="footer-wrapper">
            <div class="footer-container">
                <p class="footer-text">E-mail:kenchiku@hotmail.com</p>
                <p class="footer-text">Telefone:(12)98279-7099</p>
            </div>
        </div>
        <!--Fim do footer-->           
    </body>
</html>
