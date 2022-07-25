# Poema Dev
<p aling="center">
    <img  width="650" height="350" src="./imagens/logo-poema.png">
</p>

Poema-Dev é o ponto de partida para todas as pessoas que querem ter o primeiro contato com tecnologias, focadas no 
client-side(front-end) ou seja o lado do cliente. Dessa forma, o projeto consiste em escrever um simples poema com uma imagem de fundo na tela.

## HTML e CSS

index.html:

```html
    <!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Poema Dev</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Pacifico&display=swap');

        html, body {
            margin: 0;
            padding: 0;
            min-height: 100vh;
            height: 100vh;
        }

        body {
            background-color: black;
            background-image: url('./imagens/imagem-fundo.png');
            background-repeat: repeat-y;
            background-attachment: scroll;
            background-position: center;
            background-size: cover;
        }

        main {
            font-family: 'Pacifico', cursive, Arial, serife;
            font-size: 1.5em;
            color: black;
            background-position: center;
            width: 400px;
            margin: auto;
            padding: 10px;
            text-align: center;
            border-radius: 10px;
        }

        #autor {
            font-family: Arial, Helvetica, sans-serif;
            font-size: 1em;
            text-align: left;
        }

        a:link {
            color: black;
            text-decoration: none;
        }

        a:visited {
            text-decoration: underline;
        }

        a:hover {
            text-decoration: underline;
            background-color: aquamarine; 
        }

    </style>
</head>
<body>
    <main>
        <h1>Poema dev</h1>
        <p>Todo dia me encanta.</p>
        <p>A tal da programação.</p>
        <p>Quando penso que a conquisto.</p>
        <p>Ela me leva ao chão.</p>
        <p>Com um erro no console.</p>
        <p>Ela pega pra valer.</p>
        <p>Me pergunta todo dia.</p>
        <p>Se ela eu vou querer.</p>
        <p id="autor"><a href="https://github.com/PedroPapoti" target="_blank">AUTOR: Pedro Papoti Calazans</a></p>
    </main>
</body>
</html>
```
> Agora é com você !! Escreva o seu próprio poema, mude a imagem de fundo e o link para outro repositório !! 

Links de suporte: 

[Curso de HTML E CSS](https://www.youtube.com/watch?v=Ejkb_YpuHWs&list=PLHz_AreHm4dkZ9-atkcmcBaMZdmLHft8n)

[Como colocar uma imagem no fundo de um site](https://www.youtube.com/watch?v=9hV5oXi80-A&list=PLHz_AreHm4dmcAviDwiGgHbeEJToxbOpZ&index=13) 

[Click aqui para ver o poema!!](https://pedropapoti.github.io/Poema-Dev/)

Caso tenha alguma duvida entre em contato comigo pelo email pedropapoti@gmail.com .





