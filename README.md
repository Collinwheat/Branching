## Git Branching

### Basic Commands

* 'git init' - initialize local git repo
* 'git add filename' - stage 'filename' for commit
* 'git commit -m "message"' -commit to local repo with message
* 'git branch -m newName' -change name of current branch

### Information Commands
* 'git status' - show commit status of local repo
* 'git log' - show commit log
* 'git log -- oneline' - show commit log (compact formatting)
* 'git congif -l' - list repo configuration

### Branching Commands
* 'git branch' - list local branches
* 'git branch branchName' - create local branch 'branchName'
* 'git checkout branchName' - switch to branch 'branchName'

### Remote Commands
* 'git remote add origin repoUrl' -create alias for remote repo 'repoUrl'
* 'git push origin branchName' - push to remote branch 'branchName'
* 'git push -u origin branchName' - push to remote branch 'branchName' making it the default remote 
* ''