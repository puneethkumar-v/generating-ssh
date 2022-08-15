#Creating SSH keys on Linux and setting them default for git and github

##Pre-requisite:
_ [x] Deleting the existing keys on the system
_ [x] Finding the ssh keys folder on the system \* [x] By Default ssh keys are present in the folder ~/.ssh

##Important things:
_ [x] Generating ssh keys using ssh-keygen
_ [x] Saving the key using any appropriate name as required
_ [x] Copy the ssh-key.pub content to the github
_ [x] Find the ssh key and gpg key settings under github setting and create a new ssh key and paste the copied public key into it and save
_ [x] Test the connection between your system and github.com using the command "ssh -T git@github.com"
_ [x] If the connection fails then add the current ssh key that you want to use using "ssh-add 'ssh-key'"
\_ [x] Deploy your git files to the github and test

##Creating alias for basic git commands:
Syntax: alias [name]='the command'
_ [x] alias gss = 'git status'
_ [x] alias gaa = 'git add .'
_ [x] alias gp = 'git push -u origin'
_ [x] alias gcm = 'git commit -m'
\_ [x] alias gbm = 'git branch -M main'
