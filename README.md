git clone <url> -- to clone remote repository into local machine
tocuh README.MD -- to create a new file

git add README.md -- to add new file

git comit -m "comment"

git push -- this push chagnes to remote repository

git commit -am "comment" -- '-am' will add and commit files

git pull --whatever on the server to download them in my computer.

# git global configuraiton settings

git config --global -l #to view
git config pull.rebase false # merge
git config pull.rebase true # rebase
git config pull.ff only # fast-forward only

#to remove a setting from global setting
git config --global --unset pull.ff

git reset --hard <commit>
git reset --hard origin/master

#branching

1. git branch
2. git checkout
3. git merge

git checkout -b <feature name>

#making same chagnes
