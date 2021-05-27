# LearningGithub

You can use the following git commands to perform several functions:

1. create local repo by using ->  git init
2. connect with remote repo by using -> git remote origin "link here"  or for ssh -> git remote set-url origin git@github.com:username/repo.git
3. you can pull data from remote repo to your local machine folder by using -> git pull origin main
4. To check what new files are available in your local folder that are not committed using -> git status
5. before commit we need to add files in index of git that can be done using -> git add FILENAME  or to add multiple files use -> git add -A
6. now we can commit the newfile in repo by using -> git commit -m "add some information here" or to add multiple files use -> git commit -a -m "Some message"
7. we can see all the changes made in a log by using -> git log
8. we can create branches by using -> git branch BRANCH NAME
9. made new branch to use it use -> git checkout Brachn name
10. to remove conflict open git mergetool  :diffg RE to save :wqa
11. to connect through ssh we need to generate key for the first time for the system using -> ssh-keygen -> enter until key is created
12. add this key in github account and verify it on local machine by writing -> ssh -T git@github.com
13. to push data to github use -> git push origin master
14. to push data to branches use -> git push origin branch name   you must be in that branch to push the data
