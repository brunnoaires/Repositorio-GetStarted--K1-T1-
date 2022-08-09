Passos - 1* - Criar nova branch - git checkout -b "nome_da_branch"
obs: Cada branch deve resolver uma nova feature, ou uma issue ou um update
Nesse caso pode ser uma branch só pra cada e ir alterando conforme o necessário,
mesmo não sendo uma boa prática.
Passos - 2* -  Fazer alterações - enter "git status" e veja quais alterações voce quer
commitar pro seu repositório local
Passos - 3* -  enter "git add <nome_do_arquivo>aqui pode ser um ou vários arquivos,
separados cada um por espaço"
Passos - 4* - enter "git pull origin main" após commitar tudo que você salvou no local, para evitar conflitos
Passos - 5* - enter "git push"
passos - 6* - Vai no github, entra na sua branch no repositório e clica em create merge request ou pull request
não lembro como é no github, mas é um botão gigantesco verde que não tem erro
no topo da página
passos - 7* - Se não houver conflitos -o github mostra isso -, você pode aprovar a
merge request, ou pedir pros amigos do grupo baixarem sua branch com "git checkout <nome_da_branch>"
e ver se tem algo errado, caso não tenha é só aprovar o merge request