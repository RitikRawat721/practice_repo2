# Making a git repository Locally
* create a folder 
* create or copy the files in the folder which you want to make a repository
* in the terminal type "git init"
You will have something like this [Initialized empty Git repository in C:/Users/USER/Desktop/websites/git/practice_repo2/.git/]

## How to push the files in remote repository
* Create a repository in the github
* come to the terminal and type "git add remote origin [link of the repository]"
* you can check the remote repopsitory connected in the current repo by typing "git remote -v"
* to push you can do "git push orgin main" OR 
* if you want the coming files to push directly to this repo you type "git push -u origin master" [-u = upstream]
* after putting the above command you can just type "git push" and it will automatically push the files in that repo

## NEXT is Branching 