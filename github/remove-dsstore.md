### Remove .DS_Store from Git repo

#### Remove existing files from repo

`$ find . -name <file name> -print0 | xargs -0 git rm -f --ignore-unmatch`

#### Add to gitignore:

`<file name>`

##### Or:

`$ echo <file name> >> .gitignore`

#### Add and Commit:

`$ git add .gitignore`
`$ git commit -m "<message>"`
