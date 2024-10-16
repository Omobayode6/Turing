# Turing

## GIT
1.  How can you see all local branches with merged work? => **git branch --merged** | git branch --merged main
2.  Which command can you use to discard changes to a file inside a git repository? => **git checkout -- <filename>** | git restore <filename>
3. which of the following are true about tags in git? => **D**
  A. branches contain full copies of the files in their histories
  B. Tags can only point to a branch
  C. Tags cannot be pushed to a remote
  D. Tags cannot be moved and can be cryptographically signed => **True**
  E. None of the above
4. When is it necessary to use git mv for moving a file? => It simplifies the process of moving/renaming and staging the change in one command.
5. In Gitflow, the following branch types are part of the standard workflow => **Main/Master branch, Develop branch, Feature branches, Release branches, Hotfix branches**
6. Which command can be used to configure vimdiff and the default diff tool for git  => **git config --global diff.tool vimdiff**
7. How can you stash your changes interactively? => **git stash push -p | git stash save -p**
8. When do you use git rebase instead of git merged? => **Use git rebase when you want a clean, linear history and want to avoid merge commits.**
9. Which of the following is not a git configuration scope => **User** While Global, Local, and System are valid configuration scope
10. How can you replace several commits with one? => **squashing using interactive rebase eg git rebase -i HEAD~3**
11. Which character append at the end of a commit reference points to the parent of that commit? **^**
12. git pull is a shorthand for which command? => **git pull = git fetch + git merge**
13. Which command can be used to identify all the branches that have been merged into master? => **git branch --merged master**
14. Which of the following commands can be used to delete all files and directories that git does not track from your working directory? => **git clean -fd**
15. after installing git and prior to issuing the first commit, which two configuration properties does the tool expect you to configure? => **username and useremail**
16. Which command can you remove a file from git without removing it from your file system? => **git rm --cached <file> | git reset <file> | git unstage <file>**
17. how can you restore a branch you just deleted? => **Create a new branch on the same commit after looking up the commit hash with reflog git reflog and git checkout -b <branch-name> abc1234**
18. what happens when you run git commit without the -m argument? => **Git will open the default text editor for you to enter a commit message.**
19. Which is the first step in a typical git workflow? => **git init**
20. Which command returns the shortest unique SHA1 for a commit inside the current repository? => **git rev-parse --short <commit>**
21. Which of the following cannot be done with git checkout?? => **Remove a file from the staging area**
22. Which command shows the author for each line of text? => **git blame <filename>**
23. How can you stash your changes, not including anything in the staging area? => **git stash push --keep-index | git stash push -k**

