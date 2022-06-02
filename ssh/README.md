# How to setup personal and work account

1. Setup personal and work ssh key
    - `ssh-keygen -t rsa -b 4096 -C "EMAIL@...`
    - visit github/gitlab.com and insert the .pub key
2. The default ssh key utilize `Host github.com`
    - For personal projects change remote to `personal-github.com` per repository
    - `git remote add <REPO_NAME> git@personal-github.com:<GITHUB_USER>/<REPO_NAME>.git`
    - verify `git remote -v`
