Git Prompt Settings
===================

This is my git settings stuff. It's stuff I've cobbled together over the years of using git.


## Usage

Clone to repo somehwere, and add the following to your .bash_profile or .bashrc

```
source ~/path_to_files/colours.sh
source ~/path_to_files/git-prompt.sh
source ~/path_to_files/git-completion.sh
```

This will give you a git prompt that looks something like this:

```
emyr@localhost ~/development/someproject (master)*$
```

Where the branch name is on display, and the * tells you if the branch is clean or dirty (i.e. has modifications made to it.)

There's also an alternative to git log in this repo as well, and to use that, run:


```
cp gitconfig ~/.gitconfig
```

