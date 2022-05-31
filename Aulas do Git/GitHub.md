#Primeiros passos no GitHub/Git Bash
###Criando uma pasta

- Utilize **mkdir** seguido do nome do diretório que se deseja criar.
	- Ex.
		
			$ mkdir Anotacoes 			# para criar diretório com este nome "Anotacoes".

###Alterando o diretório de trabalho

 - Utilize **cd** para mudar diretório
 	- **cd ..** - retorna para diretório anterior
 	- **cd** seguido do nome do diretório - avança para o diretório indicado

###Listando arquivos de um diretório
 - Utilize **ls** para listar os arquivos
	 - Para listar arquivos ocultos utilizar a flag *-a*. 
		 - Ex:
		 
		 		$ ls -a				# Lista arquivos ocultos como .git

###Criando um arquivo dentro de um diretório
 - Utilize **>** seguido do nome do arquivo, bem como extensão do mesmo.
	 - Ex. 
	 	
			$ > GitHub.md 			# Para criar um arquivo markdown chamado "GitHub"
 - Utilize **echo > nome do arquivo**

### Movendo um arquivo entre diretórios
 - Utilize **mv nome do arquivo local do diretório**
 
###Iniciando um repositório Git em um diretório
 - Abrir **Git Bash** no diretório ou "navegar" utilizando **cd** até o mesmo
 - No **Git Bash** utilizar ***git init** 

###Configurando o Git (primeira vez) para atribuir autor
 - Utilize **git config --global user.email "email"**
 - Utilize **git config --global user.name "username"**

### Commitando um arquivo (commits dão significado às alterações)
 - Utilize **git add * **
 - Utilize **git commit -m "mensagem do commit"**

###Verificando status dos arquivos em um repositório remoto
 - Utilize **git status**
	 - untracked files - git não tem ciência
	 - unmodified files - arquivos não modificados no git
	 - modified files - arquivos modificados no git
	 - staged files - arquivos preparados (git add)
	 - commit volta arquivos para unmodified

###Atualizando arquivos que serão commitados
 - Utilize **git add nome do arquivo nome do diretório**
 - Utilize **git add * ** para todos
