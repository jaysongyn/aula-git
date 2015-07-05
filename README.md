#Criando Reposit�rio local GIT

- Voc� pode criar um novo reposit�rio ou versionar um reposit�rio j� criado
- Criando Reposit�rio

`mkdir <nome_diretorio>`

#Versionando Reposit�rio

- � criado uma pasta .git onde cont�m as informa��es das vers�es, para remover o versionamento basta excluir .git.

`git init`

#Estados do Commit

- Para entender melhor como funciona o git crie um arquivo.txt escrito "Hello world" na pasta versionada

- O git possui tr�s estados.

- Para verificar o status
`Comando git status`

* Untracked File: quando o arquivo ainda n�o foi adicionado para seu controle de vers�o. 

* Changes to be commited: quando o arquivo faz parte do seu versionamento e est� pronto para ser comitado

`git add <nome_arquivo>
git add --all`

* Commited: quando voc� comita sua aplica��o

`git commit`

- Para verificar basta digitar novamente 

`git status`

**DICA**
- Para voltar um arquivo no estado de untracked basta digitar

`git reset HEAD <nome_arquivo>`


**DICA**
- Para pular etapa dois e j� comitar todos os arquivo basta digitar

`git commit -a`

#Configurando Reposit�rio

- Depois de criar o reposit�rio online na sua conta do GITHUB agora � a hora de fazer a comunica��o com sua m�quina. 
- Para fazer essa configura��o digite o comando abaixo. 

`git remote add origin <caminho_github>`
exemplo https://github.com/jaysongyn/aula-git.git

#Commit para GITHUB

- Para enviar os arquivos para o servidor basta digitar o comando. 

`git push origin master`

**Para mais informa��es acesse minha [wiki Page!](https://desenvolvimento.wiki.zoho.com)**
