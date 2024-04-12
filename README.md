# LearningGit-3.2

# GitHub Authentication

GitHub provides several ways to authenticate, which are crucial for interacting with repositories in a secure manner. The methods available are:

- **Username and Password**: The simplest form of authentication, but not the most secure. It's recommended to use this method only if necessary.

- **SSH Keys**: A secure method that allows you to interact with your repository without needing to enter your credentials every time. SSH keys need to be generated and then added to your GitHub account.

- **Personal Access Tokens (PATs)**: These are similar to using a password, but more secure. PATs can be easily revoked and can have specific permissions.

# GitHub Commands

Here are 15 commonly used GitHub commands and their usage:

1. `git init`: Initializes a new Git repository.
2. `git add`: Adds a file to the staging area.
3. `git commit`: Commits the file to the repository.
4. `git status`: Shows the status of changes as untracked, modified, or staged.
5. `git pull`: Fetches and merges changes on the remote server to your working directory.
6. `git push`: Pushes your changes to the remote repository.
7. `git clone`: Clones a repository into a new directory.
8. `git branch`: Lists, creates, or deletes branches.
9. `git checkout`: Switches branches or restores working tree files.
10. `git merge`: Merges one or more branches into your current branch.
11. `git remote`: Manages set of tracked repositories.
12. `git fetch`: Downloads objects and refs from another repository.
13. `git tag`: Creates, lists, deletes or verifies a tag object signed with GPG.
14. `git revert`: Reverts some existing commits.
15. `git reset`: Resets your current HEAD to the specified state.

# Most Used GitHub Commands

The four GitHub commands that are most commonly used in real projects are:

1. `git add`: This command is used frequently as it stages the changes you've made in the project. Without this command, your changes won't be included in the commit.

2. `git commit`: This command is essential for saving the changes you've made. It's like setting a checkpoint in the project that you can revert back to if needed.

3. `git pull`: This command is used to update your local repository with the latest changes from the remote repository. It's crucial when working in a team to ensure everyone has the latest version of the project.

4. `git push`: This command sends the committed changes to the remote repository. It's necessary to ensure that your changes are available to everyone else working on the project.