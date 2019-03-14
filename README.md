# 

Shell Prompt magic
https://www.ibm.com/developerworks/linux/library/l-tip-prompt/

~~~~~~~~~~~~~~~~~~~~~~
$ cat ~/.bash_profile

if [ -f ~/.bashrc ]; then . ~/.bashrc; fi

export PS1="\w \$ "; clear;


~~~~~~~~~~~~~~~~~~~~~~
$ cat ~/.bashrc

echo "setting dinesh env"

source $HOME/din-env.sh


~~~~~~~~~~~~~~~~~~~~~~
Set P4 Editor in Mac
http://answers.perforce.com/articles/KB/2987
p4 set P4EDITOR="open -e -W -n"


Show/Hide Hidden Files on macOS 

defaults write com.apple.finder AppleShowAllFiles YES

https://ianlunn.co.uk/articles/quickly-showhide-hidden-files-mac-os-x-mavericks/

Install Zsh and then oh my zsh

SJC-ML-00038867% echo $SHELL
/bin/zsh

SJC-ML-00038867% sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"


https://github.com/robbyrussell/oh-my-zsh

https://medium.com/@elviocavalcante/5-steps-to-improve-your-terminal-appearance-on-mac-osx-f58b20058c84
https://github.com/powerline/fonts

https://medium.com/@Clovis_app/configuration-of-a-beautiful-efficient-terminal-and-prompt-on-osx-in-7-minutes-827c29391961
https://github.com/bhilburn/powerlevel9k/wiki/Show-Off-Your-Config

https://github.com/bhilburn/powerlevel9k

https://sourabhbajaj.com/mac-setup/iTerm/zsh.html


The Ultimate vimrc
The Ultimate vimrc it's a collection of vimrc configurations to make easy the usage of vim.

To download the The Ultimate vimrc, you need to install the git client. If you need install it, use home brew:

brew install git
Now, download the vimrc files:

git clone https://github.com/amix/vimrc.git ~/.vim_runtime
To install the complete version, run:

sh ~/.vim_runtime/install_awesome_vimrc.sh
To install the basic version, run:

sh ~/.vim_runtime/install_basic_vimrc.sh
Update
To update the vimrc scripts, run:

cd ~/.vim_runtime && git pull --rebase && cd -

Add Java to PATH
Add JAVA_HOME to your environment variables by adding the line below to your env.sh (see iTerm2 section if you don't have a env.sh file).

export JAVA_HOME="`/usr/libexec/java_home -v 1.8`"
If you are using Java 9, use the following:

export JAVA_HOME="`/usr/libexec/java_home -v 9`"

https://www.macrumors.com/how-to/use-mac-volume-keys-adjust-monitor-audio/
https://github.com/mattingalls/Soundflower
brew cask install soundflower


