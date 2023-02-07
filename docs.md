## Setting Up SSH Keys for GitHub

```
- `ssh-keygen -t ed25519 -C example@gmail.com`
- `eval "$(ssh-agent -s)"`
- `touch ~/.ssh/config` create config file and write the below configuration
- `cat id_ed25519.pub` copy the content and paste on github SSH
- `ssh -T git@github.com` test the ssh key
```

inside `~/.ssh/config`:

```
Host *
 AddKeysToAgent yes
 IdentityFile ~/.ssh/id_ed25519
```

```
- Start Windows subsystem Linux
- Install Ubuntu from Microsoft Store
- `sudo apt-get install software-properties-common`
- `sudo add-apt-repository ppa:fenics-packages/fenics`
- `sudo apt-get update`
- `sudo apt-get install fenics`
- pip3 -V
```
