cd /g/git_rbtech/local
id_ed25519.pub

eval "$(ssh-agent -s)" sem aspas eval $(ssh-agent -s)
ssh-add ~/.ssh/nome_da_chave---->

$(ssh-agent -s)
ssh-add ~/.ssh/id_ed25519

git help ---
git config --global user.name "AlexandreJupiter"
git config --global user.email "alexandresoarespereiralima@gmail.com"
git config --global core.editor nano
git config user.name
git config --list
git init
git add .
git commit -m "mensagem"
git commit -a -m "mensagem" ---> commita sem precisar dar o add
git status
git diff
git diff --staged
git diff --name-only
git log
git log -p
git log -p -1
git log --author="AlexandreBitworld"
git log --pretty=oneline
git shortlog
git log --decorate
git shortlog -sn
git log --graph
gitk
git show f5b1626ecac31b17eb8855f14bb1f3fd9087f20a
git commit --amend -m "commit 04"
git reset HEAD novo.php
git checkout -- novo.php (desfaz mudanças)
git rm nomearquivo (remover arquivo)
git tag
git tag -a v1.0 -m "versão 1.0"
git tag -a v0.0 1d20229444319e51266ee2054558579fd4d56b5e -m "versão 0.0"
git tag -d v0.0 (excluir a tag)
git show v1.0
git checkout v0.0
git checkout v1.0
git checkout v2.0
git checkout master
git branch teste
git checkout teste
git checkout master
git merge teste
git branch -d teste
git branch -D teste
https://www.treinaweb.com.br/blog/comandos-do-git-que-voce-precisa-conhecer-parte-1

rede local
git init --bare

ele cria na sua maquina
git clone file:////athena/g/git_projetos/rbtech_projeto/cliente1 jupiter

git push origin master

git remote
git remote -v
git branch -M main
git branch master
git remote add origin git@github.com:AlexandreBitworld/rbtech_curso.git
git push -u origin main

…or create a new repository on the command line
echo "# rbtech_curso" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/AlexandreBitworld/rbtech_curso.git
git push -u origin main
…or push an existing repository from the command line
git remote add origin https://github.com/AlexandreBitworld/rbtech_curso.git
git branch -M main
git push -u origin main
