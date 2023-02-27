### create an empty catalogue ###

```
$ mkdir learngit
$ cd learngit
```
### turn the catalogue to managabel git ###

```
$ git init
```
then you get an empty repository

### add file to repository ###
after edit a file --readme.txt for example under tht catalogue *learngit*.
```
$ git add readme.txt
```

### commit file to repository ###
```
 git commit -m "wrote a readme file"
```
`-m` is followed by your declaration on this commit.

### check file status ###
```
$ git status
```
you will know if the file has been changed.

### to see what has been changed ###

```
$ git diff
```
then git will show the difference between this version and the last version.

## always remember: before `git commit` do `git status` to check the status ##

### if you want to check history version ###
```
$ git log
```
and if you want git print less information
```
$ git log --pretty=oneline
```
### if you want to back to n.th history version ###

```
$ git reset --hard HEAD~n
```
and when you want to go back to any version
```
$ git reset --hard <type your version number here>
```
for example
`$ git reset --hard 7b488` 
dont need to type the full number.

### if you want to check your cmd history ###
`$ git reflog`
then you have every command you had made.

`$ git checkout`用版本库中的内容替换工作区的内容