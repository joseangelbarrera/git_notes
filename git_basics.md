# Git Basic Commands

## Init a repository

To initialize to a repository we have to use the command `git init` Then tthis commmand will create hidden `.git` folder into the sub-folder of the project folder.

every commit will have a comment / description (this is for every change). with git log you can show all commints, refers to a time line that match with the branch concept. For the monet we are ging to work in a master branch. The name the repository have is master (this is the principal banch).

`git add` this command is used to include the file into the status of pre commit.

we must do in two steps in order to put the messge can explain why you are commit the file. Also is usefull because the commit provide a unty in the project. Yhis is perfect for big projects, for instance the team can work in a part of the website as 'files structure'.. This is the great reason for the staging.

`git commit` The commit is alwais with comment

in case you not write any message the edit bin open in the screen

`esc + :` or `q!` or `wq!` is the command to exit from the edit program bin


## Track firts changes

First time oru files are *untracked*
To start tracking our foles we have to `commit` them

To `commit` the files we have to do the following...

For instance if we have an index `.html` we can start tracking it by doing...

```git init
git add index.html
git commit -m "first commit```
