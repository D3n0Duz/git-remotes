# Git Remotes (How to easily sync many Git servers with each other)

> :warning: **Assuming that both repositories already exists**

#### Cloning the repository

`git clone <First-Repository-Link>`

#### Adding a remotes

`git remote set-url origin --push --add <First-Repository-Link>`

`git remote set-url origin --push --add <Second-Repository-Link>` 

`git remote add origin-second-git-server <Second-Repository-Link>` 

#### Checking the remotes

`git remotes -v`


#### Push the changes everywhere

`git push origin --all`

#### Pull changes from First Repository Link

`git pull --all`

#### Pull changes from Second Repository Link

`git pull origin-second-git-server <branch-name>`
