# Introduction

BangkitGitTraining is a repository purposefully built to teach students how to use git and github

# Step by Step Guide

## **Step 1** 
Start by forking this repository by clicking the fork button on the upper right corner of the screen. 

!TODO: add image fork

This should automatically create your own version of the repository within your account. 

!TODO: add name

Then clone the repository by clicking the `[Code]` button and copying the https url. 
Go to git bash and write the command
```
git clone [https://...]
```
To clone the repository to your working directory

## **Step 2**

I have prepared a simple quiz for you to complete. But first, within the src folder, create a folder with the naming convention `firstname_lastname_bangkitcode` and copy the `quiz.py` inside your folder. Then complete the quiz.

## **Step 3**

After you have completed the `quiz.py` it is time to push your changes to github. Go to your folder by doing 
```
cd src/firstname_last_name_bangkitcode 
```
in git bash. Then do the command
```
git add quiz.py
```
Check whether or not the changes have been staged by doing
```
git status
```
Then commit the changes by doing
```
git commit -m "[Input your message here]"
```
Make sure you message is clear and explain what you have done. Also, git commit message should be longer than 10 words so as to not overflow your commit message into the description. Lastly, perform
```
git push origin master
```
To push your changes into the master branch of your forked repo.

## **Step 4**

Go back to `www.github.com` and now merge the changes you have made to the original repo by doing pull request. Click on your forked repo, and on top the screen click on `Pull Requests`. Select `New Pull Request` and then on the base repository make sure it is `EvanMillikanTKP/BangkitGitTraining` and in the head repository it is `[Your GitHub Name]/BangkitGitTraining`. 

OPTIONAL: you can put a short message in the description. 

Set the title as your name, then click on `Create pull request`

# Conclusion

That basically concludes your git training and should equip you with enough knowledge to collaborate with others using git and github. 

