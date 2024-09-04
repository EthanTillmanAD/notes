Git Fundamentals

git is a VCS (version control system) that can track files over time a history file can be found called .git like .gitignore it is hidden
inside .git you can find snapshots of everything changed when you use git commit


branching allows changes to be made before altering saved files until those files are ready to be merged back into main/master file

git wont track files unless you ask for them to be tracked (you can start tracking after running git init)
git init = creates .git file to save all changes/Starts tracking
git add (file name or -A) = starts the staging process/moves them from working directory to staging
git commit -m "message explaining what has been modified" takes the snapshot for .git directory/repository and commits/ gets them ready to be pushed to repository

git rm (file name) = removes file
git config --global = this can change config such as user.email and user.name 
git log = shows commit history of repository
git diff = shows differences between previous and modified files
git branch <branch-name> = create a new branch separate from main/master (using git branch -a lists branches)
git checkout <file name> = move between branches or create a new one and moves you into it
git merge <branch name> = this will merge the branch you identified into your working directory
git clone <link> <copy name> = copys a repository such as we did in the book
git remote <link> = this will connect you to a remote repository
git push (git push - u main/master) = this pushes all commited files to a remote repository
git pull = pulls from remote repository and merges changes
git fetch = is like git pull but doesn't merge changes
git revert <commit message> = makes a new commit that reverts changes (find commit message in git log)
git reset <--(soft, mixed, or hard)> <commit> = resets repository soft = only index but changes remain staged, mixed = index and working directory(unstaged), hard = resets all 
git help --<git command> = gives you information about that command such as git help --add
git --version = see what version of git you have
ls = list files in working directory (adding in -a will show everything including hidden)
cd = change directory
mkdir = make directory
pwq = print working directory
touch = makes a new file in directory
git status = checks the status of working directory(modified/unmodified)
git switch -c == git checkout -b (both change and make new branch)
:q = quits without changed
:wq = writes and quits
vi <file name> = views file :wq and :q are used here
git commit --amend = allows fixing mistakes without creating new commit