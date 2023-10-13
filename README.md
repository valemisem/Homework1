# **Commands for restructuring Git commits**

## 1. git pull and git fetch

![Git pull and fetch both copy changes from a remote GitHub or GitLab repo locally](https://itknowledgeexchange.techtarget.com/coffee-talk/files/2023/05/gf03.gif)

## 1.1 git pull 
- Brings the copy of all the changes from a remote repository and merges them into the current branch
- The local repository is updated directly
- Updates the changes to the local repository immediately

## 1.2. git fetch
- Gives the information of a new change from a remote repository without merging into the current branch
- Review of commits and changes can be done
- No possibility of merge conflicts

## 2. git commit --amend
- Used to modify the most recent commit
- Combines staged changes with the previous commit instead of creating an entirely new commit
- Not just alter the most recent commit, it replaces it entirely
