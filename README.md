iniciar novo packet com git na maquina
### git init

definir as configuraçoes do usuario
### git config --local user.nome Fabio
### git config --local user.email fabioserrao16@hotmail.com

baixa arquivos do git
### git clone --branch <branch_name> <repository_url>
### git clone --branch 1.0 https://github.com/serraof/estudogit.git

verificar a branch
### git branch

baixar as atualizaçoes
### git pull

verificar aquivos locais alterados
### git status

adicionar arquivo criado ao indice(staging area), (working diretory) e repositorio git
### git add <file>
### git add README.md

para  adicionar todos os arquivos
### git add .

representa um conjunto de alterações em um ponto especificodo projeto, registra algumas allteraçoes adicionadas ao indice de preparação.
Comando -m insere umna mensagem de commit diretamente pelo linha de comando
### git commit -m "criar o arquivo readme"

envia os commits para repositorio remoto
### git push <remoto> <branch>
### git push origin 1.0

arquivo completo 1.0