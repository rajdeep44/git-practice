Practice repository
Commands for git

- git init
- git status
- git add
- git commit
- git log

-i to enter inster mode
esc - :wq! - enter 
git commit -m "message"

git checkout   checksout the branch

git remote add <remote> <url>: Add a new <remote> at <url>
git remote -v:   lists the remote repositories
git push -u <remote> <branch>:   Push <branch> to <remote> and set default upstream for <branch>
git fetch:  Fetch changes from remote repo 
git pull: fetch and then merge
git fetch + git merge = git pull

- git merge   the merge changes from one repository into another

- merging means to bring changes from one repository into another repository

- fast forward merge happens when the target was branched from the current one and there are no new changesto the current branch since then

- automatic merge happens when the two histories have diverged but git is able to reconsile them into one set og changes. This creates a new commit on the current branch

- git push   psuhes the commit changes from local repo to remote repo
