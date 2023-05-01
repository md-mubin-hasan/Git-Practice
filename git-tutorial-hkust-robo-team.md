git workflow?

creating a git repo
1. make a new floder
2. git init   #init a repo
3. git remote add origin "ADDRESS"  # add a remote repo to you local repo
4. git remote -v

clone 

git clone “ADRESS(http/ssh)” # you can clone a remote repo from github 

add and commit
1. add: Stage your changes, i.e. tell git what you have changed
2. commit: turn your code into a git object and move to repository, i.e. record your changes each commit has a commit id in SHA-1. If git commit is executed, HEAD will point to this commit.
Commit without add, git will not record any changes
Add without commit, nothing will be uploaded when push
3. Upload your commit
# git push <remote> <branch>
git push origin master

Add new branch
	git branch <BRANCH>

Change branch
	git checkout <BRANCH>

Both with one command
	git checkout -b

If want to combine two branch:
	git merge <branch>

then it will automatically perform the merging.
	If it is unsuccessful, merge conflict occurs. You need to solve it and commit and you are not allowed to checkout or perform another merge.
	Even if it successfully merged, you need to check what has been changed(Can be checked by diff) as it is very unreliable.

git state?
branch workflow?
