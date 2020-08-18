Basic CLI Commands
=================

| Command  | Description | Example |
| ------------- | ------------- | ------------- |
| `mkdir` | create a folder | mkdir <new-folder>
| `touch` | create a file| touch <new-file>
| `cd` | change directory (aka folder) | cd <new-folder>
| `~` | root directory | cd ~
| `..` | parent directory | cd ..
| `ls` | list file and directory names | ls <folder-name>
| `cmd + l` | clear terminal | n/a

Useful GIT Commands
=================

| Command  | Description | Example |
| ------------- | ------------- | ------------- |
| `git init` | create a hidden .git file | note: `cmd + shift + .` to see hidden files
| `git remote add <name> <link>` | add remote links (upstream, partners, etc.) | `git remote add` upstream <Org GitHub Link>
| `git remote -v` | list remote links (v for verbose) | n/a
| `git pull <name> <branch>` | pull file(s) from remote link's branch | `git pull partner master`
| `git push <name> <branch>` | push file(s) to remote link's branch (need auth access) | `git push origin master`
| `git status` | see status of staging area | n/a  
| `git add <name>` | add files to staging area | `git add index.js`
| `git add .` | add all modified files to staging area | n/a
| `touch .gitignore` | create hidden .gitignore file (add untracked files) | n/a
| `git commit -m "<commit message>"` | commit files in staging area | `git commit -m "button to open directory is functioning"`
| `git log` | list of previous commits | n/a
