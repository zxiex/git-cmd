# git-cmd
Tried to set up **gitlab** for home projects. Spent a few hours and finally got it running, but can't see any real benefit for such a huge package if the only thing I want is to freely create projects or a *git server*. Finally removed everything and wrote these three  small commands for git

* `git-ls` list the projects on the remote git server repo

* `git-get` clone the remote project without the need to specify the URL

* `git-pub` publish the local create git project into the remote server

all these commands need to read the enviroment variable `GIT_REPO`, which is 
baiscally `remote_host:/remote_git_repo_dir`

`git pull` and `git push` might need to set the upstream

# use
copy these `git-*` to your `$PATH` and also export the enviroment variable `GIT_REPO`, then you can use `git ls`, `git get` and `git pub` commands.
