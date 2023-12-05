# Git Command

- [Initialization](https://github.com/jsmile631/Git-Command#initialization)
- [Common](https://github.com/jsmile631/Git-Command#common)
- [Advanced](https://github.com/jsmile631/Git-Command#advanced)

## Initialization

Use this command at the first time. and don't forget to add  ```.gitignore``` file if your project needs it

1. Add git to your project
```
git init
```
2. Add all your working directory / all changes to git 
```
git add .
```
3. Commit after you create changes / new file or directory
```
git commit -am "your commit mmessage"
```
4. Add your new remote and give name to it. i use origin as name of remote here
```
git remote add origin your_url_remote
```
6. Push all your commit to your remote
```
git push --set-upstream origin master
```
7. Set your new remote as default remote
```
git branch --set-upstream-to origin/master
```
## Common

Most used git command

1. Cheking changes of your project
```
git status
```
2. Add all your changes / new directory / file
```
git add .
```
3. Commit your changes
```
git commit -am "your commit message"
```
4. Pull your team changes to your project
```
git pull
```
5. Push all your commit to your remote
```
git push
```

## Advanced

1. List all remotoes 
```
git remote -v
```
2. Show remote information with [name] is remote name
```
git remote show [name]
```
3. Add new remote, with [name] is remote name and [url] is url remote
```
git remote add [name] [url]
```
4. Set default remote to [remote], with [remote] is remote name
```
git branch --set-upstream-to [remote]/master
```
5. Change push url with [name] is remote name and [url] is url remote
```
git remote set-url --push [name] [url]
```

## Account
1. Change user name
```
git config --global user.name "Your Name"
```
2. Change email
```
git config --global user.email "you@example.com"
```

## Updating .gitignore file

```
git rm -r --cached .
git add .
git commit -m ".gitignore is now working" 
```
