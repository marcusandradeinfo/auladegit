AULA DE GIT E GITHUB


MUDAR O NOME DA BRANCH

git branch -M "nome da branch"

INICIA O REPÓSITÓRIO REMOTO DO GITHUB NA MÁQUINA

git remote add origin https://github.com/marcusandradeinfo/auladegit.git

*origin é o apelido do repositório no github

SUBIR OS ARQUIVOS PARA O GITHUB

git push -u origin main

* origin - É o nome do repositório remoto
* main  - É o nome da branch principal

CRIAR UMA NOVA BRANCH

git checkout -b "nome da nova branch"

CRIAR O MERGE ENTRE AS BRANCHS

git merge "branch paralela"

FAZER O DOWNLOAD DO REPOSITÓRIO DO GIT PARA O COMPUTADOR

git clone https://github.com/marcusandradeinfo/auladegit.git

BAIXAR ATUALIZAÇÕES DE UM REPOSITÓRIO

git pull
