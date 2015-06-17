## O que é git

1. Explicar que no SVN o seu repositório é o remoto apenas<br />
    *No git você faz cópias locais de todo o seu repositório, há vários backups*
2. Slide de apoio<br />
    *http://pt.slideshare.net/dist**_bp/git-23107813*

## Como instalar?

**verificar como instalar no windows**

## Servidores Remotos

1. mostrar gitlab<br />
    *http://git.buscapecompany.com*
2. mostrar Stash<br />
    *https://www.atlassian.com/software/stash*
    *https://www.atlassian.com/git/tutorials*
3. mostrar github<br />
    *http://github.com*

## Configurações

1. configurar quem é você
2. pelo terminal

     	git config --global user.email "thiago.freitas@buscapecompany.com"
        git config --global user.name "THIAGO SANTOS DE FREITAS"

1.2) pelo eclipse
		preference -> team -> git -> configuration

2) configurar sua conexão com o servidor
	configuração é feita por ssh
	no git bash rodar ssh-keygen -t rsa
	capturar chave pública
	adicionar na sua ferramenta git
https://help.github.com/articles/generating-ssh-keys/#platform-windows

* criar repositório
    1) Pelo eclipse: 
    	Team - share projects -> git -> (use or create repository in parent folder)
    2) Pelo terminal 
    	git init

* commits
    1) Commits locais
    	Criar pasta "capitulo 1"
    	Criar arquivo introducao.md
    	Copiar exemplos
    2) Commit local por comando
    	git add introducao.md
    	git commit -m ""
    3) Conectando com repositório remoto
    	Mostrar como criar repositório no gitlab
    	https://git.buscapecompany.com/
    	Criar repositório no github treinamentoGitProvisorio
    3.1) Configurar pelo eclipse
    	Team -> Remote -> Push -> marcar para fazer o force
    	Subir arquivos para o servidor
    	Mostrar que não há configurações de repositório remoto feita
    3.2) Configurar pela linha de comando
    	git remote add origin https://github.com/tsfreitas/treinamentoGitProv.git
    	fazer push pelo eclipse
    	git push origin master
    4) Fazendo commit local com conexão remota syncada
    	Faz commit e commit e push

* Clone
    1) No eclipse
    	Import -> Projects from Git	

====BRANCHES

====MERGES
=======Automático
=======Conflito

====REBASE

====GITIGNORE

====MARKDOWN
=======README.md

=====gitlab
=====github

