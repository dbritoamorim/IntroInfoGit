# Aula1GitT3
* Aula de Git e GitHub

Git Config comandos:
*git config > Usado para configuração do git
*git config --global user.email sam@google.com > Configurar e-mail de usuario no Git

Git init comandos:
*git init > Usado para criar um novo repositório GIT.

Git add comandos:
*git add (+arqivo) > Adiciona um arquivo para o diretório principal
*git add. > Adiciona todos os arquivos do diretório.


Git clone comandos:
*git clone abcd@93.188.160.58:/path/to/repository > Usado para baixar arquivos em um repositório remoto
*git clone /path/to/repository > Usado para baixar arqivos em repositório local.

Git commit comandos:
*git commit –m “coloque sua mensagem aqui” > Usado para confirmar as alterações em um arquivo.

Git status comandos:
*git status > Exibe a lista de arquivos alterados juntamente com os arquivos que ainda não foram adicionados ou confirmados.

Git push comandos:
*git push origin master > Envia as alterações para o repositório remoto.

Git checkout comandos:
*command git checkout -b <branch-name> > Usado para criar uma nova branch e mudar para ela.
*git checkout <branch-name> > Muda de uma branch para outra.

Git remote comandos:
*git remote -v > Lista repositórios remotos configurados.
*git remote add origin <93.188.160.58> > Conexta a um servidor remoto.

Git branch comandos:
*git branch > Lista as branchs do repositório.
*git branch –d <branch-name> > para excluir uma branch.

Git pull comandos:
*git pull > Enviar todas as alterações no repositório.

Git Merge comandos:
*git merge <branch-name> > Usado para mesclar uma branch na branch ativa.

Git diff comandos:
*git diff --base <file-name> > Visualizar conflitos com o arquivo base.
*git diff <source-branch> <target-branch> > Exibir os conflitos entre branchs antes de realizar o merge (mesclar)
*git diff > Listar todos os conflitos atuais

Git tag comandos:
*git tag 1.1.0 <insert-commitID-here> > Usado para realizar marcações com tags (comando com exemplo de marcação)

Git log comandos:
*git log > Exibe uma lista de logs em uma branch
Exemplo de saída do comando: 
$ git log
commit 7dc52ae09c33f042f1fb86cf5e8c6a6e068d9e59 (HEAD -> main, origin/main)
Author: diego <diego.brito.a@gmail.com>
Date:   Wed Oct 27 22:02:12 2021 -0300

    editado o arquivo READ.md

commit c0b77dc6648c1de13a37ab29c9e48e2977802c40
Author: diego <diego.brito.a@gmail.com>
Date:   Wed Oct 27 21:27:16 2021 -0300

    first commit

Git reset comandos:
*git reset > Usado para redefinir o diretório 
*git reset --hard HEAD > Redefir para o ultimo commit

Git rm comandos:
*git rm (+nome do arquivo) > Usado para remover arquivos

Git stash comandos:
*git stash > Salvar alterações que não irão para o commit imediatamente, ficam salvas em uma base temporária.

Git show comandos:
*git show > Visualizar informações sobre o projeto em trabalho.

Git fetch comandos:
*git fetch origin > Obter todos os dados do repositório remoto que ainda não estejam no repo local.

Git LS comandos:
*git ls-tree: Exibe uma arvore junto com o nome e o modo de cada item.
* git ls-tree HEAD (Exemplo)

Git cat-file comandos:
*git cat-file –p d670460b4b4aece5915caf5c68d12f560a9fe3e4 > Exibe um tipo de objeto usando o valor SHA-1.

Git grep comandos:
*git grep " " > Procura através do projeto, frases ou palavras

Gitk comandos:
*gitk > Exibe uma interface gráfica (MUITO TOP)

Git instaweb comandos:
*git instaweb > Executar um servidor web jutamente com um repo local

Git gc comandos:
*git gc > Limpar arquivos desnecessários e otimizar o repositório.

Git archive comandos:
*git archive --format=tar master > Permite criar um arquivo ZIP ou TAR com os componentes de um repositório.

Git prune comandos:
*git prune > Arquivos sem marcação de entrada são excluidos (Não entendi ver com o professor)

Git fsck comandos:
*git fsck > Verifica a integridade do sistemas de arquivos Git, usado para verificar arquivos corrompidos.

Git rebase comandos:
 *git rebase master > Usado para a reaplicação de arquivos em outra branch. (Tbm não entendi ver com o professor).








