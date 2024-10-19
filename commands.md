Initialization and Setup
mkdir git-for-devops
Creates a new directory named git-for-devops.

cd git-for-devops/
Changes the current directory to git-for-devops.

git init
Initializes a new Git repository in the current directory.

git config --global user.name "[username]"
Sets the global username for all Git repositories.

git config --global user.email "[email]"
Sets the global email for all Git repositories.

Basic Operations
git branch
Lists all branches in the repository.

git status
Shows the current status of the working directory and staging area.

git add [file]
Adds the specified file(s) to the staging area.

git commit -m "[message]"
Commits the staged changes with a message describing the commit.

git log
Displays the commit history.
 

git restore [file]
Restores the specified file to the last committed state.

vim [file]
Edits the specified file using Vim.

cat "text" >> [file]
Appends the specified text to the file.

Branch Management
git checkout -b [branch name]
Creates a new branch and switches to it.

git switch [branch name]
Switches to the specified branch.

git checkout [branch name]
Switches to the specified branch.

Remote Operations
git remote -v
Displays all configured remote repositories.
Miscellaneous
git rm --cached [file]
Removes the specified file from the staging area but keeps it in the working directory.
