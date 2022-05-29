# Github

we can create repo on github and then first we need to add the local file to remote url

```bash
git remote add origin url.com
```

once you add your file to remote

```bash
git remote -v
```

then you need to push all the changes to remote branch

```bash
git push origin master
```

# Github (git brach)

you should always create a new branch and make changes with it , don't commit or push your code directly to the main or master branch because maybe your code have some bug so the bug also go to master or production

so how to create a brach

```bash
git branch branchName(test)
```

or

```bash
git checkout -b branchName
```

## Github fork

what is github fork and why we use the github fork?

you can not directly add or edit file on any project in github so you need to fork it mean when you hit fork on any project in your account the project's copy added, so the fork does that copy the hole project and added to your profile

## git clone

git clone mean clone a github project

```bash
git clone url
```

so, when ever you fork any project that you want to contribute , so first step fork and then second step is clone the project

# origin

you may ask what is origin?

so origin the name of you url origin represent of you github url, you can change your url name and set to what every you want but by **tradition** _origin_ the url name

# upstream

what is upstream?

upstream is - from where you have form the project (mean - project or repository main url), that is know as upstream url

```bash

git remote add upstream <url>

```

and then

```bash

git remote -v // that show your url name and where the url and name linked

```
