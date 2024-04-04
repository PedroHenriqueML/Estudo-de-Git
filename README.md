# meu-projeto

git init
- iniciar novo projeto com git

git add <nome-arquivo>/.
- add os arquivos que estão prontos para serem commitados

git commit -m "mensagem commit"
- commit os arquivos no historico

git log
- mostra os ultimos commit, log de alterações

git status
- como esta o estado da nossa ramificaçoes

git diff
- que mostra o que foi alterado
- o que tem de alteração na ramificação

git merge
- merge de ramificações, mescla ramificações

git branch
- mostra a branch atual

git checkout <nome-branch>
- muda pra essa branch

git branch -b <nome-da-branch>
-criar uma nova branch a partir da branch atual que estamos

git remote add <nome> <url>
- add um novo repositorio remoto

git push <nome> <nome-da-branch>
- manda nossas alterações locais para o repositorio remoto, pra cada branch

git pull <nome> <nome-da-branch>
- pega as alterações do repositorio remoto, e joga pra nossa maquina

git fetch
- atualiza o novo historico local de acordo com o historico salvo la no repositorio
- sincronização do local com o remoto
