Step 1 : Forked it on github page, seems much easier
git clone https://github.com/kedWHH/Git-Task-1 #Actually used my private key to get it, but same thing
git branch -M master

So we made a new branch master on our git

Step 2 : 
echo "30/7/24" | tee Kedar-Sivaramakrishnan.txt
git add Kedar-Sivaramakrishnan.txt
git commit -m "30/7/24"

We made an initial commit, but still not fully sent over the data

Step 3 : 
git branch -M Kedar-Sivaramakrishnan

made a new branch w my name and switched over to it

Step 4 :
nano abtMe.md
git add abtMe.md

added file abtMe to name branch

Step 5 : 
git log
git commit -m "jeje"

Used git log to find old commit info

Step 6 :
git branch master
git merge Kedar-Sivaramakrishnan

switched to master and merged the two branches

Step 7 : 
git reset HEAD README.md

moved head back, hence "undoing" the change to the data

Step 8 :
git add commands.md

added this file to git

Step 9 : 
git push -u origin master 

Finally sent over all the files to master branch, updated on the web
