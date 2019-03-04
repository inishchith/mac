# mac 


## # Packages


### Xcode

```bash
$ xcode-select --install
```

### Brew

```bash
$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

### Vim

```bash
$ brew install vim
```

### Tmux

```bash
$ brew install tmux
```

### Git

```bash
$ brew install git
```

### Oh My Zsh

```bash
$ sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

<hr>


### Setup Dotfiles

- Setup dotfiles from this [repo](https://github.com/inishchith/dotfiles)

```bash
$ git clone https://github.com/inishchith/dotfiles.git ~/.dotfiles
```

### [VSCode](https://code.visualstudio.com/)

- [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
- [TODO Highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight)
- [Beautify](https://marketplace.visualstudio.com/items?itemName=HookyQR.beautify)
- [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
- [Visual Studio IntelliCode - Preview](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode)
- [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)

### Generate ssh key

```bash
$ ssh key-gen
$ cat .ssh/id_rsa.pub
```

### Java

- Download jdk 8 from this [link](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html) after accepting the Agreement Terms. Open dmg and follow through the setup process. Check if java is installed properly by running

```bash
$ java -version
```

### Python

```bash
$ brew install python@3

# check if python and pip both are pointing to version 3

$ pip install virtualenv
```

### Node.js

```bash
$ curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.11/install.sh | bash
$ source ~/.zshrc
$ nvm install <version>
```

### Tree

```bash
$ brew install tree
```

### Evernote

- Download evernote from this [link](https://evernote.com/download)

### Workflowy

- Download workflowy from this [link](https://workflowy.com)

### Trello

- Download workflowy from this [link](https://trello.com/)

### DaisyDisk

- Download daisydisk from this [link](https://daisydiskapp.com/)

## System Preferences (customize)

- Trackpad
- Dock
- Battery

<hr>

## OPTIONAL

### Iterm2

- Download and install iterm2 from [here](https://www.iterm2.com/downloads.html)

#### Iterm2 Preferences

* Profiles
* General
* Check *Reuse previous session directory* under *Working Directory*
* Terminal
* Check Unlimited Scrollback
* Follow this [link](https://coderwall.com/p/h6yfda/use-and-to-jump-forwards-backwards-words-in-iterm-2-on-os-x) to jump words backward/forward.
