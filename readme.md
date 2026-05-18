```bash
git config --global user.name "Your Name"
git config --global user.email "your_email@example.com"
```

git rm --cached -r . (Run this command to clear Git's cache and make it scan the folder fresh:)
git rm --cached -r -f . (force it)


git reset --soft HEAD~2 (What this did: It safely removed those two local commits. Your code files are completely safe and still look exactly how they are right now. They are just sitting back in your "Changes" list in VS Code)


# check the size of push
git add .
git commit -m "testing push size"
git push --dry-run --verbose 
