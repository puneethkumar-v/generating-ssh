#Creating SSH keys on Linux and setting them default for git and github

##Pre-requisite:
    - [x] Deleting the existing keys on the system
    - [x] Finding the ssh keys folder on the system \* [x] By Default ssh keys are present in the folder ~/.ssh

##Important things:
    - [x] Generating ssh keys using ssh-keygen
    - [x] Saving the key using any appropriate name as required
    - [x] Copy the ssh-key.pub content to the github
    - [x] Find the ssh key and gpg key settings under github setting and create a new ssh key and paste the copied public key into it and save
    - [x] Test the connection between your system and github.com using the command "ssh -T git@github.com"
    - [x] If the connection fails then add the current ssh key that you want to use using "ssh-add 'ssh-key'"
    - [x] Deploy your git files to the github and test

##Creating alias for basic git commands:
Syntax: alias [name]='the command'
    - [x] alias gss = 'git status'
    - [x] alias gaa = 'git add .'
    - [x] alias gp = 'git push -u origin'
    - [x] alias gcm = 'git commit -m'
    - [x] alias gbm = 'git branch -M main'
