# Comandos Iniciais para o uso do GIT/Github

## Configuração inicial
#### Configurar usuário
        git config --global user.name "Leonardo Lima"
        git config --global user.email leonardostlima@gmail.com

## Criando um projeto
### git init
##### Inicializando um projeto em um repositório existente
        git init

##### Primeira versão
        touch .gitignore
        git add .gitignore
        git commit -m "Versão inicial do projeto"

### git clone
        git clone (url do projeto a ser clonado)

## Alterações básicas
#### git add
        git add . (para adicionar todos os arquivos ao repositório)
        git add README (ou passar o nome de um arquivo específico)

#### git status 
        git status (verificar o estado dos arquivos)

#### git commit
        git commit -m "mensagem que aparecerá no commit" (usado após já ter adicionar com 'git add')
