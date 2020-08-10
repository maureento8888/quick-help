Remove .DS_Store from Git repo

Remove existing files from repo
\$ find . -name .DS_Store -print0 | xargs -0 git rm -f --ignore-unmatch

Add to gitignore:

.DS_Store

Or:
\$ echo .DS_Store >> .gitignore

Add and Commit:
$ git add .gitignore
$ git commit -m ".DS_Store removed"
