# Simple Git Tutorial

## Setting Up Git

1. **Install Git**:
   - Download and install Git from [git-scm.com](https://git-scm.com/).

2. **Configure Git**:
   ```sh
   git config --global user.name "Your Name"
   git config --global user.email "your.email@example.com"
   ```

## Basic Git Commands

### Initialize a Repository

1. **Create a new repository**:
   ```sh
   git init
   ```

2. **Clone an existing repository**:
   ```sh
   git clone <repository-url>
   ```

### Working with Changes

1. **Check the status of your repository**:
   ```sh
   git status
   ```

2. **Add changes to the staging area**:
   ```sh
   git add <file-name>
   # or add all changes
   git add .
   ```

3. **Commit changes**:
   ```sh
   git commit -m "Your commit message"
   ```

### Working with Branches

1. **Create a new branch**:
   ```sh
   git branch <branch-name>
   ```

2. **Switch to a branch**:
   ```sh
   git checkout <branch-name>
   ```

3. **Create and switch to a new branch**:
   ```sh
   git checkout -b <branch-name>
   ```

4. **Merge a branch into the current branch**:
   ```sh
   git merge <branch-name>
   ```

### Working with Remote Repositories

1. **Add a remote repository**:
   ```sh
   git remote add origin <repository-url>
   ```

2. **Push changes to a remote repository**:
   ```sh
   git push origin <branch-name>
   ```

3. **Pull changes from a remote repository**:
   ```sh
   git pull origin <branch-name>
   ```

### Additional Tips

- **View commit history**:
  ```sh
  git log
  ```

- **Undo changes in the working directory**:
  ```sh
  git checkout -- <file-name>
  ```

- **Reset the staging area**:
  ```sh
  git reset <file-name>
  ```