# gitrepo

1: installed git for windows and linux machine 
2: creadted an account in github --- done 
3: create the pubblivc repo in github called myrepo

----------case study 
Deveopler is going to ccraete 	a projet on its loccal and move to the remote repo.

config 
git config --global user.name umasha
git config --global user.email umasha@mail.com


----------
1: craeting files and we see all are untracked -- not consider by git.
2:staging -- before commiting the code to local repo you need to stage.
3:commit -- menans commmite dto the loacal repositery
 
git status --
shows wheather the files are in which position 

git add one.txt  ADDS the files to git consideration.

and check throuugh status and thhe file is availble in green clour 
-----------	
git commit -m "one.txt is created"

git log-------
using git log commit detaails can be checked.
-------
git remote add origin 
git push -- sends the files to the remote 
git clone --clone the entire remote repo
git pull -- takes the wanted files frommthe remote to the loacal.
---------------
Branch -- master brach is the top of every branch 

master ---> conatils files like one.txt ,,,,seven.txt.
dev1_brach--
dev2_brach--

merge dev1_brach code to master 
master will have eight.txt

creating  brancch :
git branch dev1
git branch dev2

moving to other branch
eg:
git checkout dev1
git checkout master 
 
To detlete the branch
git branch -D dev1

merge :
git merge dev1 to master 
git merge dev1 

--------
to move other branches 
git push origin dev1
git push origin dev2

git log --graph --pretty=oneline
to se one line log of files in branches 

git diff 
sees the diffrent of the file



revert :
git revert "commmit id"
goes to version it was  before  

----------- 


git stash 
git stash pop



--------------



