



<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://fonts.googleapis.com/css?family=Montserrat:400,700,900|Roboto+Slab:700|Roboto:400,400i">
    <link rel="stylesheet" href="style.css">
    <title>M de maravilhosa</title>
</head>

<body>

    <nav>
        <div class="navbar">
            <div class="navbar_logotipo">
                <img src="img/logo-white.png" alt="Logotipo M de Maravilhosa">
            </div>
        </div>
    </nav>

    <!-- Cabeçalho -->
<header class="header">
    <div class="container_header">
        <div class="header_titulo">
            <h1>The future is female coders.</h1>
            <a class="header_button">Saiba mais</a>
        </div>
        <div>
            <div>
                <img class="header_maravilhosa_img" src="./img/header_maravilhosa.jpg" alt="" />
            </div>
        </div>    
    </div>
</header>
   

    <!-- Secao Maravilhosa -->

    <section>
        <div>
            <h2>Frida Kahlo</h2>
        </div>
        <div>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Unde vero vitae aperiam, facere, eaque consequatur ex minus eveniet voluptatem natus reiciendis sequi et quibusdam ipsa. Impedit incidunt tempore doloremque porro.</p>
        </div>

        <div>
            <img src="" alt="">
            <div>
                <h2>Sua história</h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Atque eveniet magnam fugiat minus ut modi dolorum explicabo aut unde, tempora quisquam at quos quo ipsam! Dolores aperiam quae dignissimos odio.</p>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Illo facere rem atque molestias ducimus dignissimos ad officia expedita eligendi in? Doloribus dolore asperiores incidunt, vel labore consequatur molestias perspiciatis porro.</p>
            </div>
        </div>
    </section>

   

   <!-- AUTORA -->
   <section>
       <div>
           <h2>Sobre a autora</h2>
           <div>
               <img src="" alt="">
               <div>
                   <h3>Rosana</h3>
                   <p>
                       Lorem, ipsum dolor sit amet consectetur adipisicing elit. Numquam at ullam ratione magnam eveniet quasi qui assumenda unde enim nemo suscipit voluptatem ducimus reprehenderit, explicabo nulla dolorum possimus deleniti repellendus?
                   </p>
               </div>
           </div>
       </div>
   </section>
   


    <!-- Footer -->

   <footer>
       <div>
           <ul>
               <li><a href="#" target="_blank">Home</a></li>
               <li><a href="http://www.reprograma.com.br/" target="_blank">Conheça a {reprograma} </a></li>
           </ul>
           <img src="./img/logo-white.png" alt="" >
           <div>
            <a href="https://www.facebook.com/ReprogramaBr/" target="_blank">
                <img src="./img/icon-facebook.png" alt="Íconde do Facebook">
            </a>
            <a href="https://twitter.com/ReprogramaBr" target="_blank">
                <img src="./img/icon-twitter.png" alt="Ícone do Twitter">
            </a>
            <a href="https://www.instagram.com/reprogramabr/" target="_blank">
                <img src="./img/icon-instagram.png" alt="Ícone do Instagram">
            </a>
            <a href="https://www.linkedin.com/company/reprogramabr/" target="_blank">
                <img src="./img/icon-linkedin.png" alt="Ícone do LinkedIn">
            </a>
           </div>
        
       </div>
   </footer>



</body>

</html>



===========================================================================
CSS



* {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
  font-family: 'Montserrat', Arial, Helvetica, sans-serif;
}

a {
    text-decoration: none;
    color: inherit;
    margin: 2px;
}

/* NAVBAR */

.navbar{
    background-color: #C083B9;
    width: 100%;
    height: 85px;
}

.navbar_logotipo {
    text-align: center;
    padding: 5px;
}

/* -------------------------------------------------------------------------------- */


/* HEADER */

.header {
    background-image: url(./img/backgroud_header_01.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    min-height: 80vh;
    width: 100%;
    height: 500px;
    color: #ffffff;
}

.container_header {
    width: 100%;
    height: 100%;
    display: flex;
    padding: 30px;
    flex-direction: column;
}


.header_maravilhosa_img{
    width: 90%;
    height: 220px;
    margin-left: 20px;
    margin-top: 50px;
}

.header_titulo {
    width: 90%;
    margin: 5px 10px 5px 10px;
    text-align: center;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}






/* --- BOTAO --- */
  
.header_button {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 150px;
    height: 40px;
    background: #7F479B;
    border-radius: 5px;
    color: #ffffff;
    text-decoration: none;
    list-style: none;
    font-size: 18px;
    font-weight: bold;
    letter-spacing: 0.5px;
    margin-top: 40px;
}

.header_button:hover {
    background-color: #2e1842;
    color: #ffffff;
    transition: background-color .5s;
}




/* SECAO Maravilhosa */



/* AUTORA */



/* SECAO Recado */



/* FOOTER */


/* MEDIA QUERY */




-------------------////// DÚVIDAS PARA QUARTA-FEIRA /////////// ---------------------------------------------------------------




-------------------------------------------------------------OUTROS LINKS--------------------------------------------------------------------------------------------
Como Mudar de Master para Main https://youtu.be/MdthEusEoy8?t=199 || outro link sobre Master para Main https://alismed.github.io/blog/2020/07/27/mudar-master-main.html

Método BEM https://medium.com/reprogramabr/organizando-seu-c%C3%B3digo-o-que-%C3%A9-m%C3%A9todo-bem-e-como-utiliz%C3%A1-lo-89f1664af295 

Imagens Responsivas https://developer.mozilla.org/pt-BR/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images

Background no CSS https://www.devmedia.com.br/css-background/38313

Imagens e legendas CSS https://www.w3.org/Style/Examples/007/figures.pt_BR.html

Imagens HTML https://developer.mozilla.org/pt-BR/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML

COMPARADOR DE TEXTO/CÓDIGO https://www.invertexto.com/comparar-textos
https://m-de-maravilhosa-on13.netlify.app/#
