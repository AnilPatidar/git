# git
All About Git Commands


#----------Trick 1-------------#

How to remove stagged file which was added using add add file.txt command.

Step 1: check if it is already stagged by - 
git status

Step 2: check all the stagged files using
git -ls-fiiles -s

It should show all the staged files

Step 3: remove file from stagging area and put it in untrack files 

git rm --cached file.txt

#----------Trick 2-------------#



