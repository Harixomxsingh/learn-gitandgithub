# How to contribute to other github projects?

## Fork (1st step)

What is fork?

you can not directly add or edit file on any project in github so you need to fork it mean when you hit fork on any project in your account the project's copy added, so the fork does that copy the hole project and added to your profile

- first you need to fork it(that's gone make a copy of this project to your project)

## Clone (2nd step)

second step is clone the fork project to your local machine using the <code> git clone url</code> command

## set upstream url (3ed step)

hit the command

```bash
git remote -v
```

you should see the origin push and pull url

so

we need to add the main project url, so do using the upstream, upstream mean the main project url, not your fork one because the fork one name is origin, so we need to set the main project url using the upstream command

```bash

git remote add upstream <url>

```

## create Branch (4th step)

never do commit on the main branch, it is not a good habit if your code have any bug then the users or the main branch also affect it

so you need to create a new branch and the do your work

```bash
git checkout -b Branchname

or

git branch Branchname

git checkout branchname
```

## create a pull request (5th step)

when ever your done is work , then we need to create a pull request to see change or see my code to main repository,

```bash

git push origin yourBranchName

```

then this will sent you a notification to your fork project and you need to compare and the you need to create a pull request to main repo

if your code is good enough and if the repo's founder some person see your code and if he or she agree with your code then he will merge to the main project and your code will be go to main file,

<hr>

one thing you notice the fork one not updated, because it is not fetch from the upstream.

# how to fetch manual from the cli

## checkout to master or main brach (1st step)

```bash
git checkout main or master
```

## upstream url in there or not (2nd step)

you need to see that you upstream url is set or not

```bash
git remote -v
```

if it not set go upper i tech there!

## fetch (3rd step)

```bash
//          all  all delete file
git fetch --all --prune
```

## reset (4rd step)

we need to reset this it mean that reset my main branch of my **origin** to my **upstream**

```bash

git reset --hard upstream/master

```

## push all those thing to origin master

```bash

git push origin master

```
