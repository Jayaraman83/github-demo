Learning github:

commands:

create a github local repo:
Goto the folder where you need to create a repo Ex: c:/git-demo
Goto terminal and type: 
cmd: git init --> This will create a repo in this directory locally
Now Type 
cmd: git status
--> This will show the codes which are not commited in this folder.

If you have changed a file inside a directory & want to commit changes to the Local GIT Repository :
cmd: git add <filename>
Ex: git add sample3.html

To commit these files to Local Repo:
First you need to configure user name and email address for you to commit changes:

cmd1: 
git config --global user.name "Jay Bala"
git config --global user.email "jayaraman83@gmail.com"

To check if these are configured:
cmd: git config --global --list

Output:
jayaramanb@jayaramans-air git-demo % git config --global --list
user.name=Jay Bala
user.email=jayaraman83@gmail.com
jayaramanb@jayaramans-air git-demo % 


Now finally to commit the files into Local Repository:
cmd: git commit -m "First Commit"

So Step 1: To Move the changed file to Staging area : Command is : git add <filename>
   Step 2: To commit the changed files from Staging to the Local Repository: git commit -m "Comments"

If you have changed multiple files and move all of them to gether:
1. To Move them to stage: git add *
2. To Move stage to Local Repo: git commit -m "Comments"