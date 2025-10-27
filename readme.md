Basic git commands
=================

**Initialize a repository**
```sh
$ git init
```

**Show the status of the working directory**
```sh
$ git status
```

**Add a file to the staging area**
```sh
$ git add <file>
```

**Commit changes**
```sh
$ git commit -m "Message"
```

**Show the commit history**
```sh
$ git log
```

**Edit the last commit**
```sh
$ git commit --amend
```

**Create a new branch**
```sh
$ git checkout -b <branch>
```

**Change the name of a branch**
```sh
$ git branch -m <new-name>
```

**Switch to a branch**
```sh
$ git checkout <branch>
```

**Add remote repository**
```sh
$ git remote add origin <repository-url>
```

**Clone a repository**
```sh
$ git clone <repository-url>
```

**Push changes to a remote repository**
```sh
$ git push origin <branch>
```

**Pull changes from a remote repository**
```sh
$ git pull origin <branch>
```

**Rebase changes**
```sh
$ git rebase <branch>
```

**CHERRY-PICK changes**
```sh
$ git cherry-pick <commit>
```

**Commit change the last commit**
```sh
$ git commit --amend --no-edit
```

**Reset changes to a specific commit**
```sh
$ git reset --hard <commit>
```

**Reset soft changes to a specific commit**
```sh
$ git reset --soft <commit>
```

**Show the changes in the working directory**
```sh
$ git diff
```

**Show the changes between two commits**
```sh
$ git diff <commit> <commit>
```

**Show the changes in a file**
```sh
$ git diff <file>
```

**Show the changes in a file between two commits**
```sh
$ git diff <commit> <commit> <file>
```