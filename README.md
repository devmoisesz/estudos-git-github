# Meus Estudos

git init
- inicar novo projeto com git

git add .
- add os arquivos que estão prontos para serem commitados

git commit -m ""
- commit os arquivos no histórico

git log
- mostra os ultimos commit, log de alterações

git status
- como está o estado da nossa ramificações

git remote add (url)
- add um novo repositorio remoto

git diff
- que mostra o que foi alterado
- o que tem de alteração na ramificação

git merge
- merge de ramificações, mescla ramificações

git branch
- mosta nossa branch atual

git branch nome-da-branch
- cria uma nova branch apartir do histórico que estamos

git branch -d branch
- deleta uma branch local
- não é possível deletar a branch atual, mude de branch antes

git branch -D branch
- deleta uma branch local forçando (mesmo sem merge)

git switch nome-branch
- muda pra essa branch
- se a branch não existir, dá erro.

git switch -c nome-branch
- cria uma nova branch e já entra nela

git checkout branch -- arquivo
- puxa arquivo de outra branch pra branch atual

git restore --source=branch arquivo
- puxa um arquico específico de outra branch pra branch atual
- versão moderna do: git checkout branch -- arquivo

git push <nome> <nome-da-branch>
- manda nossas alterações locais para o repositório remoto, pra cada branch

git push origin -u branch
- envia a branch para o repositótio remoto e define como padrão
- depois disso, pode usar só git push e git pull sem precisar especificar a branch

git push origin --delete branch
- deleta uma branch no repositorio remoto

git pull <nome> <nome-da-branch>
- pega as alterações do repositório remoto, e joga pra nossa maquina

git fetch
- atualiza o novo historico local de acordo com o historico salvo la no repositório remoto
- sincrozinação do local com o remoto