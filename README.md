# dotfiles
My dotfiles

## Instructions
Terminal -> Profile Preferences:
- Pallete: Solarized 
- Use transparent background: ~15%
- Text color: #1ec503

Install [cURL](https://curl.haxx.se/):  
`sudo apt-get install curl`

Install [Git](https://git-scm.com/):  
`sudo apt-get install git`

Install [Vim](http://www.vim.org/):  
`sudo apt-get install vim`  

Install [vim-pathogen](https://github.com/tpope/vim-pathogen):  
`mkdir -p ~/.vim/autoload ~/.vim/bundle`  
`curl -LSso ~/.vim/autoload/pathogen.vim https://tpo.pe/pathogen.vim`  

Install [base16-vim](https://github.com/chriskempson/base16-vim):  
`git clone https://github.com/chriskempson/base16-vim.git ~/.vim/bundle/base16-vim`  

Install [NERDTree](https://github.com/scrooloose/nerdtree):  
`git clone https://github.com/scrooloose/nerdtree.git ~/.vim/bundle/nerdtree`

Install [Ruby](https://www.ruby-lang.org):  
`sudo apt-get install ruby-full`

Install [Maven](http://www.mkyong.com/maven/how-to-install-maven-in-ubuntu/):  
`sudo apt-get install maven`  

Install [Java](https://www.digitalocean.com/community/tutorials/como-instalar-o-java-com-apt-get-no-ubuntu-16-04-pt):  
`sudo add-apt-repository ppa:webupd8team/java`    
`sudo apt-get update`  
`sudo apt-get install oracle-java8-installer`

Install [ZSH](https://github.com/robbyrussell/oh-my-zsh/wiki/Installing-ZSH):  
`sudo apt-get install zsh`

Install [Oh My ZSH](http://ohmyz.sh/):  
`sudo sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`

Install [tmux](https://github.com/tmux/tmux/wiki):  
`sudo apt-get install tmux`

Install [tmuxinator](https://github.com/tmuxinator/tmuxinator):  
`gem install tmuxinator`

Make folders:  
`mkdir projects && cd $_`  
`mkdir me && cd $_`

Clone [dotfiles](https://github.com/rodrigopandini/dotfiles) repo:  
`sudo git clone git@github.com:rodrigopandini/dotfiles.git`  
and copy files to /home folder

Clone [base16-shell](https://github.com/chriskempson/base16-shell) repo:  
`git clone https://github.com/chriskempson/base16-shell.git ~/.config/base16-shell`  
and type `base16_default_dark` to use "default dark theme"

Install [NVM](https://github.com/creationix/nvm):  
`curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.5/install.sh | bash`

Install [Yarn](https://yarnpkg.com/lang/en/docs/install/):  
`curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list`  
`sudo apt-get update && sudo apt-get install yarn`

Install [pip](https://www.saltycrane.com/blog/2010/02/how-install-pip-ubuntu/)  
`sudo apt-get install python-setuptools python-dev build-essential`  
`sudo easy_install pip`  
`sudo pip install --upgrade virtualenv`   

Install [AWS cli](http://docs.aws.amazon.com/pt_br/cli/latest/userguide/installing.html)  
`pip install awscli --upgrade --user`  
and configure [aws credentials](http://docs.aws.amazon.com/pt_br/cli/latest/userguide/cli-chap-getting-started.html)  

Install programs:  
- [Code](https://code.visualstudio.com/)
- [Insonia](https://insomnia.rest/)  
- [Slack](https://slack.com/downloads/linux)  
- [Spotify](https://www.spotify.com/br/download/linux/)  

Install browsers:  
- [Chrome](https://www.google.com.br/chrome/browser/desktop/index.html)  
- [Firefox (Dev)](https://www.mozilla.org/pt-BR/firefox/developer/)  
- [Opera](http://www.opera.com/pt-br)  

Add ssh for github:  
https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/  
https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account/

Clone your github projects!  

Utils:  
Install [htop](http://hisham.hm/htop/)

For fun:  
Install [cmatrix](http://www.asty.org/cmatrix/)  
Install [cool-retro-term](https://github.com/Swordfish90/cool-retro-term)  

Frequently remember to update and upgrade your distribution:  
`sudo apt-get update`  
`sudo apt-get upgrade`  
