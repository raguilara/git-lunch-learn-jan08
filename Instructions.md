# Add your name to the Onboarding Guest Book

## 1. Clone onboarding repository to your local machine
`$ git clone https://github.com/jonasrk/git-lunch-learn-jan08`

## 2. Edit the README file and add your name to the guest book 
```
$ cd git-lunch-learn-jan08 
$ gedit README.md
```
`gedit` is just a text editor. You can use any of your choice. Remember to save your changes.

## 3. Stage the README update

It's always helpful to first check out the status of the repository before selectively staging the hunks. 

```$ git status
$ git add -p
```
## 4. Commit the staged modifications

**Best Practice**: Write clear commit message. First line should be short, other lines, if necessary, can be as large as needed.
```$ git commit -m "Adds jonaskemper to Onboarding Guest Book."```

## 5. Publish your signature on our shared remote repository 

**Best Practice**: First checkout a branch. Don't push master.
```
$ git checkout -b 20200108-jonaskemper
$ git push 
$ git push --set-upstream origin 20200108-jonaskemper
```

## 6. Do a Pull Request on GitHub
Go to GitHub > switch to your branch > Compare and Pull request > Write pull request (Why you want to merge and @who should review it)
