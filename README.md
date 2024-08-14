<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exercicio 15</title>
        <style>
            body{
                margin: 0;
                background-image: url(background.avif);
                background-size: cover;
                font-family: Tahoma;
                color: white;
            }

            img {
                height: 50px;
                margin: 5px;
            }

            header {
                display: inline-flex;
                background-color: white;
                width: 100%;
                color: black;
                font-size: 22px;
                
                
            }

            main {
                display: inline-flex;
                margin-top: 0px;
                width: 100%;
                padding: 5px;
            }

           #linguagens {
            
            text-align: center;
            height: 500px;
            padding: 10px;
            width: 200px;
            font-size: 20px;


            background-color: rgba(113, 113, 212, 0.5);
            
           }

           .solucao{
            width: 100%;
            text-align: center;
            
           }

           #titulo {
                font-size: 30px;
                margin-bottom: 100px;
           }


           #rotape {
            width: 100%;
            position: fixed;
            bottom: 0;
            padding: 30px;
            text-align: center;

            background-color: black;
            background-size: cover;
            

           }

        </style>
</head>
<body>
    <header>
        <img src="logotipo.png" alt="logo">
        <p>Window Web Wizard</p>
    </header>

        <main>
            <div id="linguagens">
              <tr>
                <td>Java</td>
                <td>PHP</td>
                <td>JavaScript</td>
                <td>Python</td>
                <td>Html / Css</td>
              </tr>  
                  
            </div>
              
                <table class="solucao">
                    <tr><td id="titulo">Mostraremos a Solução</td></tr>
                    <tr><td>Pesquise seu problema</td></tr>
                    <tr><td>Mostraremos a solução</td></tr>
                    <tr><td>Teste</td></tr>
                    <tr><td>Caso não resolva, entre em contato</td></tr>
                </table>
        </main>


        <div id="rotape">
            <footer>
                
                <img src="logotipo.png" alt="logo">

                    <table>
                        <tr><a href="#">Espaços</a></tr>
                        <tr><a href="#">Atualizar</a></tr>
                        <tr><a href="#">Sem anúncios</a></tr>
                        <tr><a href="#">Boletim informativo/a></tr>
                        <tr><a href="#">Obtenha Certificação</a></tr>
                    </table>

                <h2>Contate-nos</h2>
                <table id="informacoes">
                    <tr><a href="#">Instagram</a></tr>
                    <tr><a href="#">Youtube</a></tr>
                    <tr><a href="#">GitHub</a></tr>
                    <tr><a href="#">Twitter</a></tr>
                </table>
                <p>2024 Meu Website. Todos os direitos reservados</p>
            </footer>
        </div>
</body>
</html>
