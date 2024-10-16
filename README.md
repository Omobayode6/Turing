# Turing

##GIT
1.  How can you see all local branches with merged work? => **git branch --merged** | git branch --merged main
2.  Which command can you use to discard changes to a file inside a git repository? => **git checkout -- <filename>** | git restore <filename>
3. which of the follows are true about tags in git? => **D**
  A. branches contain full copies of the files in their histories
  B. Tags can only point to a branch
  C. Tags cannot be pushed to a remote
  D. Tags cannot be moved and can be cryptographically signed => **True**
  E. None of the above
4. When is it neccesary to use git mv for moving a file? => It simplifies the process of moving/renaming and staging the change in one command.
5. In Gitflow, the following branch types are part of the standard workflow => **Main/Master branch, Develop branch, Feature branches, Release branches, Hotfix branches**
6. which command can be used to configure vimdiff and the default diff tool for git  => **git config --global diff.tool vimdiff**
7. how can you stash your changes interactively? => **git stash push -p | git stash save -p**
8. when do you use git rebase instead of git merged? => **Use git rebase when you want a clean, linear history and want to avoid merge commits.**
9. which of the following is not a git configuration scope => **User** While Global, Local and System are valide configuration scope
10. How can you replace several commits with one? => **squashing using interactive rebase eg git rebase -i HEAD~3**
11. which character append at the end of a commit reference points to the parent of that commit? **^**
