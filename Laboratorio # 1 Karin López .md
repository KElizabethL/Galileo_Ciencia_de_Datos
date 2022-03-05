# Universidad Galileo
**Karin Elizabeth López Padilla** 

*Carne: 21002935*


## GIT

Git es un software de control de versiones diseñado por Linus Torvalds, pensando en la eficiencia, la confiabilidad y compatibilidad del mantenimiento de versiones de aplicaciones cuando estas tienen un gran número de archivos de código fuente. 

### Directorio de trabajo 
El directorio de Git es donde se almacenan los metadatos y la base de datos de objetos para tu proyecto. Es la parte más importante de Git, y es lo que se copia cuando clonas un repositorio desde otra computadora. El directorio de trabajo es una copia de una versión del proyecto.

1. Working directory

2. Staging area

3. Repository

![Directorio de trabajo](https://www.jose-aguilar.com/blog/wp-content/uploads/2019/07/ciclo-de-vida-git.png)

### Principales comandos 
|Codigo                | Descripción                                              |
|----------------------| -------------------------------------------------------- |
|git init              |Crea un repositorio Git vacío o reinicializa uno existente|
|gt status             |muestra el estado del directorio de trabajo               |
|git clone <url>       |Clonamos el repositorio de github o bitbucket             |
|git add .             |Añadimos todos los archivos para el commi                 |
|git commit -m "     " |Hacemos el primer commit                                  |
|git push origin master|subimos al repositorio                                    | 

    
## ¡Un poco de codigo!

`
$ pwd

/c/Users/Klopez/Desktop/Laboratorio1

$ ls
    
'Laboratorio1.md'


$ git init

Initialized empty Git repository in C:/Users/Klopez/Desktop/Laboratorio1/.git/


$ git status
    
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        "Laboratorio # 1 Karin L\303\263pez .md"

nothing added to commit but untracked files present (use "git add" to track)

No commits yet

    
$ git add Laboratorio1.md

warning: LF will be replaced by CRLF in Laboratorio1.md.
The file will have its original line endings in your working directory

$ git status
    
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   Laboratorio1.md


$ git commit

Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.



$  git config --global user.email "karin.lopez@galileo.edu"


$ git config --global user.name "KarinL"


$ git commit
    
[master (root-commit) 6fd00dc] Mi primer commit
 1 file changed, 46 insertions(+)
 create mode 100644 Laboratorio1.md


$ git log

commit 6fd00dc9bd92597b1bafabacfe325e2e648ef0d1 (HEAD -> master)
Author: KarinL <karin.lopez@galileo.edu>
Date:   Sat Mar 5 15:33:58 2022 -0600

    Mi primer commit


$ git status
    
On branch master
nothing to commit, working tree clean
    
$ git remote add origin https://github.com/KElizabethL/Galileo_Ciencia_de_Datos


$ git push -u origin master
To https://github.com/KElizabethL/Galileo_Ciencia_de_Datos`


    
    
### Material de ayuda
    
 *Comandos de Git(https://education.github.com/git-cheat-sheet-education.pdf)
 * [Introduccion a Git](https://www.youtube.com/watch?v=jGehuhFhtnE)
 * [Video de Git y Github](https://www.youtube.com/watch?v=HiXLkL42tMU)

    


