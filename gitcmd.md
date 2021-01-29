# merge patch with pull request :

https://github.com/pratyush463/hybridappone.git

Step 1: From your project repository, check out a new branch and test the changes.

>> git checkout -b pratyush463-patch-1 master

>> git pull https://github.com/pratyush463/hybridappone.git patch-1

>> git checkout master

>> git merge --no-ff pratyush463-patch-1

>> git push origin master
