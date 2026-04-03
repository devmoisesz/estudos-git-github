# meus estudos

git init
- inicar novo projeto com git

git add <nome-arquivo>/.
-add os arquivos que estão prontos para serem commitados

git commit -m ""
- commit os arquivos no histórico

git log
- mostra os ultimos commit, log de alterações

git status
- como está o estado da nossa ramificações

git diff
- que mostra o que foi alterado
- o que tem de alteração na ramificação

git merge
-merge de ramificações, mescla ramificações

git branch
-mosta nossa branch atual

git checkout <nome-branch>
- muda pra essa branch

git branch -b <nome-da-branch>
-cria uma nova branch apartir do histórico que estamos

git remote add <nome> <url>
- add um novo repositorio remoto

git push <nome> <nome-da-branch>
-manda nossas alterações locais para o repositório remoto, pra cada branch

git pull <nome> <nome-da-branch>
- pega as alterações do repositório remoto, e joga pra nossa maquina

git fetch
- atualiza o novo historico local de acordo com o historico salvo la no repositório remoto
-sincrozinação do local com o remoto