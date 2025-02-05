# 2025-02-Git
Redo 01-09 &amp; 01-16 Lectures

- `git clone`: does a one-time download from github to your local computer
    * make sure the directory you are cloning is not already a git repo

- `git status`: tells you what's happening in your current git repository git add <FILE>: adds to the staging area

- `git commit -m "MESSAGE"`: creates a commit (aka snapshot) with the changes in the staging area, with the message you supplied

- `git push <where> <what>`: pushes changes from local machine to remote (where) using the branch (what)

- `git pull <where> <what>`: brings changes from the remote to the local machine

git branches

- `git branch`: lists all your current branches. The one you are on will have a * and be colored green

- `git branch <NAME>`: this will create a branch where HEAD is

- `git switch <NAME>`: moves over to the branch

- `git log --oneline`: see where you are

- `git push origin b1`: pushes the b1 branch to the remote

- `git pull origin b1`: pull the b1 branch from the remote

- `git switch -c <NAME>`: will create a new branch and switch to it