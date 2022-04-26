# Git Command
clear.  
git --version.  
1. git init.  
2. git clone (ssl or https).  
3. git status.  
--------------------

# Add file
1. git add . (or filename).  
2. git commit -m "Title" -m "message"    
3. git push -u origin master (repos,branch).  
1. git remote add origin (ssl or https).  
2. git remote -v.  
3. git push -u (for default) origin master (can user git push later).  
--------------------
# Branch
1.  git branch.  
2.  git checkout -b(create new branch) feature-instructions.  
3.  git status.  
4.  git add .   
5.  git commit -m "Title" -m "Message".  
6.  git checkout master.  
7.  git diff  feature-instructions.  
8.  git checkout feature-instructions.  
9. git push -u origin feature-instructions.  
--------------------
# Pull / Merge
 (After Mergerd).  
1. git checkout master.  
2. git pull.  
3. git branch -d feature-instructions.  
4. git commit -am ""   
--------------------
1. (feature)git  diff master.  
2.  git merge master.  
3.  fix in directory in code.  
4.  git status.  
5.  git diff.  
6. git commit -am "Merge from master".  
--------------------
# (Reset)
1. git reset file namegit reset HEAD.  
2. git reset HEAD~1(to the last commit).  
3. git log.  
4. git reset --hard(save reset version)  (hash).  






