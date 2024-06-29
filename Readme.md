## check git in cmd
- `git --version` check version of git

## list of config
- `git config --list` to get list of git

## To initinalize repositiry

- `git init` that help to inititilize repository and create .git folder where implement logics

## To delete or Remove init
 - `rm -rf .git` that help to remove git init

## To see Status
 - `git status` to view your status and data nad file changes 


## To track file
- `git add .` to track all files
- `git add filenam.txt` for add file and track

## To untrack all files
- `git rm -rf . ` that helps to untrack all files
- `git rm --cached filename.txt`  to untrack file   


## commit message before push

- `git commit -m "your message" ` always commit message before push

## quit vim editor
- press `esc` & press `colom :` & press `wq`
- `:wq`

## git restore give last commited 
- `git restore filename.txt` for remove all files from stagging to commited . use when your code pices is dirty 
- `git restore` restore all files not comited

## git restore from stageing area to working area
- `git restore --staged filename.txt` that back to staggeing area to working area.

## Diff b/w git rm and git restore
- if you want to move file back to `untracked stage` use `git rm` . other wise if you want the change to `working or staging` area use `git restore`.

## To create new branch
- `git branch -b <branch_name>` that help to create new branch
- TO view branch -> `git branch`

## To enter or check branch
 - `git checkout <branch_name>`

## To check logs
- `git log` to view all your logs
- How to exit git log -> By pressing `q` 


## How To connect your code and push to github
- 1 `git init `
- 2 `git add .`
- 3 `git commit -m <your_msg>`
- 4 `git branch -M  main`
- 5 ` git remote add origin <origin_url>`
- 6 `git push -u origin main` 

## remote origin
- `git remote rm <remote_connection_name>` this helps to delete the connection.
- `git remote rename <oldname> <newname>` this help to rename remote connection.

## git pull 
- after updateing and push all use `git pull`
- pull from specif branch -> `git pull <remmote_url> <branch_name>` eg: `git pull origin features`

## merge conflicts
- when happens when more people try to change the codebase commit or pull or push already then this happend.
- How to handle this -> try use `VSCODE` like `check accept bot changes or what you want`.




