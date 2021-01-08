gitty
=====

Just by using gitty push you can save a lot of your efforts while pushing your code to github

How ?

While pushing your code to github, you need to init git then you need to add all your files to staging area then commit it add remote and then only you are ready to push your code.

But this all could be more easy 

$ gitty push -r https://github.com/Sangeetaaaa/gitty-gitcmd-automation.git -m "initial commit"


# Usage

<!-- usage -->
```sh-session
$ npm install -g gitty

$ gitty COMMAND
running command...

$ weight --help [COMMAND]
USAGE
...
```
<!-- usagestop -->

# Commands
<!-- commands -->
* [`gitty push`](#gitty-push)

## `gitty push`

gitty push will automatically push your code to github after adding it to the staging area, commiting it.

USAGE
  $ gitty push
  $ gitty push -r https://github.com/Sangeetaaaa/gitty-gitcmd-automation.git  -m "Intial Commit"

OPTIONS
  -m,  commit message
  -r,  add remote
  -h, --help         show CLI help

DESCRIPTION
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
