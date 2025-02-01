# Git Cheat codes
1. Initializing git inside a directory
```
git init
```

2. Checking for staged files
```
git status
```

3. Staging files and folders
```
git add . # Adds all the files in the current directory
git add folder_name/ file_name   # To add folder and file
```

4. Commiting staged files
```
git commit -m "commit_message"
```

5. Checking commit history
```
git log
git log --all --graph
```

6. Pushing to github
```
git remote add origin <repository_url> #connecting repo
git branch -M main   #renaming branch name if first time
git push -u origin main
```

7. Check the Current Remote URL
```
git remote -v
```

8. Remove the Existing Remote origin
```
git remote remove origin
```

9. Update Remote Without Removing
```
git remote set-url origin <new_repository_URL>

```