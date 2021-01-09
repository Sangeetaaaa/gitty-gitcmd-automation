gitty
=====

Just by using $ gitty push you can save a lot of your efforts while pushing your code to github

How ?

While pushing your code to github you need to initial git, then you probably need to add all your files to the staging area, commit it, add remote and then only you are ready to push your code.


This all can be done using only one command
![https://giphy.com/gifs/ufc-26FL5GGyV7SjcCJ8I](one)


$ gitty push -r https://github.com/Sangeetaaaa/gitty-gitcmd-automation.git -m "initial commit"

note: This will push your code to master branch


# Usage

<!-- usage -->
```sh-session
$ npm install -g gitty

$ gitty push 

$ gitty --help 
USAGE
...
```
<!-- usagestop -->

# Commands
<!-- commands -->
* [`gitty push`](#gitty-push)

## `gitty push`

gitty push will automatically push your code to github after adding it to the staging area, commiting it.

### USAGE
  $ gitty push
  $ gitty push -r https://github.com/Sangeetaaaa/gitty-gitcmd-automation.git  -m "Intial Commit"

### OPTIONS
  -m,  commit message
  -r,  add remote
  -h, --help         show CLI help

### DESCRIPTION
$ gitty push 

This command is the combination of 

git add ., 

git commit -m "" and 

git push -f origin master


$ gitty push -r https://github.com/Sangeetaaaa/gitty-gitcmd-automation.git  -m "Intial Commit"

This command is the combination of 

git init, 

git add ., 

git commit -m "", 

git remote add origin and 

git push -f origin master
