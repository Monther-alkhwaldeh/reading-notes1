## read 02b
## Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it.


## You can also create a copy of an existing Git repository from a particular server by using the clone command with a repository’s URL:$ git clone https://github.com/test

## Check File StatusTo determine the state of files, utilize the git status command:$ git status
## Tracking and Staging a New File All Files Track all files in a repository by using the following command:$ git add *

## Committing a FileAfter staging one or multiple files, you should commit the changes and record what you did within the commit message:$ git commit -m “made change x,y,z”


