# Devops_lab
Practicing Git commands Here.
<br>
<b>git config --global user.name "username_here"</b>
<br>
<b>git config --global user.email "useremail_here"</b>
<br><br>
<b>git clone "link goes here"</b>
<br><br>
<b>git status </b>
<br>
==><b>4 types of result</b>
<br>
==><b><i>untracked</i></b>->new files that git doesn't know
<br>
==><b><i>modified-></i></b>changed
<br>
==><b><i>staged</i></b>->file is ready to be committed(only we have added not committed)
<br>
==><b><i>unmodified</i></b>->unchanged(committed)
<br><br>
add==>adds new or changed files in your working directory to the Git staging area.
<br>
<b>git add <-file name-></b>
<br>
<b>git add .</b>(to add all changed files)
<br><br>
commit==>is is the record of change
<br>
<b>git commit -m "some message"<b>
<br><br>
push==>upload local repo content to remote repo
<br>
<b>git push origin main<b>

<br><br>
INIT COMMAND
<br><br>
<b>init<b> - used to create a new repo
<br><br>
<b>git init<b>
<br>
<b>git remote add origin <-link-><b>
<br>
<b>git remote -v<b> ==> to verify remote
<br>
<b>git branch<b> ==> to check branch
<br>
<b>git branch -M main</b> ==> (to rename branch)
<br>
<b>git push origin main<b>
<br>
<b>git push -u  origin main<b> ==> -u means we are setting up upstream which tells that each time we push to main branch only .Every time no need to give origin main thereafter.
<br><br>
Workflow
<br>
Create repo in Github -> clone it to local system -> change -> add ->commit 
<br><br>
<b>Git Branch</b>
<br>
<b>git branch </b> (to check branch)
<br>
<b>git branch -M main</b> (to rename branch)
<br>
<b>git checkout <-branch name-></b>  (to navigate)
<br>
<b>git checkout -b <-new branch name-></b> (to create new branch)
<br>
<b>git branch -d <-branch name-></b> (to delete branch)
<br>
