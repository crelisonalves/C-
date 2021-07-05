Arquivo do tipo MarkDown - estilo HTML https://docs.pipz.com/central-de-ajuda/learning-center/guia-basico-de-markdown#open

# Git | GitHub
 > O Git é um sistema de versionamneto de código de forma colaborativa. O GitHub é uma plataforma de armazenamanto de código na nuvem.
 > https://git-scm.com/ : para instalar o GIT
 > https://github.com/  : para armazenar na nuvem seus repositórios
 > https://web.digitalinnovation.one/course/introducao-ao-git-e-ao-github/ curso de Git/GitHub no Digitasl Innovation One

# Comandos de navegação de diretórios no Windows

Comando  | Ação
:--------|:--------:
cmd      | invoca o terminal no Windows
cd    | mudar de diretório
dir   | listar diretórios e arquivos
cls   | limpar a tela - clean screen
TAB   | aucompleta o nome dos diretórios e arquivos
mkdir | criar diretórios
del   | apagar arquivos
rmdir | remover diretórios
echo  |  direciona o fluxo de dados         
~ | echo Olá mundo > texto.txt        
~ | direciona a cadeira de caracteres para o arquivo texto.txt


> Instale o windows subsystem for linux no Windows 10, siga as instruções do tutorial a seguir [ https://youtu.be/muFHmfC9PVU ]

>Depois de instalado o GIT no Windows, abra o Explorador de Arquivos e navegue até a página que vovê quer trabalhar e com o botão direito do mouse clik na pasta que você quer >trabalhar e seleciona a opção Git Bash Here.


# Comoandos de navegaçção de diretórios no Linux 
Comando | Ação
:-------|:-------:
cd    | mudar de diretório
ls    | listar diretórios e arquivos
clear | limpar a tela
mkdir | criar diretórios
rm    | apagar diretórios rm -rf nomeDoDiretório [ r : recursivamnmete, f : força para que tudo ocorra conforme o desejado ]
rf    | remover diretórios

# Comandos para manipular repositório e código no Git/GitHub

Comando | Ação
:------| :-----:
git init   | iniciar o git
git add    | adicionar arquivos
git commit | comitar o git
git config --global user.email "crelisonalves@gmail.com"  | configurtar o e-mail do autor
git config --global user.name Crelison                    | configura o nome do autor
git add *                                                 | inclui todos os arquivos e diretórios no repositório da pasta atual
git commit -m "commit inicial"                            | inicializa o commit
git status                                                | informa o status do Git
git config --list                                         | lista os dados do usuário, digit q para sair 
git remote add origin link-GitHub                         | gravar endereço do link em origin https://github.com/crelisonalves/Arduino.git

~~~Git
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/crelisonalves/teste.git
git push -u origin main
~~~


