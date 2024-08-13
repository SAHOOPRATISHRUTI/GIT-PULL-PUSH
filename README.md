"# GIT-PULL-PUSH" 
Git Push through Command Line 
Steps:

Step:1
 echo “#reponame” >> README.md
 git init
 git add README.md 


Step:2
	git commit -m “first commit” 
	git branch -M main
	git remote add origin “path repo”
	git push -u origin main
	


Lets take an example -
echo "# MOMFrontend" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/SAHOOPRATISHRUTI/MOMFrontend.git
git push -u origin main

Git Pull through Command Line 
Steps:

Step:1
	Fork the Repository
Step:2
	git clone “path of the clone repo”
Step:3
	Create a new branch and Switch to it — git checkout -b ‘branch-name’
Step:4
	git remote add Upstream(when you changes anything in the clone project  the changes also          syncing to the origin project )  —-- git remote add upstream “original-repo-path”

Step:5
	Change and Update what do you want to do
Step:6
	Verify the changes you made —- git diff –word-diff
Step:7
	Commit your Changes to the branch  —-  git commit -a -m “ commit-by-XXXX”
Step:8
	Push the branch backup to your git hub repo – git push origin ‘branch name’
 


git remove remote---- git remote remove <remote-name>

 https://docs.google.com/document/d/1cwj54bsI3q_MwhxqFzBxOG9qqW8ZRYcn5MOlW4Raz6o/edit?usp=sharing---acess this link  for the worf file

edit by Monalisa------------------pratishruti
