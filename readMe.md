URL === 'https://github.com/LuccasAmbrozio/First-site.git'

git clone "URL DO ARQUIVO"

git add . === seleciona todos os arquivos
git commit -m === faz o commit de todas as mudanças
git push origin main === salva as mudnaças no github, na branch main

git checkout -b "NOME DA BRANCH" === cria uma nova branch
O que é branch, uma copia do arquivo main (arquivo principal), para você poder fazer as suas mudanças, e depois pedir para mesclar com a branch main

git pull origin main === Puxa as mudanças feitas no main (como dito no push) para o seu computador

VOCÊ NÂO PRECISA DISSO PARA ESSE ARQUIVO, MAS CONHECIMENTO GERAL

git init === isso cria um novo repositorio
git remote add origin 'URL DO SEU REPOSITÓRIO DO GITHUB"
Essa sequência faz você criar um repositório (git init), e depois fala para o git para quando você fizer o commit e o push ele ir para o seu repositório do github (git remote)
