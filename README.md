# Learning Git and Github

- [Learning Git and Github](#learning-git-and-github)
  - [Initial Setup](#initial-setup)
  - [Basic Workflow](#basic-workflow)
  - [Branching](#branching)
  - [Other Commands](#other-commands)
  - [Tutorials and References](#tutorials-and-references)

## Initial Setup

1. Initialise Folder as Repository and add all files to Repository
```
git init
git add .
```

2. Add GitHub Repository
```
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY-NAME.git
```

3. Commit
```
git commit -m "commit description/message"
```


4. Set Upstream and Push changes to GitHub
```
git push --set-upstream origin main // Or other branch instead of main
OR
git push -u origin main
```

## Basic Workflow

1. Add all changes and commit
```
git commit -a -m "commit description/message"
```

2. Push Changes to Github (when upstream is already set)
```
git push
```

## Branching

1. Creating and switching to a branch
```
git branch my-branch
git checkout my-branch
OR
git checkout -b my-branch // Create as well as checkout 
```

2. Finding Difference between current branch and other branch
```
git diff branch-name
```

3. Merge another branch into current branch
```
git checkout current-branch
git merge other-branch
```

4. Delete a branch
```
git branch -d branch-name
```


## Other Commands

1. Cloning a repository 
```
git clone https://github.com/owner/repo.git
```

2. Pull from Github to local repository
```
git pull --set-upstream origin main 
OR
git pull -u origin main
```

3. Unstage Previous Commit
```
git reset 
OR
git reset file-name // To unstage a particular file
```

4. Revert Back to Previous Commit
```
git reset --hard HEAD~1 // --hard will change local files too
OR
git reset --hard <sha1-commit-id>

THEN 
git push 
OR
git push origin HEAD --force (If commit is already pushed)
```

5. See list of commits
```
git log
```

## Tutorials and References 

[Generate SSH Key](https://medium.com/@kiran.jasvanee/the-process-to-generate-ssh-key-and-add-it-on-github-ba7139c07daf)

[Setup SSH Key with Github](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

[YouTube Tutorial - freeCodeCamp.org](https://www.youtube.com/watch?v=RGOj5yH7evk&t=1900s)

[Github Docs](https://docs.github.com/en/get-started/using-git/about-git)

[Github Docs Advanced](https://githubtraining.github.io/training-manual/#/01_getting_ready_for_class)

[Cheatsheet](https://training.github.com/downloads/github-git-cheat-sheet/)

[README Styling Docs](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

