# 

Shell Prompt magic
https://www.ibm.com/developerworks/linux/library/l-tip-prompt/

$ cat ~/.bash_profile

if [ -f ~/.bashrc ]; then . ~/.bashrc; fi

# https://www.ibm.com/developerworks/linux/library/l-tip-prompt/
export PS1="\w \$ "; clear;

$ cat ~/.bashrc

echo "setting dinesh env"

source $HOME/din-env.sh
