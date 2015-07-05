#Criando Repositório local GIT

- Você pode criar um novo repositório ou versionar um repositório já criado
- Criando Repositório

`mkdir <nome_diretorio>`

#Versionando Repositório

- É criado uma pasta .git onde contém as informações das versões, para remover o versionamento basta excluir .git.

`git init`

#Estados do Commit

- Para entender melhor como funciona o git crie um arquivo.txt escrito "Hello world" na pasta versionada

- O git possui três estados.

- Para verificar o status
`Comando git status`

* Untracked File: quando o arquivo ainda não foi adicionado para seu controle de versão. 

* Changes to be commited: quando o arquivo faz parte do seu versionamento e está pronto para ser comitado

`git add <nome_arquivo>
git add --all`

* Commited: quando você comita sua aplicação

`git commit`

- Para verificar basta digitar novamente 

`git status`

**DICA**
- Para voltar um arquivo no estado de untracked basta digitar

`git reset HEAD <nome_arquivo>`


**DICA**
- Para pular etapa dois e já comitar todos os arquivo basta digitar

`git commit -a`

#Configurando Repositório

- Depois de criar o repositório online na sua conta do GITHUB agora é a hora de fazer a comunicação com sua máquina. 
- Para fazer essa configuração digite o comando abaixo. 

`git remote add origin <caminho_github>`
exemplo https://github.com/jaysongyn/aula-git.git

#Commit para GITHUB

- Para enviar os arquivos para o servidor basta digitar o comando. 

`git push origin master`

**Para mais informações acesse minha [wiki Page!](https://desenvolvimento.wiki.zoho.com)**
