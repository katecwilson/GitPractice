#Git Cheatsheet  
**Name:** Kate Wilson   
**Date:** January 17, 2017  
Git Hub keeps track of versions, enabling sharing  
GET READY 
git config --global user.name "[name]
git config --global user.email "[email address]
git config --list  SHOW ALL INFO TO CHECK
git init  CREATE "REPOSITORY" ON YOUR MACHINE (NOT YET LINKED)
git remote add origin [URL of your remote repo]
git remote -v
git status   LISTS NEW THINGS (FILES OR CHANGES) NOT YET COMMITTED
git log
git add [filename]  SHELVES "SNAPSHOT" VERSION AWAITING COMMIT; DUBBED "STAGE"
git add .   (NO FILENAME)  ADDS ALL RECENT CHANGES 
git commit -m "[clear message describing the changes you made]"  DECIDED, DONE VERSION (BUT NOT YET SHARED) WRITE LABEL OF YOUR LAST ACTION
git push origin master  PUSH = SYNC, DELIVER TO HUB, SHARED 
git reset UN-ADDS/CHANGE 