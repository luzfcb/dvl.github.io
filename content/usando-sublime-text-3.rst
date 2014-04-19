Usando o Sublime Text 3
#######################

:date: 2014-03-12 12:49
:tags: sublimetext, rascunhos
:category: Geral
:slug: usando-o-sublime-text-3
:author: André Luiz
:summary: Usando o Sublime Text 3


Creio que venho usando o Sublime Text desde 2011 e hoje posso falar que sou
totalmente dependente dele, por vários motivos que pretendo citar em topicos
abaixo.

=======
Plugins
=======

* All Autocomplete
    Por padrão o Sublime Text usa somente expressões contidas no documento
    atual na janela de auto complete, esse plugin faz com que esse comportamento
    seja alterado e que ele passe a usar todos os arquivos abertos.
* ChangeQuotes
    As vezes acho que tenho TOC, esse plugin substitui aspas simples por duplas
    e vice-versa.
* Color Highlighter
* Emmet
* EncodingHelper
    Por ser obrigado a lidar com vários scripts feitos por outras pessoas, em
    diferentes editores e diferentes sistemas operacionais uso esse plugin para
    garantir que o arquivo que estou trabalhando sempre fique com a mesma
    codificação na qual foi salvo originalmente.
* Git
    Basicamente funciona como um atalho para os comandos do Git dentro do
    editor, além de permitir que você preencha as mensagens de commit dentro
    de uma janela do próprio Sublime Text.
* GitGutter
* Jinja2
    Syntax Highlight para o sistema de template Jinja e que *por um acaso*
    casa perfeitamente bem com o sistema de templates do Django.
* JQuery
    Algumas facilidades e auto-complete para JQuery para tentar tornar minha
    experiencia ao usar Javascript menos desagradavel.
* LESS
* `Package Syncing <https://sublime.wbond.net/packages/Package%20Syncing>`_
    Devo usar uns 3 computadores diferentes (Trabalho, Desktop em dual-boot
    e Notebook), e uso o Sublime Text em todos eles, o que torna extremamente
    desagradavel manter todas as instações sincronizadas para que eventualmente
    não sinta falta de alguma função ou outra enquanto uso uma instalação
    diferente.

    Esse plugin se baseia no compartilhamente de arquivos do Dropbox (aonde é
    possivel configurar para que se baixe somente uma sub-pasta) e se encarrega
    de replicar todos os plugins e configurações para todas as maquinas que
    você usar.
* Placeholders
* SideBarEnhancements
* SublimeCodeIntel
* SublimePythonIDE
* SublimeREPL
* Trimmer
    Mais um caso de TOC, espaços em branco no final da linha me deixam
    extremamente incomodado, esse plugin remove esses espaços quando você salva
    o arquivo.

=====
Temas
=====
* LAZY
    Esse tema já vem instalado por padrão no Sublime Text, sempre gostei do
    fundo de tela claro.
* Colour Schemes by Dayle Rees
    Uma coleção de vários temas, particularmente usava o **Snappy Light**
    que é outro tema claro.
* Soda Theme
    Usei por um tempo para customizar a UI do Sublime Text, com o tempo comecei
    a achar que deixava a aplicação mais lenta, mas na epoca usava um PC
    mais modesto (Um maltido Atom na empressa antiga) e acabei nunca voltando
    a usar depois disso.

============
Configuração
============

===============
Funcionalidades
===============

* Auto Save
    Ok, não é bem esse o nome mas não sei como se chama, é a funcionalidade que
    mantem o estado dos arquivos que você está trabalhando que não foram salvos
    mesmo que você feche o Sublime Text, que seu sistema trave, falte luz, que
    sua fonte queime, já pasei por tudo isso, e na execução seguinte do programa
    meu arquivo estava lá exatamente do jeito que o vi pela ultima vez.
* Build (CTRL+B)
* Command Pallet (CTRL+SHIT+P)
* Convert Indentation
* Find in Files
* Goto (CTRL+P)
* Layout
* Permute Lines
* Snippets
* Sort Lines (F9)
    Alguem acha que eu escrevi essas listas em ordem alfabetica manualmente?
    selecione várias linhas, aperte F9, e pronto, estão ordenadas.
* Editar várias linhas ao mesmo tempo
    É um dos exemplos existentes na página inicial do Sublime Text, e um dos
    motivos que me fizeram baixar ele a vários anos atras.

    Selecione várias linhas, aperte CTRL+L e você tera um cursor em cada uma.

    Selecione uma palavra, vá apertando CTRL+D para selecionar a próxima
    ocorrencia dessa palavra ou use o CTRL+F e o Find all para selecionar todas
    e você tera um cursor em cada uma delas.
* Mover uma ou várias linhas
    Selecione um ou várias linhas, segure CTRL+SHIT e então use as setas para
    cima e para baixo para movimentar o texto.
* Copiar/Recortar toda a linha
    Coloque o cursor em alguma linha (até mesmo sem selecionar o texto), aperte
    CTRL+C ou CTRL+X para colocar toda a linha na area de transferencia,
    lembre-se: ao colar o texto será sempre inserido na linha acima do cursor.
* Incrementar / Decrementar números
    Selecione um número, segure CTRL e então use as setas para cima e para baixo.


=======
Atalhos
=======
* Deletar toda a linha: CTRL+SHIT+K
* Desindentar a linha: CTRL+{
* Comentar ou descomentar a linha: CTRL+/
