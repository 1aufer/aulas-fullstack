Git init - Start um repositório localmente criando um arquivo .git
Git status - Verifica o estado atual, indica quais arquivos são novos ou foram modificados
Git add - Adiciona arquivos para o próximo commit
Git rm --cached - Remove arquivos que foram adicionados com git add
Git branch -r - Mostra as branchs remotas disponíveis 
git branch -a - Mostra as branchs remotas e locais disponíveis
git checkout <nomedabranch> - Altera para branch solicitada
git checkout -b <nomedabranch> - Cria uma branch nova e altera para ela
git commit -m "Descrição" - Faz o commit das mudanças alteradas (arquivos novos e modificados
git merge <branch> - Mescla a branch atual na que foi informada
git push - Envia os commits do repositório local para o remoto, são mandados para a branch correspondente no repositório remoto
git branch -D <nomedabranch> - Exclui a branch que foi solicitada
git fetch - Faz o download de objetos e referências do repositório remoto, atualiza o local com informações do remoto sem merge
git pull - Faz o download de objetos do remoto e mescla com a branch atual