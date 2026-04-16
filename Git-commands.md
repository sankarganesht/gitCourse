**>git**

All possible git commands

\################################################################################################################################################

**>git clone https://github.com/sankarganesht/gitCourse.git**

Creates a local folder same name as remote project. It also initiates Git in that folder and downloads the current state of the remote on our local machine. So, now our local project is linked to the remote project.

\################################################################################################################################################

**>git remote -v**

Git will print out for us the remote repository link. Two links, one for fetch and one for push.

origin  https://github.com/sankarganesht/gitCourse.git (fetch)

origin  https://github.com/sankarganesht/gitCourse.git (push)

\################################################################################################################################################

Adding a parameter -h to the end of a git command will display the available parameters.

**>git clone -h**

**>git remote -h**

\################################################################################################################################################

**>git add Git-commands.txt**

Adds the mentioned file that has been changed to the staging area

>git commit -m "Sankar documenting all git commands from the tutorial"

A commit is a set of saved repository changes. 

A commit is never lost.

Each commit has a unique identification hashkey

Creates a new commit with the mentioned comments

\################################################################################################################################################

**>git log**

This command shows the list of the commits in our project.

\################################################################################################################################################

**>git status**

We will see the difference between the stage files that appear under the heading changes to be committed and the unstage files that appear under the heading untracked files.

\################################################################################################################################################

**>git reset Git-commands.txt**

Used to remove the files from staging and mark it as untracked.

\################################################################################################################################################

**>git branch**

List all available branches in the project. The current active branch is highlighted in Green with a *

\################################################################################################################################################

**>git branch featureBranch**

Create a new branch

\################################################################################################################################################

>git checkout featureBranch

This command is to change to another branch

\################################################################################################################################################

>git show <commit hash>

This command gives us all the changes to all the files that happened in that commit including new file creations and name changes in our project.

>git show --name-only <commit hash>
It shows file names only (shorthand information about a commit)

\################################################################################################################################################

>git reflog

This is a powerful command because it gives us information about all the changes that happened on the project, including all commits on all branches.

\################################################################################################################################################

>git push

Git push sends all our local changes to the GitHub repository.

\################################################################################################################################################

>git clone https://github.com/sankarganesht/gitCourse.git newRepository

A repository is simply a folder that git tracks, so we can have as many folders as we like pointing to the same project. They are independent.

\################################################################################################################################################

>git push

Push all the files to Git repository


\################################################################################################################################################

>git pull

Pull all the files from Git repository

\################################################################################################################################################

>git revert 583c9359151b9a9fafc44ad642eeb74f0d0157b2

Revert the changes of the mentioned hash commit

\################################################################################################################################################



\################################################################################################################################################


\################################################################################################################################################


\################################################################################################################################################


\################################################################################################################################################