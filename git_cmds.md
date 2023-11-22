git init
 - Initializes an empty git repo

git checkout -b <branch name>
 - Switching to new branch, if you want to state of the git repo

git add <fileName>
 - adds a change in the working directory to the staging area

 git commit -m "<Some Message>"
  - Use to track staged file after being add
  - commits keep track of our progress and changes as we   work. Git considers each commit change point or "save    point". It is a point in the project you can go back to if you find a bug, or want to make a change.

git restore and git restore --staged <filename>
 - Use to untrack/unstage the statge file

git log
  - show the commit history for the currently active branch.

git reset (Use for localhost machine like if u are working on ur own project)
 - git reset is a simple way to undo changes that haven’t been shared with anyone else. It’s your go-to  command when you’ve started working on a feature and find yourself thinking, “Oh crap, what am I doing? I should just start over.” 

git revert (use in production like when team are working on same prject)
  - Git revert is similar to git reset, but the approach is slightly different. Instead of removing all the commits in its way, the revert ONLY undoes a single commit by taking you back to the staged files before the commit.

git branch
 - Gives the list  of all the branches in git currently present

git push
 - It will help to transfer your code from local machine to remote machine(GitHub).

git pull
 - It will update your current master/head/main branch with the leatest change from remote. It will not effect the other branch which you create to change to update or modify the code.

git clone
 - The git clone command is used to create a copy of a specific repository or branch within a repository.

git diff
 - diff of what is changed but not staged

git diff --staged
 - diff of what is staged but not yet commited

git remote add
 - Use the git remote add command to add a new remote with a name and a URL.

git merge
 -Git marge will help to combine the changes from two or more branches into a single branch. Developers will work on different branches to improve code or to develop the code after completion we can merge them into a single version of the code.

git rebase
 - The git rebase command allows you to easily change a series of commits, modifying the history of your repository. You can reorder, edit, or squash commits together.
  - Edit previous commit messages
  - Combine multiple commits into one
  - Delete or revert commits that are no longer necessary

git cherry-pick
 - With the "cherry-pick" command, Git allows you to integrate selected, individual commits from any branch into your current HEAD branch.

 - Contrast this with the way commit integration normally works in Git: when performing a Merge or Rebase, all commits from one branch are integrated.

clone vs fork ?
 - You want to work on a personal project that is based on an existing repository.
   You would use git clone to clone the repository to your local machine, and then you would make your changes.
   You want to contribute to an open source project.
   You would use git fork to create a copy of the repository on your GitHub account. You would then make your changes to your copy, and you would submit a pull request to the original repository.
   You want to create a backup of a repository.
  You would use git clone to clone the repository to your local machine. You would then store the cloned repository on a safe location, such as an external hard drive or a cloud storage service.

Diff b/w cherry-pick vs merge vs rebase ******





 
