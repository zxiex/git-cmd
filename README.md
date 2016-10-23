# git-cmd
some useful command for git
1 `git-ls` list the projects on the remote git server repo
1 `git-get` clone the remote project without the need to specify the URL
1 `git-pub` publish the local create git project into the remote server

all these commands need to read the enviroment variable `GIT_REPO`, which is 
baiscally `remote_host:/remote_git_repo_dir`

`git pull` and `git push` might need to set the upstream
