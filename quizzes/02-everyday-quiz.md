# QUIZ 02 -- Grading Assignment

1. What is a branch?
[ ] Any group of commits could be considered a branch
[ ] A branch is a meaningful selection of commits
[ ] A branch is a history made of several snapshots (commits)
[ ] A branch is the first commit in a repository

2. What does a staged change mean?
[ ] It means the change was added but not commited
[ ] It means the change will not make it to production
[ ] Staged changes mean they are being commited to another branch
[ ] It means the changes were scanned via the command git stage

3. I wrote a small web app and put the code in a Github repository. Do my clients need git to access my app?
[ ] Yes and they are required to have a Github account before accessing your code
[ ] No, they would only need git to make pull requests
[ ] No, they would only need a Github account to make pull requests (they can edit via Github UI)
[ ] No, they would only need ssh keys to see the code

4. What command can be used to combine changes from different branches?
[ ] git branch
[ ] git switch
[ ] git merge
[ ] git init

5. My git push command errored out with the following message "Updates were rejected because the tip of your current branch is behind its remote counterpart". What is happening and how do I fix it?
[ ] The message means your local branch and the remote branch are different and there is no way to fix it
[ ] The message means your commits are dated in the future relative to the server clock. You will need to copy and paste the changes in Github UI.
[ ] The message means the last commit has issues and you should revert it before pushing.
[ ] The message means the local branch has different commits from the remote branch. You should fetch the remote changes, merge it to your local branch then push again.

6. Is it possible to run a command on every file in a directory?
[ ] yes, using ls
[ ] yes, using find
[ ] yes, but only with shell script
[ ] yes, but only on linux

7. What does the command `cat` do?
[ ] it makes cat sounds
[ ] it puts the contents of one or more files into the standard output
[ ] it puts the contets of one file into another
[ ] it labels files into categories

8. What does the 2> operator in shell mean?
[ ] It means to append the output at the end of a file
[ ] It means to put both standard output and standard error in a file
[ ] It means to move all error and warning lines to another file
[ ] It filters output for values greater than 2

9. What is better, to compose commands or to write your own programs?
[ ] You should always compose commands to avoid introducing bugs
[ ] It depends, you should always use custom programs as long as the server has an interpreter for your language
[ ] It depends: custom programs require root to install, while commands can be run by any user
[ ] It depends, if it seems simple commands are ok, but if it gets complex you should switch to custom programs

10. Does the shell remember previous commands?
[ ] Yes, only the last command, accessed by pressing "up" in the keyboard
[ ] No, commands must not be logged for security reasons (what if there is a password in the command?)
[ ] Yes, there is infinite history if you keep pressing "up" or you can search via "ctrl+R"
[x] It is configurable, it will remember a few by default. You can also define some sensitive commands to never be remembered.