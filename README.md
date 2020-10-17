# Git Remotes (How to easily sync many Git servers with each other)

> :warning: **Assuming that both repositories already exists**

#### Cloning the repository

`git clone <First-Repository-Link>`

#### Adding a remotes

`git remote set-url origin --push --add <First-Repository-Link>`
`git remote set-url origin --push --add <Second-Repository-Link>`

#### Checking the remotes
`git remotes -v`

#### Push the changes
`git push origin --all`
