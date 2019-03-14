# Dieter Joubert's dotfiles

## Bash and Git dotfiles

Make symbolic links to this repository!

```bash
ln -s /Users/dieterjoubert/Code/dotfiles/bash_profile  /Users/dieterjoubert/.bash_profile
ln -s /Users/dieterjoubert/Code/dotfiles/bashrc  /Users/dieterjoubert/.bashrc
ln -s /Users/dieterjoubert/Code/dotfiles/gitconfig /Users/dieterjoubert/.gitconfig
ln -s /Users/dieterjoubert/Code/dotfiles/gitignore /Users/dieterjoubert/.gitignore
```


## 2019/03 Space Grey Macbook Pro Setup Notes


### Installation Notes

- VLC
- Google Chrome
- Spotify
- Evernote


[Canopy v2.1.9 (python 3.5)](https://store.enthought.com/downloads/)

- brew

```bash
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

- setup this dotfiles repository

- setup SSH keys 
[generate SSH keys](https://help.github.com/en/enterprise/2.16/user/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

```bash
ssh-keygen -t rsa -b 4096 -C "dieterjoubert@gmail.com"
```

- [setup ssh keys in github](https://help.github.com/en/enterprise/2.16/user/articles/adding-a-new-ssh-key-to-your-github-account
)
```bash
pbcopy < ~/.ssh/id_rsa.pub
```

- [Sublime Text 3](https://www.sublimetext.com/3)

- [sublime text 3 package control](https://packagecontrol.io/installation)

- [sublime text 3 gitgutter](https://github.com/jisaacks/GitGutter)





