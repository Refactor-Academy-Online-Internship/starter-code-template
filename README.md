# Steps to Submit your solution :

- Clone (or pull) the repositary in your local pc.
```
git clone <repo_link>
git pull
```

- For every new milestone you will create a new branch, e.g for Milestone 2, you will create a branch called milestone-2 (no spaces)
```
To create a new branch, use the below code :

git checkout -b <branch_name>
```

- Once you have created the branch, make sure you are currently working under the same branch :
```
git branch

master
*milestone-2
```
- If you see an an asterix mark (*) against your branch name, then that is the branch you are currently working on.
- NOTE : If you are on the wrong branch, switch to your correct branch using the code below :
```
git checkout <branch_name>
```
- Once you are working on the current branch, write your solution, by making new files and completing the subtasks.
- Once you have built your project, and made sure it is in a working state:
- Add all the files to the staging area :
```
git add .
```
-  Once all the files are in the staging area, commit your task, with a message (should signify the changes):
```
git commit -m "Completed all subtasks"
```
- Once you have commited your changes, you should push all the changes from your local repositary to your github repo.
```
git push origin <branch_name>
```
<br>
THATS ALL! You have successfully submitted your milestone.
<br>
<h3> NOTE : TO WORK ON A NEW MILESTONE NOW, ALL YOU HAVE TO DO IS CHANGE TO A NEW BRANCH BY FOLLOWING THE ABOVE STEPS AND REPEAT THE PROCESS <h3>
