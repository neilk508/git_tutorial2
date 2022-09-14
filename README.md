# git_tutorial2

need to use clone to download the file to the local machine 
need to cd into the folder to be in the git repo
need to use ls -la to see all files in the folder

## this is a subheader 

git status tells us all changes that have been made but not committed 
you need to tell git to track new files before committing
    git add . is telling git to track all files
    could also tell specific files and folders  

to commit use git commit -m "message that has to do with the what and why" -m "used for the description box"
    now the code is saved locally but not to github 

need to use git push to push to a repository live 
##ssh keys 
need to prove to github that you are the owner using ssh keys 
need to generate locally : ssh-keygen -t {type of encryption} -b {strength of encryption} -C "email address"

## need to find the key 
ls | grep testkey -> need to upload the .pub file to interface 

## branching 
use git branch to see the branches in the repo
use git checkout to switch branches 
use git checkout -b {feature} to create a new branch