# Create repositories

A new repository can either be created locally, or an existing repository can be cloned. When a repository was initialized locally, you have to push it to GitHub afterwards.

`git init` 

The git init command turns an existing directory into a new Git repository inside the folder you are running this command. After using the git init command, link the local repository to an empty GitHub repository using the following command:

`git remote add origin [url]`

Specifies the remote repository for your local repository. The url points to a repository on GitHub.

`git clone [url]`

Clone (download) a repository that already exists on GitHub, including all of the files, branches, and commits

# The .gitignore file

Sometimes it may be a good idea to exclude files from being tracked with Git. This is typically done in a special file named .gitignore. You can find helpful templates for .gitignore files at github.com/github/gitignore.

# Synchronize changes
Synchronize your local repository with the remote repository on GitHub.com

`git fetch`

Downloads all history from the remote tracking branches

`git merge`

Combines remote tracking branches into current local branch

`git push`

Uploads all local branch commits to GitHub

`git pull`

Updates your current local working branch with all new commits from the corresponding remote branch on GitHub. git pull is a combination of git fetch and git merge

# Work withh Branches

To create a new branch, use this command.

`git switch -c {BRANCH-NAME}`

Once you are ready, push the branch to GitHub and create a PR
