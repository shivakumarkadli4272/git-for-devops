############################# GIT-Basic Commands##################################


# Git Basics
git init                            # Initialize a new Git repository.
git clone <repository>              # Clone an existing repository.
git status                          # Show the status of changes.
git add <file>                      # Stage changes for the next commit.
git commit -m "<message>"           # Commit staged changes with a message.
git push                            # Push changes to a remote repository.
git pull                            # Fetch and integrate changes from a remote repository.
git fetch                           # Download changes from a remote repository without merging.

# Branching
git branch                          # List branches.
git branch <branch-name>            # Create a new branch.
git checkout <branch-name>          # Switch to a branch.
git checkout -b <branch-name>       # Create and switch to a new branch.
git merge <branch-name>             # Merge a branch into the current branch.
git rebase <branch-name>            # Reapply commits on top of another base branch.

# Viewing Changes
git log                             # View commit history.
git diff                            # Show changes between commits, branches, or the working directory.
git show <commit>                   # Show details of a specific commit.

# Remote Repositories
git remote -v                       # List remote repositories.
git remote add <name> <url>         # Add a new remote repository.
git remote remove <name>            # Remove a remote repository.

# Undoing Changes
git reset <file>                    # Unstage a file.
git reset --hard                    # Reset the working directory and index.
git checkout -- <file>              # Discard changes in the working directory.
git revert <commit>                 # Create a new commit that undoes a specific commit.

# Stashing
git stash                           # Stash changes in the working directory.
git stash apply                     # Apply the most recent stash.
git stash pop                       # Apply the most recent stash and remove it from the stash list.

# Tagging
git tag                             # List tags.
git tag <tag-name>                  # Create a new tag.
git push origin <tag-name>          # Push a tag to a remote repository.

# Configurations
git config --global user.name "<name>"  # Set the user name.
git config --global user.email "<email>" # Set the user email.
git config --list                    # List all configuration settings.
