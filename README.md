## :wave: About :wave:

Easy to use git shortcut commands aimed to increase developer's productivity in Linux environment.  
Shell scripts are added globally.  


## :desktop_computer: Installation :desktop_computer:
  
Scripts are added to /usr/local/bin (with executable permissions) to allow global execution.
  
Clone this repo, navigate to it and execute ``` bash install ``` in terminal.
  
## :no_entry: Removal :no_entry:
 
Navigate to this repo, execute ``` bash uninstall ``` in terminal.
 

## Features

| Shell Shortcut | Git Command | What it does |
| ------ | ------ | ------ |
| gaa | git add . | :white_check_mark: Add all changes |
| gacp | git add . && git commit -m `<message>` && git push origin `<branch>` | :white_check_mark: Add all changes, commit with message and push to specific branch |
| gc | git checkout `<branch>` | :white_check_mark: Switch to another branch |
| gcb | git checkout -b `<branch>` | :white_check_mark: Create new and switch to another branch from current | 
| gce | git config user.email `<email>` | :white_check_mark: Set config for email |
| gcmsg | git commit -m `<message>` | :white_check_mark: Commit changes with message |
| gcn | git config user.name `<name>` | :white_check_mark: Set config for name |
| ghelp | /**/ | print out overview of commands |
| gm | git merge `<branch>` | :white_check_mark: Merge named branch to current |
| gpo | git push origin `<branch>` | :white_check_mark: Push changes to specific branch |
| gpom | git push origin master | :white_check_mark: Push changes to master |
| grh | git reset --HARD | :warning:`CAUTION.` Delete all changes |
| grlb | git delete -d `<branch>` | :warning:`CAUTION.` Delete branch locally if branch is clean |
| grlbf | git delete -D `<branch>` | :warning:`CAUTION.` Delete branch even if its not clean |
| grrb | git push origin --delete `<origin-branch>` | :warning:`CAUTION.` Delete remote branch  |
| gs | git status | :white_check_mark: Display state of current working dir |
| gpull | git pull | :white_check_mark: Pull changes |
| gpullo | git pull origin `<branch>` | :white_check_mark: Pull changes from origin |

  
