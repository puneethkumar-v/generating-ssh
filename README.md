# Creating SSH keys on Linux and setting them default for git and github

## Pre-requisite:
- [x] Deleting the existing keys on the system
- [x] Finding the ssh keys folder on the system
- [x] By Default ssh keys are present in the folder ~/.ssh

## Important things:
  - [x] Generating ssh keys using ssh-keygen:
```sh
ssh-keygen -t ed255l9 -C 'mail_id'
```
- [x] Saving the key using any appropriate name as required
- [x] Copy the **ssh-key.pub** content to the github
- [x] Find the ssh key and gpg key settings under github setting and create a new ssh key and paste the copied public key into it and save
- [x] Test the connection between your system and github.com using the command:
```sh
ssh -T git@github.com
  ```
- [x] If the connection fails then add the current ssh key that you want to use using:
```sh
ssh-add 'ssh-key'
```
- [x] Deploy your git files to the github and test

## Creating alias for basic git commands:
Syntax: alias [name]='the command'
```sh
alias gss = 'git status -s'
alias gaa = 'git add .'
alias ga = 'git add'
alias gpsh = 'git push'
alias gpsho = 'git push origin'
alias gcm = 'git commit -m'
alias gbm = 'git branch -M main'
```
