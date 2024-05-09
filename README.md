# PLPGitAsssign

 I tried to push your changes to the remote repository using **git push origin main**. However, the push was rejected because the remote repository had changes that you didn't have locally.
To resolve the rejection, I pulled changes from the remote repository using **git pull origin main --allow-unrelated-histories.** This command pulls changes even if they diverge from your local history, merging them into your local branch.
During the pull, Git detected that there were unrelated histories between my local and remote branches. It merged the changes, and resolved any merge conflicts that occurred.
After resolving conflicts, I staged all changes using **git add .** indicating that I want to include all modified files in the next commit. Then, committed the changes with **git commit -m "Add hello greetings".**
Finally, you pushed the committed changes to the remote repository again using **git push origin main**. This time, the push was successful because your local branch was up to date with the remote repository, and there were no conflicts.
