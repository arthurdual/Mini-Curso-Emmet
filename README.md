# Mini-Curso-Emmet
### Este mini cusco de Emmet foi focada em Aumento de produtividade utilizando emmet para construção de codigos mais rapida.

# O que é Emmet?

O Emmet é uma maneira de você aumentar sua produtividade com HTML e CSS. Ele é nada mais, nada menos que um plugin que para seu editor de texto. Ele corta em muito o tempo necessário para se declarar tags
Retirado de: https://medium.com/trainingcenter/aumentando-produtividade-com-emmet-fbf33ff1c17c

Com Emmet a criação de uma estrutura html fica muito mais rapida, veja este exemplo:

ao digitar html:5 e apertar TAB o emmet cria a estrutura html abaixo
/*html:5 + TAB*/

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
</head>
<body>
    <!--Com a estrutura criada agora faremos a estrutura de um menu:
    Com este codigo Emmet abaixo iremos criar a estrutura do menu
      header.header>img.header-logo+nav.wrap-menu>ul.menu>li.menu-item*7 = TAB-->
     <header class="header">
        <img src="" alt="" class="header-logo">
        <nav class="wrap-menu">
            <ul class="menu">
                <li class="menu-item"></li>
                <li class="menu-item"></li>
                <li class="menu-item"></li>
                <li class="menu-item"></li>
                <li class="menu-item"></li>
                <li class="menu-item"></li>
                <li class="menu-item"></li>
            </ul>
        </nav>
    </header>
</body>
</html>
```

dicas:
```
Para criar elementos irmaos coloque +
Para criar elementos filhos coloque >
. para classe
# para id
*7 gera o item 7 vezes
```
