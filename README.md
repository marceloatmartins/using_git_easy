Iniciar novo packet com GIT na máquina, este comando só se executa uma única vez
### git init

Atribuir o nome do usuário / email
### git config --local user.name MacMar
### git config --local user.email marceloatmartins@gmail.com

Clonar o repositório do GitHub para máquina local, pegue a URL HTTPS do repositóri no Portal do GIT
### git clone --branch 1.0 https://github.com/marceloatmartins/using_git_easy.git

Verificar a branch que está usando
primeiro faça um CD para dentro da pasta da branch
### cd using_git_easy
### git branch

Baixar as atualizações, faça uma alteração manual no arquivo "index.html" do github (o git pull vai no github e puxa as alterações realizadas para o repositório local)
### git pull

Verificar STATUS, ver arquivos que eu tenho alterados
### git status

Adicionar o arquivo criado no repositório local para a area de STAGING (o arquivo fica numa area intermediaria)
### git add README.md (para um arquivo)
### git add . (para todos os arquivos)

Fazer o commit, ou seja, persistir o arquvo no repositório do github (colocar um indicação de quem criou o arquivo)
### git commit -m "MacMar adicionou o arquivo na branch"

