meu primeiro sistema no git



- install git no windows: baixando e executando
- git config --global user.name ....
- git config --global user.email ...
- git config --global editor ...
- git config --list

- git init
- git status
- git add .... ou git add -A
- git commit -m "Primeiro...."
- git commit -am "Segundo..."
- git log


git branch
git reset --hard ou soft + id(hash) 

git branch teste - criar novo branch
git checkout teste - troca de branch


git diff  - verificando alteração no arquivo
git diff --name-only


git checkout HEAD -- novodoarquivo.tct  -- voltar a versão anterior


criando repositorio no gitHub - new - nome do repositorio - descrição - public ou privada

no git bash - criar chaves publica e privada - ssh-keygen -t rsa -b 4098 -C "jcstecinfo@gmail.com"

entrar no repositorio e copiar a linha git remote add origin https://github.com/juliosantosphp/modulogit.git

fetch puxa para o computador local
push envia conteudo local para servidor remoto

git push -u origin

C588-B610