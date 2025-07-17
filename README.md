# Week1

First commit 

These are the commands I would run to make my first commit.


git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/AmandaAzania/week1
git push -u origin main

- git init initiates git on my local
computer,
- git add README.md is a command
  to add the README file to my git hub
- git commit -m is where I would write a
  message, to say what changes I made
- git remote add origin is used to point
  to which location exactly im pushing
  the work 2

GIT REBASE:

Gi rebase lets you rewrite commit history  by moving your changes on top of another branch to make things cleaner and more organised making it easy for code reviewers to review code

Commands:

git rebase -i main:

Opens a list of your commits compared to main so you can edit

git rebase --continue :

Tells git you are done editing or fixing a conflict during rebase


git rebase --abort : 

This will stop the rebase and return the branch to how it was before 

different instructions you can use in each instruction line, especially reword, edit, squash, and fixup: 

Reword: lets you change the commit message but keep the same changes

Edit: this is used to edit the code or the commit message 

Squash : combines the commit message with the one above it, keeping both messages 

Fixup:  Like squash, but discards the commit message and keeps only the first.

Drop: deletes the commit entirely

