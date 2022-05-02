# cammand that are followed in Aiops project
## for clonning the Repo from the github 
'''git clone https://github.com/bharatbhushandwarkewasi/Aiops_project.git 
'''

## for create the folder in the local system
 '''touch <main.py> 
 '''

## for createing the read me file
 '''touch <README.md> 
 '''

## to track file into the staging or to allow file to tracked by git 
''' git add <file_name> 
'''

## for logging you have to execute this cammands 
'''
git config --global user.name "your mail id"

git config --global user.mail "your name" 
'''

## to perform commit 
'''git commit -m 
'''

## rename current branch to main branch 
'''git branch -M main
'''

## to check remote branch url and name 
'''git remote -v 
'''

## to send the changes in remote brances
'''git push <remote_branch_variable> <branch_name>
'''

## to list the branch name 
'''git branch 
'''

to remove from the staging area 
'''git rm --cached
 '''

## to crete the conda runtime virtual environment for project 
'''conda create -p python==3.7 -y
'''

## to activate the conda environment for project
'''conda activate <./dir_name>
'''

## to ignore the multiple file in the virtual environment
'''touch .gitignore
'''

## to create the jupter lab 
'''pip install jupyter lab
'''

## to create the all the requirements.txt
'''pip freeze>requirements.txt
'''
