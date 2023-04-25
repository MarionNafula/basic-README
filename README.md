# simple CLI command  

below is a list of CLI command that we'll use occassionally

## working with files and folders

```bash

#creating a folder
mkdir <folder-name>

#reating a file
touch <file-name>

# navigating through folders
cd <folder-name>

#going one step behind a folder
cd ..

#navigating back to the root folder
cd ~

#removing files and folders that have no permission
rm<folder/file name>

#removing files and folders that have permission
rm -rf <folder/file name>

#opening a folder on the vs code
code <folder/file/current dir>

#list out all files withing a folder(unhidden)
ls

#list all files within a folder (hidden)
ls -a
```

##Basic git commands

```bash
#initializing the local resipotoryas git resipotory
git init

#add the files in your new local repository
git add .

#checking the status of the local repository
git status

#commiting the file that you have staged in your local repository
git commit -m  "first commit"

#pushing to remote repository
git push -u origin master

#create copy of existing repository
git clone

#delete a branch
git branch -D (branch name)