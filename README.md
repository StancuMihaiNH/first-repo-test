# CHAPTER 1: How to push local changes to git server #  

Please read the file below for instructions!

1. git add.
2. git commit -m "Message for commit"
3. git push

For any erros, please review the steps below!

# CHAPTER 2: How to track local commit that have not yet been pushed #

**Shows log of commits ahead of origin/main**

git log origin/main..HEAD

**Shows status, indicating if you are ahead**

git status

**Shows diff summary of what's ahead of origin/main**

git diff --stat origin/main

**Lists commits that are not in origin/main**

git cherry -v origin/main

By using these commands, you can effectively track and review your local commits that have not yet been pushed to the remote server, ensuring that you are fully aware of the changes that will be transferred during your next push.