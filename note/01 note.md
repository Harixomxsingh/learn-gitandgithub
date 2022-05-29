# What is git and github

git is version control tool,

github is a platform a online website that allows us to store, host the git repositories.

# git initialize

- first go to terminal
- create a folder use _mkdir_ command
- type **git init**

that command will be initialize our .git folder

<hr>

when you create the .git folder , you can see with

- go to terminal
- type **ls -a**

<hr>

## Some git commands

- git status - see the status
- git log - where you can all commiting history

<hr>

## git add

git add it is a git command that tells ok now your file is tracking

```bash
git add .
```

## git commit -m ""

ok now !

once you add the file then you need to commit it so others see that which time or which date this file is changes and what the purpose of changing the file .

```bash
git commit -m "added chapter1.txt"
```

<hr>
now we know the basic git command how to add a file and how to commit,

so let's get more further

- open the .txt

```bash
vim chapter1.txt
```

and enter some value in the file

now you can hit **git status** to see the status

you can the see that the chapter 1 file is modified, so we need to say git and again track the change and commit what's we done with this file

```bash
git add .
```

```bash
git commit -m "add some value to chapter1 file"
```

<hr>

### removing changes from the stage

removing changes from the stage without commiting it

```bash
git resotre --staged file.txt
```

### removing commit

if you delete a file or commit something by mistake, you can un do the commit by using the "rest" command

```bash

git reset yourHashNo.(ajdfkjdfkadjfak)

```

- first go and type git log
- then select the hash no down the which you commit you need to undo

## git stash

git stash is a command that you gave some power to hide some file or hide some trackfile, and when every you want the trackfile you can backup

```bash
git stash
```

### git stash pop

git stash pop said that all the people in the back area come to the front

```bash
git stash pop
```

### git stash clear

if your stash (hide tracking file) is not use full you can clear it

```bash
git stash clear
```
