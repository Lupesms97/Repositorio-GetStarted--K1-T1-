# Repositorio-GetStarted--K1-T1-



## $ git config --global user.name "[nome]"
Configura o nome que você quer ligado as suas transações de
commit

## $ git config --global user.email "[endereco-de-email]"
Configura o email que você quer ligado as suas transações de commit

##  git config --global color.ui auto
Configura o email que você quer ligado as suas transações de commit



## $ git status
Lista todos os arquivos novos ou modificados para serem commitados

## $ git add [arquivo]
Faz o snapshot de um arquivo na preparação para versionamento

## $ git reset [arquivo]
Deseleciona o arquivo, mas preserva seu conteúdo

## $ git diff
Mostra diferenças no arquivo que não foram realizadas

## $ git diff --staged
Mostra a diferença entre arquivos selecionados e a suas últimas

versões
## $ git commit -m "[mensagem descritiva]"
Grava o snapshot permanentemente do arquivo no histórico de versão

## $ git branch
Lista todos os branches locais no repositório atual

## $ git branch [nome-do-branch]
Cria um novo branch

## $ git checkout [nome-do-branch]
Muda para o branch específico e atualiza o diretório de trabalho

##  git merge [branch]
Combina o histórico do branch específico com o branch atual

## $ git branch -d [nome-do-branch]

## $ git init [nome-do-projeto]
Cria um novo repositório local com um nome específico

## $ git clone [url]
Baixa um projeto e seu histórico de versão inteiro


## $ git rm --cached [arquivo]
Remove o arquivo do controle de versão mas preserva o arquivo
localmente

## $ git rm [arquivo]
Remove o arquivo do diretório de trabalho e o seleciona para remoção

## $ git mv [arquivo-original] [arquivo-renomeado]
Muda o nome do arquivo e o seleciona para o commit



## $ git stash
Armazena temporariamente todos os arquivos rastreados modificados

## $ git stash list
Lista todos os conjuntos de alterações em stash

## $ git stash pop
Restaura os arquivos recentes em stash

## $ git stash drop
Descarta os conjuntos de alterações mais recentes em stash


SINCRONIZE MUDANÇAS
Registre um marcador de repositório e troque o histórico de versão

## $ git fetch [marcador]#
Baixe todo o histórico de um marcador de repositório

## $ git merge [marcador]/[branch]
Combina o marcador do branch no branch local

## $ git push [alias] [branch]
Envia todos os commits do branch local para o GitHub

## $ git pull
Baixa o histórico e incorpora as mudança

Esse resumo foi tirado desse [site:](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet.pdf)
