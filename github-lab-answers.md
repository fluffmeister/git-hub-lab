What command do you use to setup a git repository inside of your folder?
git init
What command do you use to ask git to start tracking a file?
git add 
What command do you use to ask git to move your file from the staging area to the repository?
git commit -m "description"

What command do you use to pull any changes from the master repository into your local repository?
git pull origin master
What command do you use to unstage a file?
git reset [file]
What command do you use to change your files back to how they were after a commit?
git reset --hard [commit]
Why is it important to use -- when changing files back to a previous state?
to define 
Why might you want to reset your files back to a previous commit?
if there was a mistake in the file

What command do you use to create a branch?
git branch [branch-name]
What command do you use to use a different branch?
git checkout[branch-name]
Why would you want to use a branch other than the default master?
master is reserved for finished working files that people will pull from
Give an example for when you would use git merge and give an example for when it would be better to submit a pull request to have your branch merged.
when your file is ready to be merged into the master branch. when your file needs to be updated.

What command do you use to send all of the work that you've done locally to your remote repository?
$ git push [remote] [branch]

