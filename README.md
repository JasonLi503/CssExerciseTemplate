# Workflows Course

This project is an example of workflow management for a lynda.com course.

add file .gitignore
.DS_Store
node_modules
.tmp
.sass-cache
builds/**/images/*


install command:

install git
install nodejs
install ruby

sudo gem install sass
sudo gem install compass

 git config branch.non_tracking.remote origin
 git config branch.non_tracking.merge refs/heads/master

 git branch --set-upstream non_tracking origin/non_tracking

git log --oneline
git log -oneline origin master [-n]

git diff origin/master..master

git push  /*for the tracking branch could ignore the rest or fetch operate*/

git log only see local repo, not need access remote repo


git fetch [origin]


git branch -a //to see what to merge

git diff origin/master..master

git merge origin/master
git log --oneline -3 master


