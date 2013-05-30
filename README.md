Aprendendo Markdown
===================
Afinal, o que eu posso fazer com essa sintaxe? :)

Markdown é uma melhor forma de escrever documentos para a web. A sintaxe permite
que você defina estruturas HTML sem a necessidade de escrever HTML diretamente.
Você economizará tempo ao escrever menos e manterá a legibilidade do seu
documento em alta.

Uma descrição completa sobre Markdown está disponível [aqui][md-pt-br] (página oficial
do Markdown, traduzida pelo Google Translate. A versão original em inglês pode ser acessada [aqui][md-en]).

  [md-pt-br]: http://translate.google.com.br/translate?sl=en&tl=pt&js=n&prev=_t&hl=pt-BR&ie=UTF-8&eotf=1&u=http%3A%2F%2Fdaringfireball.net%2Fprojects%2Fmarkdown%2F
  [md-en]: http://daringfireball.net/projects/markdown/


Sobre o autor deste documento
-----------------------------
Me chamo Joel Wallis, sou um desenvolvedor web, especializado em [Drupal][dpl],
que ama comunidades e softwares livres. Sou um defensor do livre acesso ao
conhecimento, um praticante de inteligência coletiva, um eterno aprendiz.
Você pode saber mais sobre meu trabalho visitando
[meu perfil no LinkedIn][lnkd], você pode [me seguir no Twitter][twt],
você pode forkar algum projeto do [meu Github][gth], você pode ler
[minha página no About.me][btm], ou você pode ir aonde você quiser. ;)

  [dpl]: http://drupal.org
  [lkd]: http://br.linkedin.com/in/joelwallis/
  [twt]: http://twitter.com/joelwallis1
  [gth]: http://github.com/joelwallis
  [btm]: http://about.me/joelwallis

Usando o Markdown
-----------------
@todo: escrever uma introdução bem legal aqui.

### Cabeçalhos

Para criar cabeçalhos é fácil. Veja só:

    Isso é um cabeçalho H1
    ======================

    Isso é um cabeçalho H2
    ----------------------

Para criação de títulos dessa forma, qualquer quantidade de caracteres
= (igual) e - (traço) irá funcionar.

    Este título H1 funcionará corretamente
    =

    Este título H2 funcionará corretamente também
    -

Outra forma de criar cabeçalhos é com #. Veja:

    # Este é um H1
    ## Este é um H2
    #### Este é um H4
    # Eu posso fechar o cabeçalho, mas não sou obrigado #
    ## Não importa quantos #'s eu uso para fechar #
    ### O que determina o tipo de título é a são as cerquilhas de abertura #

### Blocos de citação (blockquotes)

Use > para definir citações:

    > "Mussum ipsum cacilds, vidis litro abertis. Consetis adipiscings elitis.
    > Pra lá , depois divoltis porris, paradis."  
    > - Mussum Ipsum

Veja o resultado:

> "Mussum ipsum cacilds, vidis litro abertis. Consetis adipiscings elitis.
> Pra lá , depois divoltis porris, paradis."  
> \- Mussum Ipsum

Você pode também dar uma de preguiçoso e botar o > apenas na primeira linha:

    > "Mussum ipsum cacilds, vidis litro abertis. Consetis adipiscings elitis.
    Pra lá , depois divoltis porris, paradis."  
    - Mussum Ipsum
