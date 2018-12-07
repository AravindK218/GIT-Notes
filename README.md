# GIT-Notes

#1 git init -->>  Create empty Git repo in specified directory. Run with no arguments to initialize the current directory as a git repository.

Example: git init repo1

#2 git clone -->>Clone repo located at <repo> onto local machine. Original repo can be located on the local filesystem or on a remote machine via HTTP or SSH

Example: git clone reponame

#3 git config  user.name <name> -->> Define author name to be used for all commits in current repo. Devs commonly use --global flag to set config options for current user.

Example: git config --global user.name username

#4 git diff -->>  Show unstaged changes between your index and working directory.

Example: git diff HEAD is between repo and working tree.
         git diff
         git diff --staged repository and staging index
         
#5 git log -->> Display the entire commit history using the default format. For customization see additional options.

#6 git status

#7 git revert  <commit> -->> Create new commit that undoes all of the changes made in <commit>, then apply it to the current branch.


#8 git reset <file>  -->>  Remove <file> from the staging area, but leave the working directory unchanged. This unstages a file without overwriting any changes.

#9 git clean -n  -->> Shows which files would be removed from working directory. Use the -f flag in place of the -n flag to execute the clean.
(Remove untracked files from the working tree) ( -n <==> --dry-run )
