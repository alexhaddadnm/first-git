# first-git
first github repository 

1. update local Git user.name and user.email
$ git config --global user.name "alexhaddadnm"
$ git config --global user.email "alexhaddadnm@gmail.com"
$ git config --global --list
user.name=alexhaddadnm
user.email=alexhaddadnm@gmail.com

2. clone repository
$ git clone <paste repo url here>
  
3. notice new dir in parent? cd to new dir and check status
$ git status

-- i had updated README.md on GitHub. figured there must be a command to get my local copy updated... there is, 

$ git pull
one file updated 
$ git status :)

4. Add or edit some stuff
$ echo "<text here>" >> <filename.txt>
$ vi OR cat <filename.txt>

5. status shows "stuff" is not up to date, git add to put "stuff" in staging
$ git add <filename.txt>

6. now put "stuff" in staging into local repository
$ git commit -m "<commit note>

7. now push to master branch in server repository
$ git push origin master





