1.git init

2.git add <fileName> : For Tracking (It is not Yet Saved)

3.git commit -m "Some Massage" : For Saving

4.git log > To See commit log

5.git checkout "id of commit" > to switch to previous commit status
6.git checkout master > To come back to current status
git remote add origin https://github.com/Ishansharma1607/GITTEST.git
git push -u origin master




----------------------------
2.git init > This command tell git that It is repository
3.notepad hello.texfl
4.git add hello.txt > To start tracking hello.txt
| File will be moved to Stagging Are for tratcking

5.git commit -m "My First Commit" > For Commiting/Save
6.git log > to know history of Changes/commit
7.git checkout "id of commit" > to switch to previous commit status
8.git checkout master > To come back to current status
9.Set Email id & name:

git config --global user.email "email id"

git config --globa1 user.name "name of Person"
16.git clone https://github.com/vprem99/GitRemotePlace.git > for cloning repository to another system
11.git pull origin master > For getting fresh/Update Repository from GitHub
12.git remote add origin https://github.com/vprem99/GitRemotePlace.git
13.git push -u origin master
git is tool to track Changes in Files/Folder.
gitHub is a Platform to Store your repositories on Cloud.
git != Github



For Updating Renamed Branch Name
-----------------------------------
git branch -m stagging main
git fetch origin
git branch -u origin/main main
git remote set-head origin -a
-------------------------------

Create new Branch and Merging
---------------------------
git checkout -b stagging

Switch to Stagging Branch
git checkout stagging
git merge stagging
or
git merge stagging --allow-unrelated-histories
Now
git add .
git commit -m "My merging Done"
git push origin master

----------------------------

Deleting a branch
-----------------------
git push origin --delete stagging



===================================
1.Added a Text file & Added Numbers into this While You Are In master
2.git add & git commit will be fired
3.Create new Branch X
4.Add Alphabets

5.git add & git commit will be fired. 
6.Switch to Master & delete Some Numbers

7.git add & git commit will be fired.

8.Switch to X Branch

9.Try to merge Master into X
=============================================

