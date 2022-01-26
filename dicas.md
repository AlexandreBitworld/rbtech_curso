cd /g/git_rbtech/local
id_ed25519.pub

eval "$(ssh-agent -s)" sem aspas eval $(ssh-agent -s)
ssh-add ~/.ssh/nome_da_chave---->

$(ssh-agent -s)
ssh-add ~/.ssh/id_ed25519

git init
git add .
git commit -m "mensagem"
git commit -a -m "mensagem" ---> commita sem precisar dar o add
git status
git diff
git diff --staged
git log
git log -p
git log -p -1
gitk
