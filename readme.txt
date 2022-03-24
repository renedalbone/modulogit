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


