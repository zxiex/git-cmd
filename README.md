# git-cmd
This repo contains three simple commands to interact with a *git repo* hosted on a remote server accessible by `ssh`. 

* `git-ls` list the projects on the remote git server repo

* `git-get` clone the remote project without the need to specify the URL

* `git-pub` publish the local create git project into the remote server

all these commands need to read the enviroment variable `GIT_REPO`, which is 
baiscally `remote_host:/remote_git_repo_dir`

`git pull` and `git push` might need to set the upstream

# use
copy these `git-*` to your `$PATH` and also export the enviroment variable `GIT_REPO`, then you can use `git ls`, `git get` and `git pub` commands.
