# Bioinfo_git_Cheat

Git cheat for bioinformatics

Install Git (if not installed)

Configuring git username and email
```
$ git config --global user.name username
$ git config --global user.email email
```

Clone a repository
```
$ git clone https://github.com/username/repository_name.git
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
$ git remote add origin https://github.com/username/repository_name.git
```

Generate personal access token from github.com
```
Profile photo -> Settings -> Developer settings -> Personal access tokens -> Generate new token -> Name token -> Select expiration time -> Select all the scopes -> Generate token
```
Copy token from clipboard

Push changes into github repository
```
$ git push -u origin main
```
Authentication:- username: github_username; password: personal access token
