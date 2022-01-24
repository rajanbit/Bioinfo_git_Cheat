# Bioinfo_git_Cheat
Git cheat for bioinformatics

Configuring git username and email
```
$ git config --global user.name <username>
$ git config --global user.email <email>
```

Clone repository
```
$ git clone https://github.com/rajanbit/Bioinfo_git_Cheat.git
```

State of the working repository and staging area
```
$ git status
```

Add new or changed files in current repository to git staging area
```
$ git add .
```

Capture snapshot
```
$ git commit -m "my first commit with command line"
```

Renames the master branch(create locally) to main
```
$ git branch -M main
```

Set a new remote
```
git remote add origin https://github.com/rajanbit/Bioinfo_git_Cheat.git
```

Push changes into github repository
```
git push -u origin main
```

