<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Josefin+Sans:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;1,100;1,200;1,300;1,400;1,500;1,600;1,700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" integrity="sha512-iBBXm8fW90+nuLcSKlbmrPcLa0OT92xO1BIsZ+ywDWZCvqsWgccV3gFoRBv0z+8dLJgyAHIhR35VZc2oM/gI1w==" crossorigin="anonymous" referrerpolicy="no-referrer"
    />
    <title>Portfolio web</title>
</head>

<body>
    <div class="background">

        <nav>

            <h2>Portfo<span>lio</span></h2>
            <!--A palavra foi separada para facilitar na estilização-->
            <ul class="cabeçalho-link" id="cabeçalho-link">
                <li><a href="#cabeçalho-link">Inicio</a></li>
                <li><a href="#Main-sobre">Sobre mim</a></li>
                <li><a href="#me-contate">Serviços</a></li>
                <li><a href="#caixa">Habilidades</a></li>
                <li><a href="#Redes-sociais">Contato</a></li>
            </ul>
            <a href="#" class="btn">Subscribe</a>
        </nav>
        <div class="Main">
            <h4>Olá, meu nome é</h4>
            <h1>Anderson <span>Araújo</span></h1>
            <h3>Eu sou um futuro desenvolvedor Html, CSS e <br>Dotnet</h3>
            <div class="conteiner-btn">
                <form>
                    <input type="emai" nome="email" id="mail" placeholder="Envie o seu Email">
                    <input type="submit" nome="submit" value="Começar">
                </form>
            </div>
            <!--conteiner-btn-parte do email e botão-->
        </div>
        <!--Main-->
    </div>
    <!--Background-->

    <section class="background-color-sobre">
        <div class="Main-sobre" id="Main-sobre">
            <img class="foto2" src="img/IMG_20221225_003234-removebg-preview.png" alt="sobre">
            <div class="texto-sobre">
                <h2>Sobre-Mim</h2>
                <h5>Desenvolvedor <span>& Designer</span></h5>
                <p>Eu sou um Desenvolvedor web front-end. Eu posso fornecer codigos limpos e imagem de desing perfeito. E também fazer o website mais & mais interativo e com animação web. E posso Deixar seu site responsivo, e que ele acesse todos os usuarios,
                    independente dos sues aparelhos dispositivos</p>
                <button class="button">Vamos conversar</button>

            </div>
            <!--texto- sobre-->
        </div>
        <!--Main-sobre-->
    </section>
    <!--parte do sobre mim-->

    <div class="conteiner-serviços">
        <div class="Title">
            <h2>Nossos Serviços</h2>
        </div>
        <!--titulo-->
        <div class="caixa" id="caixa">
            <div class="card">
                <i class="fa fa-bars"></i>
                <h5>Desenvolvedor Web</h5>
                <p>Muitos sites devem ser construidos com dois principais objetivos: Primeiramente, ele precisa funcionar em todos os dispositivos, Segundo, Ele precisa ser o mais rapido possivel.</p>
                <button class="btn">Ler mais</button>
            </div>
            <!--cards1-->

            <div class="card">
                <i class="fa fa-user"></i>
                <h5>Desenvolvedor Web</h5>
                <p>Muitos sites devem ser construidos com dois principais objetivos: Primeiramente, ele precisa funcionar em todos os dispositivos, Segundo, Ele precisa ser o mais rapido possivel.</p>
                <button class="btn">Ler mais</button>
            </div>
            <!--cards2-->

            <div class="card">
                <i class="fa fa-bell"></i>
                <h5>Desenvolvedor Web</h5>
                <p>Muitos sites devem ser construidos com dois principais objetivos: Primeiramente, ele precisa funcionar em todos os dispositivos, Segundo, Ele precisa ser o mais rapido possivel.</p>
                <button class="btn">Ler mais</button>
            </div>
            <!--cards3-->

        </div>
        <!--caixas do conteiners-->

        <!--Cursos-->
    </div>
    <!--parte 3, serviços-->
    <div class="me-contate" id="me-contate">
        <p>Contate minha equipe para a gente criar um bonito site para você</p>
        <button class="btn">Enviar mensagem</button>
    </div>
    <!--Me contate-->
    <!-- <div class="cursos">

        <img src="img/C__16H.png" alt="Curso C#">

    </div>
    -->
    <footer>
        <h6>Anderson Araújo</h6>
        <p>Para mais HTML e CSS, tutorias - por favor clique no link <br>abaixo para se inscrever no meu canal</p>
        <div class="Redes-sociais" id="Redes-sociais">
            <a href="https://www.facebook.com/anderson.doacordeon" target="_blank"><i class="fab fa-facebook-f"></i></a>
            <a href="https://www.instagram.com/andersonteclasoficial/" target="_blank"><i class="fab fa-instagram"></i></a>
            <a href="https://www.linkedin.com/in/anderson-ara%C3%BAjo-b00538220/" target="_blank"><i class="fab fa-linkedin"></i></a>
            <a href="https://github.com/sydom1" target="_blank"><i class="fab fa-github"></i></a>
            <a href="https://wa.me/5579988171924" target="_blank"><i class="fab fa-whatsapp"></i></a>

        </div>
        <!--Utima tag rede sociais-->

        <div class="End">
            <p>CopyRight © By Anderson Araújo</p>
        </div>

    </footer>

</body>

CSS

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'josefin Sans', sans-serif;
}

.background {
    background-image: url(background.jpg);
    background-size: cover;
    /* a imagem ocupa todo o espaço*/
    background-position: center;
    height: 100vh;
    width: 100%;
}

nav {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 45px;
    padding-left: 8%;
    padding-right: 8%;
}

nav h2 {
    color: #fff;
    font-size: 35px;
    cursor: pointer;
    letter-spacing: 2px;
    /*serve para dar espaçamento entre as letras*/
}

span {
    color: #f9004d;
}

nav ul li {
    display: inline-block;
    /*ficar na mesma linha*/
    padding: 10px 25px;
    list-style-type: none;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
    text-transform: capitalize;
}

nav ul li a:hover {
    /*para mudar a cor quando passar o mouse*/
    color: #f9004d;
    transform: scale(1.2);
}

.btn {
    background-color: #f9004d;
    color: #fff;
    text-decoration: none;
    font-weight: bold;
    padding: 10px 25px;
    border-radius: 30px;
    transition: transform .4s;
    /*so faz efeito se tiver o houver*/
}

.btn:hover {
    transform: scale(1.2);
}

.Main {
    position: absolute;
    top: 50%;
    left: 8%;
    transform: translateY(-50);
}

h4 {
    color: #fcfcfc;
    letter-spacing: 2px;
    font-size: 20px;
}

h1 {
    color: #fff;
    margin: 20px 0px 20px;
    font-size: 75px;
}

h3 {
    color: #fff;
    font-size: 25px;
    margin-bottom: 50px;
}

.conteiner-btn form {
    width: 380px;
    max-width: 100%;
    position: relative;
}

.conteiner-btn form input:first-child {
    /*primeiro inputo first-child estiliza apenas a primira input*/
    display: inline-block;
    width: 100%;
    padding: 14px 130px 14px 15px;
    border-radius: 30px;
    outline: none;
}

.conteiner-btn form input:last-child {
    position: absolute;
    display: inline-block;
    outline: none;
    padding: 10px 30px;
    border: none;
    border-radius: 30px;
    background-color: #f9004d;
    color: #fff;
    box-shadow: 0px 0px 15px #858585;
    right: 6px;
    top: 6px;
}
