Push local changes to exisiting empty remote

$ git init

Write your code (or if already written)

$ git add . 

$ git commit -m "<message>"

Push to GitHub, create new repo (NO README)

$ git remote add upstream <repo-url>

$ git push upstream master

IF accidentally created README:
$ git push -f upstream master // '-f' erases commit on remote