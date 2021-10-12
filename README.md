# Deletion-Git

Steps to delete a file in a local repository with Git-

```

1. Checking the list of files in the repository
$ git ls-files

2. Removing a file from the repository
$ rm <YourFileName>

3. Check the list of files again. 
$ git ls-files

4. Executing git status, where you will notice that the removal of the file is still in staging and needs to be committed to the repository

5. Commit the changes
$ git add .
$ git commit -m “Removed file name”

6. Check the log
$ git log --oneline

```
