# dotfiles
My dotfiles :)

## Instructions
Terminal -> Profile Preferences:
- Rename: "matrix"
- Pallete: Solarized 
- Use transparent background: ~15%
- Text color: #1ec503
- Background color: #000000

Install [cURL](https://curl.haxx.se/):  
`sudo apt-get install curl`

Install [Git](https://git-scm.com/):  
`sudo apt-get install git`

Create new SSH Key to add in GitHub:  
https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/  
https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account/  

Install [Vim](http://www.vim.org/):  
`sudo apt-get install vim`  

Install [vim-pathogen](https://github.com/tpope/vim-pathogen):  
`mkdir -p ~/.vim/autoload ~/.vim/bundle`  
`curl -LSso ~/.vim/autoload/pathogen.vim https://tpo.pe/pathogen.vim`  

Install [base16-vim](https://github.com/chriskempson/base16-vim):  
`git clone https://github.com/chriskempson/base16-vim.git ~/.vim/bundle/base16-vim`  

Install [NERDTree](https://github.com/scrooloose/nerdtree):  
`git clone https://github.com/scrooloose/nerdtree.git ~/.vim/bundle/nerdtree`

Install [ZSH](https://github.com/robbyrussell/oh-my-zsh/wiki/Installing-ZSH):  
`sudo apt-get install zsh`

Install [Oh My ZSH](http://ohmyz.sh/):  
`sudo sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`

Install oh-my-zsh custom plugins:  
- [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions/blob/master/INSTALL.md#oh-my-zsh)

Clone [base16-shell](https://github.com/chriskempson/base16-shell):  
`git clone https://github.com/chriskempson/base16-shell.git ~/.config/base16-shell`  
and type `base16_default-dark` to use "default dark theme"

Install [tmux](https://github.com/tmux/tmux/wiki):  
`sudo apt-get install tmux`

Install [golang](https://golang.org/doc/install)  

Install [docker](https://docs.docker.com/engine/install/ubuntu/)

Install [docker-compose](https://docs.docker.com/compose/install/)

Install [docker-compose completion](https://docs.docker.com/compose/completion/)

Install [kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/)  

Install programs:  
- [Code](https://code.visualstudio.com/)
- [Insonia](https://insomnia.rest/)  
- [Slack](https://slack.com/downloads/linux)  


Make folders:  
`mkdir projects && cd $_`  
`mkdir me && cd $_`  

Clone [dotfiles](https://github.com/rodrigopandini/dotfiles) repo:  
`git clone git@github.com:rodrigopandini/dotfiles.git`  
and copy files the following files to your `/home` folder:  
  - .zshrc
  - .vimrc_background
  - .vimrc
  - .tmux.conf
  - .tmuxinator/  
After, type `source ~/.zshrc` to reload zsh configurations.



**Clone your github projects!**  

------

(optional)
Install [Ruby](https://www.ruby-lang.org):  
`sudo apt-get install ruby-full`

(optional)
Install [Maven](http://www.mkyong.com/maven/how-to-install-maven-in-ubuntu/):  
`sudo apt-get install maven`  

(optional)
Install [Java](https://www.digitalocean.com/community/tutorials/how-to-install-java-with-apt-on-ubuntu-18-04):  
`sudo apt install default-jre`    
`sudo apt install default-jdk`  

(optional)
Install [NVM](https://github.com/creationix/nvm):  
`curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.5/install.sh | bash`

(optional)
Install [pip](https://www.saltycrane.com/blog/2010/02/how-install-pip-ubuntu/)  
`sudo apt-get install python-setuptools python-dev build-essential`  
`sudo easy_install pip`  
`sudo pip install --upgrade virtualenv`   

(optional)
Install [tmuxinator](https://github.com/tmuxinator/tmuxinator):  
`gem install tmuxinator`

------

Utils:  
Install [htop](http://hisham.hm/htop/)

For fun:  
Install [irssi](https://irssi.org/)  
Install [cmus](https://cmus.github.io/)  
Install [cmatrix](http://www.asty.org/cmatrix/)  
Install [cool-retro-term](https://github.com/Swordfish90/cool-retro-term)  

----

Frequently remember to update and upgrade your distribution:  
`sudo apt-get update`  
`sudo apt-get upgrade`  
