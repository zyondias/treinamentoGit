## O que é git
1. Explicar que no SVN o seu repositório é o remoto apenas<br />
_No git você faz cópias locais de todo o seu repositório, há vários backups_
2. Slide de apoio<br />
``http://pt.slideshare.net/dist_bp/git-23107813``


## Como instalar?
**verificar como instalar no windows**

## Servidores Remotos

1. mostrar gitlab<br />
``http://git.buscapecompany.com``
2. mostrar Stash<br />
``https://www.atlassian.com/software/stash``<br />
``https://www.atlassian.com/git/tutorials``
3. mostrar github<br />
``http://github.com``


## Configurações

####configurar quem é você

- pelo terminal

			git config --global user.email "thiago.freitas@buscapecompany.com"

			git config --global user.name "THIAGO SANTOS DE FREITAS"

- pelo eclipse

			preference -> team -> git -> configuration

####configurar sua conexão com o servidor

- configuração é feita por ssh
- no git bash rodar ``ssh-keygen -t rsa``
- capturar chave pública
- adicionar na sua ferramenta git

``https://help.github.com/articles/generating-ssh-keys/#platform-windows``

## Criar repositório
1. Pelo eclipse 
``Team - share projects -> git -> (use or create repository in parent folder)``
2. Pelo terminal 
``git init``


## Commits
####Commits locais
- Commit local
- Commit com ammend
- Historico
- Commit local por comando

			git add introducao.md
			git commit -m ""
	
####Conectando com repositório remoto

- Mostrar como criar repositório no gitlab
- Criar repositório no github treinamentoGitProvisorio

- Configurar pelo eclipse

			Team -> Remote -> Push -> marcar para fazer o force
			Subir arquivos para o servidor
			Mostrar que não há configurações de repositório remoto feita
	
- Configurar pela linha de comando
	
			git remote add origin https://github.com/tsfreitas/treinamentoGitProv.git
			fazer push pelo eclipse
			git push -u origin master

####Fazendo commit local com conexão remota syncada
			Faz commit e commit e push

## Clone
1. No eclipse<br />
``Import -> Projects from Git``
2. por linha de comando<br />
``Cria pasta``<br />
``git clone <URL>``
	
	
----	
#BRANCHES

#MERGES
##Automático
##Conflito

#REBASE

#GITIGNORE

#MARKDOWN
##README.md

#gitlab
#github
	
