   # Scenes pt1__
- [x] Criar pontos na historia da produçao do seu projeto 


# git init 
o local onde esta sendo guardado as coisas do seu projeto

# touch landinpage.html
criei esse arquivo

# git add nome_do.file
add o arquivo no git

# git commit -m "adicionado o landinpage"
adiciona um comentario daquilo que vc acabou de fazer 



   # Scenes pt2__
- [x] Verificar mudanças feitas no seu projeto

# git log
vizualiza os pontos da linha do tempo / commit

# git status
mostra o estado de alteraçao feito ate agora

# git show
mostra os pontos da historia de um commit expecifico
cada commit foi um ponto da historia do file

- 1
commit a224b7512495e186e448442650c7c5915a467eb3
- 2
commit 766ff8dd46f68ca0a8eaf83927a243335be66e63



   # Scenes pt3__
- [x] começar uma funcionalidade sem estragar o projeto q ja foi feito
- [x] adiciona as novas funcionalidades ao seu projeto em produçao
- [x] quer deletar uma branch da nova funcionalidade, depois aplicar no projeto

# git branch feature/test
# git checkout feature/test
# git status

cria uma linha fora a parte, entra nessa linha e verifica se entrou nela

# ls -al
.

# git merge 
para juntar os files das branchs separadas
no caso a feature/test entrar na master

# git branch -D feature/test
agora q ja foi adicionado os files dessa feature, nao tem mais utilidade essa linha
e deletando ela dessa forma



   # Scenes pt4__
- [] colocando o projeto na nuvem

# git remote add origin 'link do repositorio'
tem-se os arquivos locais no seu pc e os remotos no git
com esse comando consigo linkar os files para o remoto

# git remote -v

# git push -u origin master

# git add .
adiciona todos os files para o remoto

# git config credential.helper store
nao precisa colocar user e password toda hora