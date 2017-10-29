# Git pull
=========

Just pull git repo

Role Variables
--------------

private key enabled to the repo, must be readable only from the owner (chmod 400)

```
git_key: id_rsa
git_url: github.com/myprofile/myprivaterepo
git_branch: master
git_dir: /tmp
```
