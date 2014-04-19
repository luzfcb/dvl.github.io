Ingresso.com e como não se armazenar senhas
###########################################

:date: 2014-04-19 17:33
:tags: seguranca
:category: Geral
:slug: ingressocom-e-como-nao-se-armazenar-senhas
:author: André Luiz
:summary: Ingresso.com e como não se armazenar senhas
:status: draft

Geralmente imaginamos que em sites maiores de grande visibilidade são mantidos
por equipes qualificadas que prezam por boas práticas e segurança, bom não é
exatamente isso que descobri nos ultimos dias.

Com o lançamento do ultimo filme do Capitão América resolvi fazer algo que não
costumo e ir ao cinema assistir, obviamente resolvi comprar o ingresso pela
internet por ser mais conveniente (o que descobri não fazer diferença pois você
tem que entrar em outra fila para trocar o ingresso) ao entrar no site do
Ingresso.com notei que não lembrava minha senha, ao iniciar o que imaginei ser
o processo de redefinição de senha levei um susto ao ver que a minha senha já
estava sendo enviada da forma como eu digitei sabe-se lá quando fiz o cadastro.

.. image:: /img/jesus-christ-how-horrifying.png
   :align: center
   :alt: Obvimente depois de alterar a senha eu pedi novamente que me fosse
         enviada a senha somente para tirar esse print, e em seguinte pedi
         que minha conta fosse deletada.

Ao ver o e-mail e notar minha senha sendo enviada ali sem qualquer cerimonia na
hora conclui que eles salvam as senhas dos usuarios em plaintext de forma que
qualquer um que tenha acesso ao banco de dados **o que aparentemente já
aconteceu e vários cliente receberam e-mails falsos que continham seus dados
pessoais**
`[1] <http://tecnoblog.net/152866/ingresso-com-emails-falsos-dados-cadastrais/>`_
`[2] <http://www.reclameaqui.com.br/8558297/ingresso-com/falha-de-seguranca-da-ingresso-com-tornou-publica-informacoe/>`_

Acabo de notar que o tecnoblog já citou essa questão das senhas em plaintext,
então até que eu termine meu levantamento mostrando como o PBKDF2 e bcrypt são
as melhores formas de se salvar senhas atualmente e que md5 já está ultrapassado
esse texto fica como rascunho não-publico.
