### Removing files tracked by git

[For detailed context, check out this StackOverFlow post](https://stackoverflow.com/questions/1274057/how-to-make-git-forget-about-a-file-that-was-tracked-but-is-now-in-gitignore)

#### Remove single file

`$ git rm --cached <file>`

#### Remove folder and children

`$ git rm -r --cached <folder>`
