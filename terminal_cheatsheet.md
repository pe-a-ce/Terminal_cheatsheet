# Cheatsheet for terminal commands

## General 

| Syntax | Description |
| ----------- | ----------- |
| Current location  | pwd |
| List  | ls |
|List (_long_) | ls -l
|List (_all inc hidden items_| ls -a
|Change directory | cd directoryname
|Move up a level in directories| cd ..
|Return to root directory | cd


## Creating, Moving, Deleting Directories and Files

| Syntax | Description |
| ----------- | ----------- |
| New directory  | mkdir directoryname |
| New file | touch filename.extensiontype|
|Move a file| mv filename newlocation
|Move file to directory up one level (relative)| mv filename ..
|Move file to a specific location (absolute)| mv filename locationpath (i.e ~Users/peace...)
|Copy file| cp 
Rename a file| mv filename newfilename
Remove a file| rm filename
Remove a directory | rm -r directoryname


## Git commands 
| Syntax | Description |
| ----------- | ----------- |
| Start git commands | git init
|display the state of the repository and staging area| git status
|displays all of the commits in a repository's history| git log
|to add a specific file| git add filename
|to select all untracked files| git add .
|commit a change| git commit -m "commit text"
|push repo to github| git push origin main