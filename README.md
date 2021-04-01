# Resumo de git :cool:

Ola! Resumo breve sobre git :wave:

- Strogonoff de frango :chicken:

*git init* - cria um novo repositório/inicializa um repositório em uma pasta
     git init
*git add* - adiciona os arquivos no repositório 
     git add <arquivo>
     git add * ou git add . (todos os arquivos)
*git commit* - confirma as mudanças feitas através de um comentário(commit)
     git commit -m "comentários das alterações"

*git-status* - Exibe o a condição da árvore de trabalho

####  Se não foi feita clonagem de um repositório existente, então deverá conectar seu repositŕio a um servidor remoto

*git remote add origin <servidor>*
*git remote -v* - traz os repósitorios remotos na qual o repositorio local esta apontado
*git push origin master* - envia as alterações ao seu repositório remoto
*git pull origin master* puxa a versão mais nova do repositorio remoto

*git config --list* Irá trazer a lista de todas as configurações que estão especificamente no seu git

*git config --global --unset* - reescrever as configurações
      *git config --global --unset user.email*
      *git config --global --unset user.name*
      *git config --global user.email "exemploemail@email"*
      *git config --global user.name "exemploname"*



