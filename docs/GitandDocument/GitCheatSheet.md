## Git CheatSheet for DevOps Engineers

### Basic Commands

### Initial Setup
- **Configure Git with your name and email**:
  ```bash
  git config --global user.name "Your Name"
  git config --global user.email "your.email@example.com"

#### Repository Management
- **Clone a repository:**  git clone https://github.com/user/repo.git

- **Initialize a new repository:**  git init

#### Branching
- **Create a new branch:** git branch new-branch

- **Switch to a branch:**  git checkout new-branch

- **Create and switch to a new branch:**  git checkout -b new-branch

#### Staging and Committing

- **Stage changes:**  git add <file>

- **Stage all changes:**  git add .

- **Commit changes:**  git commit -m "Your commit message"

#### Pushing and Pulling

- **Push changes to remote repository:**  git push origin branch-name

- **Pull changes from remote repository:**  git pull origin branch-name

### Advanced Commands

#### Branch Management
- **List all branches:**   git branch -a

- **Delete a branch:** git branch -d branch-name

#### Merging and Rebasing
- **Merge a branch into current branch:** git merge branch-name

- **Rebase current branch onto another branch:**   git rebase branch-name
  
#### Undoing Changes
- **Unstage a file:** git reset HEAD <file>

- **Discard changes in a file:** git checkout -- <file>

#### Viewing History
- **View commit history:** git log

- **View a file's history:**  git log -p <file>


### Collaboration

#### Stashing
- **Stash changes:**  git stash

- **Apply stashed changes:**  git stash apply

#### Remote Repositories
- **Add a remote repository:**   git remote add origin https://github.com/user/repo.git

- **List remote repositories:**  git remote -v

#### Tags
- **Create a new tag:**  git tag v1.0.0

- **Push tags to remote repository:** git push origin --tags
  
### Common Workflows

### Feature Branch Workflow
1. - **Create a new branch for your feature:** git checkout -b feature-branch

2. - **Make changes and commit:**
git add .
git commit -m "Add new feature"

3. - **Push the feature branch to remote:**  git push origin feature-branch

### Additional Resources
- [Git Documentation](https://git-scm.com/doc)
- [Pro Git Book](https://git-scm.com/book/en/v2)



This cheat sheet covers the essential Git commands and workflows for DevOps engineers, helping to streamline version control and deployment processes.
