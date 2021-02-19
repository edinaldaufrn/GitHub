# GitHub
Como usar o GitHub

Depois do Git e do GItHub instalado e configurado
Crie uma pasta para ser compartilhar os aquivos com o github no computado, no explorador de arquivo(janela de arquivo)
cliquer na opção Exibir, e marque a opção item ocultos. a pasta irá permanecer do mesmo jeito, ou seja, sem nada.
e dentro desta pasta com o botão direito do mouse
clique em Git Bash here, e irá abrir o tela do MINGW
Digite: Ls (tudo minusculo e der enter), irá mostra que a pasta está vazia

Para criar um repositório local no projetodigite: git init e der enter
será criada um pasta .git dentro da pasta que voce escolheu para compartilhar.
o ponto no .git, indica que é um diretório oculto.
DIgite:
ls ( clique enter)
ls -a (clique em enter), este comando mostra as pastas que são oculta
será mostrado a pasta .git na tela

Abra a pasta .git agora no computador, veja que foi criado 4 pasta e 3 documentos, e entre as pastas, a pasta objects dentro desta pasta
terá a pasta info e pack

Na pasta objects o git irá criar o grafo de commits.

Grafo de Commits, o git armazena o conteúdo do projeto representando as muldanças através de um grafo de commits.
Grafos é uma estrutura que contém objetos relacionados.

Commits é um comentário que você escreve sempre que se é modificado alguma coisa no projeto.
Antes armazena o conteúdo e formar grafo de commits o git precisa gerenciar as muldancas do projeto.
para isso, exeste uma especie de conteine onde deve ser adicionados todos os arquivos e pastas que foram ciados ou modoficados.
Para isso é usado o 
git add para fazer isso.
git status verifica o que está armqzenado no conteine
git commit identifica e armazena o conteine no repositório local, .git
dentro do repositorio .git será armazenado conteines que são identificados.
dentro doa conteines há o conteúdo do projeto.

Alnuns comandos:
clear (clicar em enter)-> limpa tela
git status (clicar em enter)-> mostrar os arquios que estão na pastar  .git
touch nomeArquivo.txt (clicar em enter)-> criar um arquivo na pasta com o nomeArquivo
ls (clicar em enter)-> mostras os arquivos criados na pasta .git se caso estiver ocultos ou não

Para dicionar um arquivo de cada vez:
git add nomeArquivo.txt (clicar em enter)-> o arquivo será adicionado
git add * (clicar em enter)-> adiciona todos os arquivos
 
 Difita de novo
 git status(clicar em enter)-> agora os nomes dos arquivos estaram em verde indica que os arquivos estão dentro do conteine.
  Feito isso agora é preciso indentidicar o conteine e armazenar no repositorio
  digite
  git commit -m "deixe o seu comentario aqui" (clicar em enter)
  feito isso digite
  ls (clicar em enter)-> mostrar os arquivo
  Para a indentificação do conteúdo do projeto digite
  git log (clicar em enter)-> mostra o comentário e a indentificação commit
  
  Para abrir o visual studio code difite
  code . (clicar em enter)-> irá abrir o visual estudio code
  
  




