Arquivo de aprendizado de git...

Crie uma nova pasta (criar um diretório)
mkdir <NOMEDAPASTA>
Navegar para dentro desta pasta (mudar de diretório)
cd <NOMEDAPASTA>
Lista dos itens dentro de uma pasta
ls
Inicializa o Git em uma pasta
git init


Checar o estado das mudanças em um repositório
git status
Ver mudanças em arquivos
git diff
Preparar um arquivo para ser commitado
git add <NOMEDOARQUIVO>
Preparar para commit todos os arquivos que foram modificados
git add .
Para fazer commit ("salvar") as mudanças que você fez com uma curta mensagem de descrição
git commit -m "sua mensagem de commit"


Adicione seu nome de usuário GitHub à sua configuração:
git config --global user.username <USUARIO>
Você pode checar novamente o que você colocou na sua configuração Git digitando:
git config --global user.username


Adicionar remotos
git remote add <NOMEDOREMOTO> <URL>
Remover remotos
git remote rm <NOMEDOREMOTO>
Mudar o URL de um remoto
git remote set-url <NOMEDOREMOTO> <URL>
Receber mudanças de um remoto
git pull <NOMEDOREMOTO> <NOMEDOBRANCH>
Ver os endereços dos remotos
git remote -v
Enviar mudanças
git push <NOMEDOREMOTO> <NOMEDOBRANCH>


Para criar um repositorio em compartilhado em rede local ou em computador local:
crie uma pasta que servira como pasta repositorio
$ mkdir <nome-da-pasta-repositório>
inicie o repositorio sem um diretório de trabalho
$ git init --bare
adicione o endereco da pasta repositorio aos repositorios de cada progrmador seguindo os passos da sessao anterior