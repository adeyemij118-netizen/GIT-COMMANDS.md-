## GIT COMMANDS 

 1. git init

    What it does `git init` initializes a new Git repository in the current directory. It creates a hidden `.git` directory where Git stores information about the repository, including its history and configuration.
    Example ```bash mkdir my-project cd my-project git init ``` 


  2. git status
 
     what it does git status shows the current state of your Git repository. It tells you which files have been modified, which files are untracked, and which files have been staged for a commit. ### Example ```bash git status ```

 3. git add
    what it does `git add` adds changes to the staging area. ### Example To add a specific file: ```bash git add README.md ``` To add all changed files: ```bash git add .

4. git commit
 
     `git commit` saves the staged changes to the Git repository's history. The -m option allows you to provide a message describing the changes it does.Example ```bash git commit -m "Add project README" ```

5. git push

      `git push` The git push command is used to upload your local repository commits to a remote repository.Example ```bash git push origin main```

6. git clone

   `git clone` git clone is used to download an existing remote repository onto your local computer.Example ```bash git clone https://github.com my-custom-folder```

 7. git branch

    `git branch` git branch command is used to create, list, rename, and delete branches within your repository.Example ```bash git branch```

8. git merge 

   `git merge` git merge command is used to combine the commit history and changes from one branch into another.Example ```bash git merge feature-login```

