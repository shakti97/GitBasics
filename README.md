# GitBasics
GitCommands

start your project with command
git init :- it will initialize your project with the .git file which will be responsible for detecting
             the change in the directory, it is invisible but u can view it by allowing to show the hidden files.
             
Do some stuff like creating files to be used in your project if u had it already then ignore

git status :- it will give you the status of the tracked files and untracked files

git add <<file>> :- it will make your files ready to be commit in the tree

git commit -m <<message>> :- it will commit all the staged file to the local repository

If you want to commit your files in the remote repository , first make a repository in the github and take the origin(master) url from the
repository 
It will be like example 
git remote add origin https://github.com/******/*******.git

then just use the command 
git push -u origin master :- It will push the local repository to the remote origin
while performing the last command Github will ask your username and the password, this should be only for one time 

Now you can check out that the content is pushed in the remote repository

