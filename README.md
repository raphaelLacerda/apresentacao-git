# Apresentação GIT

> *"...distributed is the new centralized..."*
 

![Alt text](img/tweet-08-2014.png "Todo começo é triste")

## Walkthrough
* O que é?
* Rede social
* Hello world
* Repositórios locais e remotos
* Trabalhando com branches
* Trunk base x Feature Branch
* Pull Request

## "This thing called GIT"

* Segundo [**Linus Torvalds**](https://www.ted.com/talks/linus_torvalds_the_mind_behind_linux?language=en)

* [TOP frases do Linus em discussões](http://www.attendly.com/linux-founder-linus-torvalds-delivers-a-smackdown-like-no-other/)

![Alt text](img/linus2.jpg "You've gotta learn it")

> *".. Take Concurrent Versions System (CVS) as an example of what not to do; if in doubt, make the exact opposite decision ... "*

#### em outras palavras...

> *".. GIT is my second big project, which was only created for me to mantain my first big project... "* 

### "This is Hell"
![Alt text](img/git-hell.png "hell")

### (pequeno parênteses)
![Alt text](img/nerdtech.png "NerdTech")


## Rede Social
![Alt text](img/Github2.png "Seu time")
![Alt text](img/gitlab.png "Seu time")
![Alt text](img/bitbucket.png "Seu time")

## Hello world  

* clone
* add
    * untracked
    * staged -> rastreado mas não gravado
	* separando seus commits

![Alt text](img/stage.png "Área de Stage") 

* commit
    * -am
* push
* pull
* checkout

![Alt text](img/comandos.png "Seu time")

## Local x remotos

* origin
* head
* branch 
    * -a
    * -v
* remote -v
* reset --hard --soft

![Alt text](img/remote.png "Finalmente eu venci")

### múltiplos Repositórios

![Alt text](img/remotes2.png "Finalmente eu venci")

## Trabalhando com branches

* git checkout -b nova
* merge
* rebase
* Ferramentas - [meld merge](http://meldmerge.org/)

### branch fácil - "the merge option"
* git checkout iss53
* git merge master

![Alt text](img/branch-facil.png "branch fácil")

### "rebase is better"

* git checkout iss53
* git rebase master

![Alt text](img/rebase-facil.png "branch fácil")

> *"The major benefit of rebasing is that you get a much cleaner project history. First, it eliminates the unnecessary merge commits required by git merge."*

#

> *"Now, to the question of whether merging or rebasing is better: hopefully you’ll see that it’s not that simple. Git is a powerful tool, and allows you to do many things to and with your history, but every team and every project is different. Now that you know how both of these things work, it’s up to you to decide which one is best for your particular situation."*


### branch hell

![Alt text](img/branch-hell.jpg "branch fácil")


## Trunk X Feature

### 
![Alt text](img/gitflow.gif "Como eu trabalho")

### Trunk com **Feature toogle**

![Alt text](img/discussao-twitter.png "Finalmente eu venci")

[Acompanhe aqui](https://twitter.com/lacerdaph/status/755898667308048384) essa discussão!!



## BUT... "Who is the boss?"

![Alt text](img/paulo-tweet.png "The boss!")

## Outros comandos

* log
    * --stat
* show
* diff
* gitk

![http://stackoverflow.com/questions/24907140/git-returns-http-error-407-from-proxy-after-connect](img/equipe.jpg "Seu time")


# FIM
![Alt text](img/tweet-11-2015.png "Finalmente eu venci")



## Links interessantes

* Comandos [git](https://medium.freecodecamp.com/git-cheat-sheet-and-best-practices-c6ce5321f52#.1oxi5pmms).
* Meu [gist](https://gist.github.com/raphaelLacerda/687db0162a610f63d13ae899ec680518)

![Alt text](img/git-casa-codigo.png "Finalmente eu venci")