# Assignment 3 -Saeed 1081922

## Step-by-step Actions

### 1. Setup Git Repository:

First, I created a directory in my downloads file using (mkdir) command, then I initialized it using (git init).

Second, I created a README.md file by (touch) command and i used (vim) to write the discription of the project in README file.

Third, I staged and commited the README file by using (git add .) and (git commit -m "the message") command.

### 2. Making Changes and Vision Control:

First, I created a new branch called feature-1 by (git branch) command and switching to it by (git checkout) command.

Second, I created the app.py file and I wrote the print statement in the file. Then staged and commited it.

Third, I modified the app.py by adding a new print statement that prints my name. Then staged and commited it.

### 3. Merging Branches:

First, I switched back to the master branch and merged the feature-1 branch by (git merge) command. I didnt face any merging issues.

### 4. Using GitHub:

First, I created a new account on GitHub and I created a repository called my_project under that account.

Second, I added the local my_project file to GitHub by (git remote add origin) command followed by my GitHub repository url, then pushed both master and feature-1 branches by (git push -u origin) command followed by the name of the branches. Then checked from GitHub that everything was pushed properly.

### 5. Collaboration Simulation:

First, I created a branch called bugfix-1 and switched to it. Then I added my family name in the print statement that print my name. Then staged and commited this branch and pushed it to my_project repository that is in GitHub.

Second, I requested a pull on GitHub and merged the branch into the master branch from GitHub.

### 6. History and Revision:

First, I used (git log) command to view my commit history.

Second, I reverted to my last commit on the master branch by using (git reset --hard HEAD~1) command.

## Encountered issues

I have faces two issues in this assignment and they made me start all over again. 

The first issue was pushing the local my_project to GitHub, when i tried to do that and error message shows up that says something like the password authentication has been canceled. I searched about it and found two ways to resolve this issue, either by the SSH key (secure shell) or by PAT (personal access token). I used the PAT becuase it was easier.

The second issue was after pushing the local my_project to GitHub I thought that all branches will be pushed, but turns out it only pushes the branch name you entered after (git push -u origin) and I learned that in my second try. I resolved it by pushing botht the master and the feature-1 branch.