# git_learning
<br>
Author : Pritam Padhan
<br>
Learning git from scratch
<br>
In this repository i will keep all my learning about Git and Github.
<br>
I started with watching "apna college/git and github for beginers".
<br>
To initialize a local repo as git repo, we have to run the command: git init
<br>
To clone the remote repo, where we want to do the modifications, we run the command: git clone <remote repo link>
<br>
To stage all untracked files(newly added files) and modified files, we run the command: git add .
<br>
To commit all the changes, we run command: git commit -m "message"
<br>
To do the final push into the remote repo, use command: git push origin main
<br>
Before push, you have to do the following set up, it's one time set up.
<br>
git config --global user.name "user github account name"
<br>
git config --global user.email "user github account password"

<br>
Now we will learn about "branch"
Why we need branch?
 in one project there may more then one devloper working.
 So they can use, git branch. Then can create separate separate branch and push their code. later they can merge their branch.
1. To check the current branch name, command: git branch
2. To rename the branch name, command: git branch -M main
3. To go one branch name to diff branch name: git checkout <branch name>
4. To create a new branch, command: git checkout -b <branch name>
5. To delete a branch, command: git checkout -d <branch name>

Merging code:
1. To check the difference: git diff <branch name>
2. To merging the code: git merge main

