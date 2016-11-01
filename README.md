# Terminal Commands used so far:
* cd into the appropriate directory where we wanted to store the repo
* typed ls -la verify no .git folder exists to make sure the directory was not already a git directory
* git clone https://github.com/jdubz1982/git_test.git
* ls again to see the folder and use cd to navigate into the folder
* touch awesome_page.md to create file in repo folder
* git status to check status of new files
* git add awesome_page.md to stage the new file
* git commit -m "Initial commit" to commit the file or create a save point for the branch
* git push origin/master - local master branch will be pushed to the master branch of the remote origin
* git checkout -b add-command-log - we created a new branch and checkout it out or switched to the new the branch.
* feature branches are useful because developers can create separate lines of code and test them out in isolation without messing with the master branch. The master branch should contain stable code. Once the new feature has been tested and peer reviewed, it can be merged properly into the master branch. 
* The three stages of a git change are untracked, modified, and staged. Untracked files are new files that are not being tracked. Modified files are tracked but they have been modified since the last commit. Staged files are those files ready to be committed. To move out of the untracked stage, you must git add the file and then git commit with an initial commit message. To move from modified to staged, you must add the file with git add. Once the files are staged, they are ready to be committed with a git commit and good commit message. 
* A commit is snapshot in time or a save point of a project. A good commit message is detailed and states what was changed since the last commit. Typically, it is standard to summarize the entire commit on the first line in less than 50 characters, leave a blank line, then add a detailed explanation of what has been changed.  