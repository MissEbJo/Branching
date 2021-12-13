## Git Cheat Sheet


### Basic Commands

* 'git init' - Initialize local Git repository
* 'git add ' - Add all files in and under current directory to git index, staging them for commit
* 'git commit -m "Message"' - commit changes to local repo with commit message "Message"

###Information Commands

* 'git status' - display current status of local working directory/repository
* 'git log' - list commit history
*'git log --oneline' - list commit history, compact format


### Branching Commands

* `git branch` -list local git branches
* `git branch newBranch` - create local branch
`newBranch`
* `git checkout newBranch` - check out local branch `newBranch`

* 'git branch -M otherBranch' - Rename current brach to 'otherBranch'


### Remote Commands
* `git remote add origin remoteUrl` - add alias "origin " for remote repositoryURL "remoteUrl"
* `git push origin main` - push locally-commited changes to `main` branch on remote repository
* `git push -u origin main` - Same, setting "origin main " as default for subsequent `git push`
