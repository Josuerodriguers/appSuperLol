# 
echo "# Meu-reposit" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:Josuerodriguers/Meu-reposit.git
git push -u origin main

alguns comandos de git

[—— GITE GITHUB ———

COMANDO DESCRIÇÃO

git clone url-do-repositorio
git remote -v
git branch
git checkout -b nome-da-branch
git checkout nome-da-branch
git add nome-do-arquivo
gitadd.

git status

git commit -m "Mensagem
descrevendo a alteração”

git commit -am "Mensagem
descrevendo a alteração"

git pull

git pull origin nome-da-branch

git push -u origin nome-da-branch

git push

git push --set-upstream
origin nome-da-branch

git log

Clona/baixa um repositório remoto já
inicializado para a máquina

Verifica o repositório atual

Verifica as branches existentes e
mostra a branch atual

Cria uma branch nova (a partir da atual) e
alterna automaticamente para ela

Alterna para a branch especificada

Adiciona o arquivo especificado em staging
(espaço temporário antes do commit)

Adiciona todos os arquivos modificados em
staging (espaço temporário antes do commit)

Verífica o status dos arquivos do projeto

Cria um ponto de acesso para a alteração e
possui uma mensagem descrevendo quais
alterações foram feitas

Comando curto para git add e git commit. Não
adiciona arquivos novos, apenas as modificações
realizadas em arquivos existentes e realiza o commit.

Traz as alterações que estão
remotas da branch atual

Traz as alterações que estão remotas na branch
especificada para a branch atual (que você está
realizando modificações)

Deixa a branch acessível remotamente
e envia as alterações realizadas

Envia as alterações realizadas na branch
atual (quando a branch já está remota)

Aparece quando o comando git push é feito e a
branch ainda não está acessível remotamente

Mostra os registros dos commits
(alterações realizadas)
