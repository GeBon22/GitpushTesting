    • feature branches sind temporäre branches, die für die Einführung eines Features neben dem Main branch herlaufen
    • die Änderungen im feature branch werden committed und von anderen reviewed (= „Pullrequest“)
    • nach review und stattgabe wird der feature branch final mit dem main branch gemerged

#usefull git commands:

- git init: create empty local repository
- git status: check status
- git add <Filename>: add filename to git
- git commit -m "Message" (i.e. Changes on xy) -> saves changes in repository
- git add . : add all changes
- git restore --staged <filename>: delete added but not committed changes
- git diff <filename>: shows changes made in the file
- git restore <filename>: deletes all uncommitted changes
- git remote add origin <git repository ssh>
- git push -u origin main
- git clone <github repository ssh>: clones repository that is not already on local drive ("first timer")
- git push (don't need to use git remote again)
- git log: shows git history with changes e.a.
- git switch -c <branchname>: creates new branch with <branchname>
- git switch <branchName>: switch between branches
- git pull: pulls changes that happend on the branches onto local drive (that should be done frequently on a daily basis if working on branches)
- git branch: shows all branches
  (- git checkout head-1 : jumps back to the last commit before HEAD)
- git config --global core.editor "nano" : changes default editor from vi to nano
- git remote -v : shows remote git
- git remote set-url origin <git URL ssh> : changes git origin (from 
https to ssh for example)

