Atividade Prática 10 - Trabalhando com GitHub

Título da Prática: Criação de repositório dentro do gitHub

Objetivos: Utilizar o versionador GitHub para desenvolver todas as etapas de criação do repositório e manipulação dele.

Materiais, Métodos e Ferramentas: Iremos fazer uma pesquisa na internet e utilizar o gitHub.

Atividade Prática

Informalmente, notamos que “uma versão” não pode existir por si só, mas deve ser entendida como sendo uma versão de algo. Assim, podemos tentar a seguinte definição: Uma versão é uma instância concreta potencial de algum objeto (específico).

Dias  (2016)  aponta  que  as perguntas à serem realizadas para analisar a necessidade de um software para controle de versão, são quatro: 

1. “Alguém já subscreveu o código de outra pessoa por acidente e acabou perdendo as alterações?”

2. “Têm dificuldades em saber quais as alterações efetuadas em um programa, quando foram feitas e quem fez?”

3. “Tem dificuldade em recuperar o código de uma versão anterior da que está em produção?”

4. “Têm problemas em manter variações do sistema ao mesmo tempo”

Caso alguma dessas perguntas acima tiveram um “sim” como resposta, logo se faz necessário um software para fazer o versionamento do código.

E seguindo essa linha de raciocínio podemos citar o git, que é um sistema open-source que serve para fazer o gerenciamento de versões. Ele foi desenvolvido por Linus Torvards, o mesmo desenvolvedor do Linux, que foi criado exatamente para gerenciar o desenvolvimento dos códigos do Linux, isso em 2005.

Segundo Buis (2018) “é o sistema de controle de versão mais usado por aí e sua influência é difícil de exagerar”.

Também não podemos deixar de mencionar que o versionador Git é um sistema para controle de versão “distribuído”, ou seja, ele não depende de um servidor centralizado.

Uma coisa muito interessante é que o git pode ser usado para controlar versões de vários formatos, como por exemplo, de códigos fonte, projetos de análise de dados, manuscritos, websites, apresentações etc.

E então vem a pergunta, mas porque usar o Git? Existem várias razões para isso dentre elas temos:

Ele é rápido;
Não é necessário que tenhamos acesso direto ao servidor, só se tivermos uma conta no git já é o suficiente;
Muito indicado para fazer o gerenciamento e a unificação simultânea do mesmo arquivo;
E atualmente se tornou o principal protocolo de gerenciamento de versões.
Outra ferramenta que podemos destacar é o GitHub.  Então podemos dizer que é uma rede social para gerenciar códigos e projetos.  Segundo Marques (2019) “Se o Git é o coração do GitHub, então o Hub é a alma. O hub de GitHub é o que torna uma linha de comando, como o Git, a maior rede social para desenvolvedores do mundo.”

Com isso podemos chamar o GitHub de “rede social”, pois dentro dele é possível uma socialização entre vários usuários e é um portfólio para indicar o que estão desenvolvendo. Todavia, vale ressaltar algo muito importante, o GitHub não é apenas para desenvolvedores, ainda segundo Marques (2019): O   GitHub   é   uma   ótima   plataforma   que   mudou   o   método   de   trabalho   de desenvolvedores.  Mas qualquer pessoa que deseja gerenciar seu projeto com eficiência e trabalhar com outros colaboradores também pode usar o GitHub.

GitHub é um serviço popular de compartilhamento de código social baseado na Web que utiliza o sistema de controle de versão distribuído Git. Tem se tornado uma ferramenta essencial em áreas de tecnologia que requerem colaboração, como desenvolvimento de software e redação técnica. Também está vendo uma adoção generalizada em outras áreas, transformando a forma como as pessoas colaboram em um repositório compartilhado. Um dos principais pontos fortes do GitHub está na conscientização e recursos de transparência que fornece aos membros da equipe, do projeto e da comunidade. Essas características influenciam positivamente como pessoas contribuem para projetos.

Agora que já entendemos o que é um versionamento, o ambiente de linhas de comando git e o ambiente gráfico do GitHub, vamos criar uma pasta com o nome do projeto da sua escolha e um arquivo chamado index.html

A seguir você irá adicionar o seguinte conteúdo ao arquivo:

<!DOCTYPE html>

<html lang=“pt-br”>

<head>

<title>Título da página</title>

<meta charset=“utf-8”>

</head>

<body>

<h1>Aqui vai um título</h1>

</body>

</html>

Copied!

Na sequência você irá subir o seu projeto para o GitHub.

1. Criar um repositório em seu GitHub.

2. Você irá abrir o seu terminal de comando e irá adicionar a origem remota e conectar o seu projeto local com o GitHub.

3. Verifique se as alterções que foram realizadas no seu projeto e assim adicionar ao fluxo de versionamento.

4. Execute um commit com uma mensagem útil e na sequência, você dará um push para o repositório remoto (GitHub).

Após isso você irá abrir uma pasta do seu projeto, e irá criar uma pasta chamada imagens, procure no Google por uma imagem de cachorro e salve dentro dessa nova pasta criada. Feito isso, irá abrir seu arquivo index.html e irá adicionar as seguintes modificações e salve o arquivo:



<!DOCTYPE html>

<html lang=“pt-br”>

<head>

<title>Fanpage de Gatinhos</title>

<meta charset=“utf-8”>

</head>

<body>

<h1>Perfil #catsoninstagram</h1>

<img src=“images/nome_da_sua_imagem.jpg” />

</body>

</html>
