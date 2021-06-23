### Create new repo (GitHub) - NO README, license, .gitignore

In Terminal, cd into local repo

`$ git init`

`$ git add .` // stage all files for commit

`$ git commit -m "<message>"` // commits tracked changes to push

In GitHub, copy URL

`$ git remote add origin <remote repo URL>` // sets the new remote

`$ git remote -v` // verifies the new remote URL

`$ git push -u origin master` // pushes the changes in your local repository up to the remote repository you specified as the origin
