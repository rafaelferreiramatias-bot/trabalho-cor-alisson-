



<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Site com Cartões</title>

    <style>
        * {
            box-sizing: border-box;
        }

        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #0b2341;
            color: white;
        }

        header {
            padding: 30px;
            text-align: center;
            background-color: #081b33;
        }

        nav {
            padding: 15px;
            text-align: center;
            background-color: #102f55;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
        }

        main {
            padding: 40px;
        }

        .cartoes {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 20px;
            max-width: 1200px;
            margin: 0 auto;
        }

        .cartao {
            background-color: white;
            color: black;
            padding: 20px;
            border-radius: 8px;
            min-height: 160px;
        }

        footer {
            margin-top: 40px;
            padding: 20px;
            text-align: center;
            background-color: #081b33;
        }

        /* Quando a tela ficar menor, organiza em 2 colunas */
        @media (max-width: 850px) {
            .cartoes {
                grid-template-columns: repeat(2, 1fr);
            }
        }
        #cartao1 {
          background:#00A8FC;
          color:#000000;
        }

        #cartao2 {
          background:#322724;
          color:#FE74EE;
        }

        #cartao3 {
          background:#0DFF00;
          color:#0019FF;  
        }

        #cartao4 {
          background:#00FBE6;
          color:#FF0000;  
        }

        #cartao5 {
          background:#FAFA00;
          color:#4702F6;  
        }

        #cartao6 {
          background:#8F00D1;
          color:#00FFFF;  
        }


        #cartao7 {
          background:#FF8C00;
          color:#8F00D1;  
        }

        #cartao8 {
          background:#00FFEA;
          color:#8F0404;  
        }


        






    </style>
</head>

<body>

    <header>
        <h1>Meu Site</h1>
        <p>Exemplo de página semântica com cartões</p>
    </header>

    <nav>
        <a href="#">Início</a>
        <a href="#">Sobre</a>
        <a href="#">Contato</a>
    </nav>

    <main>
        <div class="cartoes">

            <div class="cartao" id="cartao1">

                <h2> William Shakespeare</h2>
                <p>
                    "Ser ou não ser, eis a questão.
                </p>
            </div>

            <div class="cartao" id="cartao2">
                <h2>John Lennon</h2>
                <p>
                    "A vida é o que acontece enquanto você está ocupado fazendo outros planos."
                </p>
            </div>

            <div class="cartao" id="cartao3">
                <h2>Oscar Wilde</h2>
                <p>
                    "Viver é a coisa mais rara do mundo. A maioria das pessoas apenas existe."
                </p>
            </div>

            <div class="cartao" id="cartao4">
                <h2> Albert Einstein </h2>
                <p>
                    "No meio da dificuldade encontra-se a oportunidade.
                </p>
            </div>

            <div class="cartao" id="cartao5">
                <h2> Confúcio</h2>
                <p>
                    "Não faça aos outros o que não quer que façam a você."
                </p>
            </div>

            <div class="cartao" id="cartao6">
                <h2>Albert Einstein </h2>
                <p>
                   "Duas coisas são infinitas: o universo e a estupidez humana; e eu não tenho certeza sobre o universo."
                </p>
            </div>

            <div class="cartao" id="cartao7">
                <h2> Isaac Newton</h2>
                <p>
                    "Se eu vi mais longe, foi por estar sobre os ombros de gigantes.
                </p>
            </div>

            <div class="cartao" id="cartao8">
                <h2> Élie Wiesel</h2>
                <p>
                    "O oposto do amor não é o ódio, é a indiferença."
                </p>
            </div>

        </div>
    </main>

    <footer>
        <p>© 2026 - Meu Site</p>
    </footer>

</body>
</html>






