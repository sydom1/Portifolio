# Portifolio
https://www.youtube.com/watch?v=TsMuT8OjAQs - link do video
<!DOCTYPE html>
<html lang="en">

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
            <ul class="cabeçalho-link">
                <li><a href="#">Inicio</a></li>
                <li><a href="#">Sobre mim</a></li>
                <li><a href="#">Serviços</a></li>
                <li><a href="#">Habilidades</a></li>
                <li><a href="#">Contato</a></li>
            </ul>
            <a href="#" class="btn">Subscribe</a>
        </nav>
        <div class="Main">
            <h4>Olá, meu nome é</h4>
            <h1>Tahmid <span>Ahmed</span></h1>
            <h3>Eu sou um desenvolvedor web</h3>
            <div class="conteiner-btn">
                <form>
                    <input type="emai" nome="email" id="mail" placeholder="Envie o seu Email">
                    <input type="submit" nome="submit" value="Começar">
                </form>
            </div>
            <!--conteiner-btn-->
        </div>
        <!--Main-->
    </div>
    <!--Background-->
</body>

</html>

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
