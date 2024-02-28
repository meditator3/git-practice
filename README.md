practice revert and cherry pick

after qwuitting the job file, 
we use git revert on the commit id
and then the file is deleted(after the message telling you that)

but the history remains

next, we decided that we do want to quit-
so we use

git cherry-pick <id of commit> which is the id of the quit txt file

and then the file is back on the menu.

