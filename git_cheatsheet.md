All the git commands I can remember

git init : creates a new local repo
git status : tells you if local matches repo or not
git add : adds any modifications to the local repo
git commit : commits added modifications to local repo
git push : pushes committed file to remote repo
git checkout : allows you to move among repo branches
git branch : creates a branch copy of the master

Yeah. It's a start.
#This is a modification to test working with development branch

Git & Github (Day 2 Notes on Git)

•	Git is version control
•	Github facilitates organization of version control. It is a hosting service. There are others that do the same thing,  Github is just the most commonly used.
•	Github also allows a forum for sharing and collaborating on files/versions
•	Local: on my computer only
•	Remote: stored somewhere for archiving or sharing
•	Should I change my github config so that I don’t have to enter my username and password with every commit? 
•	Git status shows whether current version is committed or not
•	Git diff shows difference between current and most recently committed
•	I missed the ‘master’ part in terminal commands – is this why I can’t see additional commits? (After pushing a new commit, only one remains listed on github)
•	If you clone a file, you copy it from remote (github) to local (your own machine) to peruse and modify as you wish
•	Git branch. The master branch should be the one that is working as desired and is used live. If you want to play with the master, you make a branch from it and when you want any changes to be part of the live/master version, you merge it into the master, but not until you know it works the way you want without bugs
•	Git checkout… allows you to move among branches
•	Instead of clone to desktop (an option for cloning on github), paste the link for the file into the terminal in order to add the file to the exact directory you want it in.
