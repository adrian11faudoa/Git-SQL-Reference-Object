Subject:

Git

git init

git status

README.md
This is a file you will see in many repos to describe what the repo is for

git add <*>

git commit -m "feat: add drop table reference"

git merge <branch_name>

git log --oneline (-x, x number of logs)
<<to see the most recent log
git log -1 

<<Delete a branch
git branch -d <branch_name>

<<Create and move to a branch
git checkout -b <branch_name>

git rebase <main / branch>

<<Stash your changes so you can add them to a different branch.
git stash. 

git stash list

git stash pop
git stash show -p

git reset HEAD~1 <--hard --soft>

git rebase --interactive HEAD~2
git rebase --interactive --root
>>nano: r (to reword a commit), d (delete a commit), s (squash use commit, but meld into previous commit)

git remote add origin <link>
git remote -v
git remote set-url <new_link>