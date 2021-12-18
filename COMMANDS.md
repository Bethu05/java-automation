CLI - Command Line Interface
Repository - Project, or the folder/place where your project is kept
Github - A website to host all your repositories
Git - Tool that tracks changes of code over time
clone -> Bring  a repository that is hosted somewhere like Github into a folder in computer
add -> Track your files and changes in Git
commit -> Save your files in Git
push - Upoad Git commits to a remote repo, like Github
pull -> Download changes from remote repo to your local machine, the oppositr of push

# Commands - pull repository to the local machine

## CLONE REPOSITORY
git clone <ssh name>
## Commit Channges
git status - shows files created, deleted but not yet changed
git add . /or/ git add <specific file name>  - add untracked files
git commit -m "message for doing the commit" -m "Message for commiting"

git pull --rebase origin

## git push
git -u push origin



## SSH KEY GENERATION
### ssh key generation
ssh-keygen -t rsa -b 4096 -C "bethwellangat05@gmail.com"
### adding key to ssh-agent
ssh-add ~/.ssh/id_rsa
### Start ssh-agent
eval "$(ssh-agent -s)"
eval `ssh-agent -s`




<!-- NEW REPOSITORY -->
1. Create the repository
2. Turn into git repository - git init
