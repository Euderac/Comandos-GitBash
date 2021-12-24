
# APRENDENDO COMANDOS NO GIT
### Neste tutorial estarei mensinando alguns comandos mais utilzados por iniciantes na interação do Git com o GitHubi

## COMANDOS GLOBAIS
- Listar pasta/arq. dentro do diretório                                      -> ls
- Limpa tela                                                                 -> ctrl+L
- Listar Pasta ocultas                                                       -> ls -a
- Move arquivo                                                               -> mv nome_do_arquivo.md ./pata_desejada/
- Criando pasta                                                              -> mkdir (nome da pasta)
- Criando arquivo                                                            -> echo > (nome do arquivo)

## COMANDO GIT
- Iniciaar comando                                                           -> git init
- Preparar pasta/arquivo para commit                                         -> git add/add *
- Digniicando ao Objeto                                                      -> git commit -m "comentáro"
- Verificar status da pasta/aqr.                                             -> git status


- git config --global user.email "Seu email de acesso na GitHub"
- git config --global user.name "Seu nome de usuário na GitHub
- Sair do usuario no Git -> git config --global unsat user.email


## CONFIGURANDO A GIT COM GitHub
- ssh-keygen -t ed25519 -C (email na GitHub)
- senha=Github
- cd/c/Users/ecosta/.ssh/
- cat id_ed25519.pub
- eval $(ssh-agent -s)
- ssh-add id_ed25519
- sennha=Github

## PASSANDO A PASTA PARA REMOTE
- Ver. se o Git ja se ecnotra configurado                                 -> git config --list
- Encontre o caminho da basta na GitHub                                   -> git remote add origin Url
- Manda a pasta para o local da url                                       -> git push origin master

## BAIXANDO AQUIVO DO GIT-HUB
Puxar                                                                     -> git pull origin maste/main
Clonando                                                                  -> git clone

## REMOVENDO PASTAS DA GitHub
- Remover o arquivo/pasta do seu dispositivo local.                       -> git rm -rf -- pasta/caso seja arquivo git rm --arquivo
- Clone a pasta na github pelo git                                        -> git clone
- Verifique a lista de pasta e arquivos                                   -> ls
- Remova o desejado                                                       -> git rm -rf -- pasta/ caso seja arquivo git rm --arquivo
- Adicionar o arquivo/pasta no .gitignore                                 -> echo "folder1/" > .gitignore
- Realize o commit                                                        -> git commit -m 'folder1'
- Mande o arquivo para github                                             -> git push origin master
- Remova o aquivo/pasta                                                   -> rm .gitignore
- Remova o arquivo/pasta                                                  -> git rm .gitignore