# Learning Git and Github

- [Learning Git and Github](#learning-git-and-github)
  - [Initial Setup](#initial-setup)
  - [Basic Workflow](#basic-workflow)
  - [Other Commands](#other-commands)
  - [Tutorials and References](#tutorials-and-references)

## Initial Setup

1. Initialise Folder as Repository and add all files to Repository
```
git init
git add .
```

2. Add GitHub Repositoory
```
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY-NAME.git
```

3. Commit
```
git commit -m "commit description/message"
```


4. Set Upstream and Push changes to GitHub
```
git push --set-upstream origin main
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

## Other Commands

1. Cloning a repository 
```
git clone https://github.com/owner/repo.git
```

2. Creating and switching to a branch
```
git branch my-branch
git checkout my-branch
```

## Tutorials and References 

[Generate SSH Key](https://medium.com/@kiran.jasvanee/the-process-to-generate-ssh-key-and-add-it-on-github-ba7139c07daf)

[Setup SSH Key with Github](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

[YouTube Tutorial - freeCodeCamp.org](https://www.youtube.com/watch?v=RGOj5yH7evk&t=1900s)

[Github Docs](https://docs.github.com/en/get-started/using-git/about-git)

[Github Docs Advanced](https://githubtraining.github.io/training-manual/#/01_getting_ready_for_class)

[Cheatsheet](https://training.github.com/downloads/github-git-cheat-sheet/)

[README Styling Docs](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

