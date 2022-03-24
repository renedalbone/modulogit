Meu primeiro sistema no GIT


alteração do readme


principais comandos
Git Status
Git add -A
Git commit -m "colocar uma descricao"
git commit -am "colocar uma descricao"

com o -am ele já faz o mesmo que o -A e o -m

Git log
Git reset --soft colocar a chave

o reset pode ser com soft, hard e 

git branch = mostra em qual branch está


git branch nome = cria um novo branch

git checkout nome - altera para esse branch


git diff = mostra as alterações

git diff --name-only = mostra apenas o nome dos arquivos modificados

git checkout HEAD -- nome do arquivo (volta apenas esse arquivo para não precisar comita-lo)

para criar uma chave para concetar no github deve entrar no bash
e colocar a linha de comando abaixo

 ssh-keygen -t rsa -b 4096 -C "dalbonerenedev@gmail.com"


Para adicionar do local para o github
git remote add origin https://github.com/renedalbone/modulogit.git
git branch -M main
git push -u origin main

para ver o que tem digita
git remote

para ver as opções digite
git remote -v

é possivel ignorar arquivos para não precisar adicionar ou commitar
para isso deve criar um arquivo chamado gitignore e dentro dele colocar
o nome dos aquivos que serão ignorados, pode ser *.extensão do arquivo.

git revert = volta o commit sem perder o código
git revert --no-edit <colocar a chave do ultimo commit>

DELETAR um branch remoto = colocar o dois pontos
git push origin :nome do branch

DELETAR um branch local 
git branch -D nome do branch

para puxar uma atualização do github para local
git pull origin nome do branch 

CLONAR um projeto
git clone url do projeto 

