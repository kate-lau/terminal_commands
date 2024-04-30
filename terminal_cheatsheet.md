# Terminal Commands List
| COMMAND | RESULT |
| -------------- | -------------- |
| **pwd** | Shows where you are located. |
| **cd (folder name)** | Go to Folder. |
| **mkdir (folder name)** | Creates new folder. |
| **touch (file name)** | Creates new file. |
|**mv (file name) (location/new file name)** | Moves File to new Location, or renames File.
| **rm (file name)** | Deletes File. |
| **rm -r (folder name)** | Deletes Folder. |
| **cp (file name) (location)** | Copies File to Location. |
| **cp -r (folder name) (location)** | Copies Folder to Location. |

### Git Specific Commands

| COMMAND | RESULT | NOTES
| -------------- | -------------- | -------------- |
| **git init** | Creates new Git repository. |
| **git remote add origin git@github.com:(git username)/(repo name)** | Setting which repo teh code will be pushed to. | *E.g. git remote add origin git@github.com:kate-lau/terminal_commands.git*
| **git push origin (branch name)** | Setting which specific branch in the repository the code is being sent to. | E.g. *git push origin main* |
| **git status** | Check for tracked/untracked files. |
| **git add (file name)** | Puts File in staging area ready to be committed. |
| **git add .** | Adds all new changes to staging are ready to commit. Step 1 after any changes to a file. |
| **git commit -m '(message to describe change)'** | Commits change to Git. Step 2 after any changes to a file.| Message should be an imperative, this commit will _. *E.g. git commit -m 'add facts.txt file'* |
|**git push** | Pushes all committed changes to Git. Step 3 after any changes to a file. |
|**git log** | Shows all commits. | A revert will show as a new commit. |