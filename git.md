learning git commands

git config --global user.eamil "m@gmail.com"
git config --global user.name "mncj"

to ways to start git
git init
or
git clone

create a folder and in that foldr run  git init
then check
ls -la
ls -l.git/

outside the git directorywe have working tree
in this area created a file or copied file
cp ../disk_uasge.py .
ls -l

git add disk_usage.py  (file added to staging area and (to get it tracked))

git status
git commit  (to get commited into the git directory)    from here write commit message and exit also save (merge commit)
