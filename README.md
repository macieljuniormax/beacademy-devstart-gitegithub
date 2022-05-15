
# Be Academy DevStart Git e GitHub

Repositório criado para armazenar os principais comandos do git abordados no Programa DevStart da Be Academy em parceria com a PayLivre.
## Autor

- [@macieljuniormax](https://www.github.com/macieljuniormax)


## Configuração ⚙️

Configurar nome do usuário
``` bash
git config --global user.name "Maciel Júnior"
```

Configurar e-mail do usuário
``` bash
git config --global user.email macielfcjunior@icloud.com
```

## Repositório Local 🗄

Inicializar um repositório
``` bash
git init
```
## Comandos mais utilizados 💻
Exibir o estado atual do repositório (alterações realizadas, alterações que não foram adicionadas, etc.)
``` bash
git status
```
Adicionar o arquivo especificado para a staged area
``` bash
git add nome_do_arquivo
```
Adicionar todas as alterações para a staged area
``` bash
git add .
```
Remover um arquivo da staged area
``` bash
git rm --cached nome_do_arquivo 
```
Fazer um commit para confirmar e salvar o que foi modificado no repositório
``` bash
git commit -m "mensagenm do commit"
```
Exibir histórico de commits
``` bash
git log
```
Exibir histórico de commits em apenas uma linha
``` bash
git log --oneline
```
## Ramificações 🔀
Exibir todas as branchs existentes e indica a que que voc'e está no momento
``` bash
git branch
```
Criar um branch
``` bash
git branch nome_da_branch
```
Navegar para uma branch
``` bash
git checkout nome_da_branch
```
Criar uma nova branch e já fazer o checkout
``` bash
git checkout -b nome_da_branch
```
Remover uma branch
``` bash
git branch -d nome_da_branch
```
Mesclar as alterações feitas em uma branch com a branch principal
``` bash
git merge nome_da_branch
```
## Repositório Remoto 🌍

Clonar um repositório remoto para a sua máquina
``` bash
git clone enderreço_do_repositório
```
Exibir os repositórios remotos
``` bash
git remote -v
```
Enviar as alterações para o repositório remoto
``` bash
git push 
```
Atualizar branch atual de acordo com o repositório remoto
``` bash
git pull
```
## Stash 🔄
Para alternar entre uma branch é necessário fazer o commit das alterações atuais previamente. Caso haja a necessidade de realizar a troca sem fazer o commit, é possível criar um Stash


Cria um stash
``` bash
git stash
```
Cria um stash incluindo um arquivo que ainda não esteja sendo rastreado
``` bash
git stash --include-untracked
```
Listar os stashes disponíveis
``` bash
git stash list
```
Recuperar um stash específico
``` bash
git stash pop stash@{x} 
```

## Revertendo um commit ↩️
Desfazer o último commit
``` bash
git revert HEAD
```
Desfazer um commit utilizando os quatro primeiro dígitos hash (xxxx) do commit
``` bash
git revert xxxx
```

