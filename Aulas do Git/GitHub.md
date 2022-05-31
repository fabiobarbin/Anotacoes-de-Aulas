# Primeiros passos no GitHub/Git Bash

### Criando uma pasta

- Utilize `mkdir` seguido do nome do diretório que se deseja criar.
	- **Ex.**
		
			$ mkdir Anotacoes 			# para criar diretório com nome "Anotacoes".

### Alterando o diretório de trabalho

 - Utilize `cd` para mudar diretório
 	- `cd ..` - retorna para diretório anterior
 	- `cd + nome do diretório ` - avança para o diretório indicado

### Listando arquivos de um diretório
 - Utilize `ls` para listar os arquivos
	- Para listar arquivos ocultos utilizar a flag `-a`. 
		- **Ex:**
		 
		 		$ ls -a				# Lista arquivos ocultos como .git

### Criando um arquivo dentro de um diretório
 - Utilize `> + nome do arquivo.extensao` 
	 - **Ex.** 
	 	
			$ > GitHub.md 			# Para criar um arquivo markdown chamado "GitHub"
 - Utilize `echo > nome do arquivo`

### Movendo um arquivo entre diretórios
 - Utilize `mv + nome do arquivo + local do diretório`
	- **Ex.**
	
			$ mv mover.md Pasta/	# Move o arquivo mover para diretório chamado Pasta
 
### Iniciando um repositório Git em um diretório
 - Abrir **Git Bash** no diretório ou "navegar" utilizando `cd` até o mesmo
 - No **Git Bash** utilizar `git init` 

### Configurando o Git (primeira vez) para atribuir autor
 - Utilize `git config --global user.email "email"`
 - Utilize `git config --global user.name "username"`

### Verificando as configurações
 - Utilize `git config --list`

##Reconfigurando Git
 - Utilize `git config --global --unset user.email`
 - Utilize `git config --global --unset user.name`
 - Após unset, volte reconfigure o Git

### Commitando um arquivo (commits dão significado às alterações)
 - Utilize `git add * ` ou `git add .` para todos arquivos
 - Utilize `git commit -m "mensagem do commit"`

### Verificando status dos arquivos em um repositório remoto
 - Utilize `git status`
	 - untracked files - git não tem ciência
	 - unmodified files - arquivos não modificados no git
	 - modified files - arquivos modificados no git
	 - staged files - arquivos preparados (git add)
	 - commit volta arquivos para unmodified

### Atualizando arquivos que serão commitados
 - Utilize `git add + nome do arquivo + nome do diretório`
 - Utilize `git add * ` para todos

### Adicionando a origem de onde estão os arquivos locais
- Utilize `git remote add origin link do repositório`

### Listando origem do repositório remoto
 - Utilize `git remote -v`


### Empurrando arquivos para servidor remoto
 - Utilize `git push origin master`

### Puxando arquivos do servidor remoto (ajustando alterações)
 - Utilize `git pull origin master`

### Clonando repositórios
 - Utilize `git clone link do repositório`

