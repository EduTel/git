# GIT
### comands
* git version
* git help
* git help [comand]
### iniciar
* git init
* status
    git status  
    git status -s -b  
* Agregar
    git add .  
    git add -A  
    git add -all  
    git add \<lista de archivos>  
    git add *.XML (directorio actual)  
    git add "*.XML"  
    git add css/  
    git add pdf/*.pdf  
* commit
    git commmit -m "start_git"  
    git commmit -am "start_git"  
    git commit --amend -m "ne name commit"  
* ver historial de cambios  
    git log  
    git log --oneline  
    git log --oneline --decorate --all --graph  
### git config
* Ver configuracion global  
    git config --list  
    git config --global -e  
    git config --global -l  
* configuracion global  
    git config --global user.name "name"  
    git config --global user.email  "mail"  
    git config --global core.editor "[ruta]"  
    git config core.autocrlf true  
* Alias  
    git config --global alias.lg "log --oneline --decorate --all --graph"  
    git config --global alias.st "status -s -b"  
### clone  
* git clone https://github.com/rabbitvcs/rabbitvcs.git  
### remote  
* git remote -v
* git remote show origin
##push  
* git push origin master  
### diff  
* git diff  
* git diff --staged  
### reset
* volver a un commit anterior
    git reset HEAD <commit name>  
    git reset --soft HEAD^  
### helps
* git checkout -- .  
* git checkout -- \<file name>  
## LINKS
https://git-scm.com/book/es/v1/Empezando-Configurando-Git-por-primera-vez  
https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup  
https://git-scm.com/book/en/v2/Git-Basics-Git-Aliases  
