## Setup
Initialize Borg repo, log directory and export key.
```console
borg init --encryption repokey --make-parent-dirs ssh://u370415-sub1@zentrallager.walloner.net:23/home/repo
borg key export ssh://u370415-sub1@zentrallager.walloner.net:23/home/repo
mkdir /home/logs
```
