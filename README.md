# gitsandbox
Playground for trying out various git commands in a safe environment :)

Change this file on the remote to test out various `git fetch` commands.

Change this file on local repo. Next up, change the file on the remote repo and see what pull/rebase does.

Changing this file on the remote/origin to see what a pull/rebase does when a change is also made to this file on 
a local branch. 

On the rebase mentioned in the 2 previous paragraphs kdiff3 messed up the subsequent merge. It would only allow
either line 6 or line 8 to be in the merge, not both. Line 9 was unaffected. A text based merge allowed for the
correct merge although I did have to change the ordering of the lines to get them to be as seen above. The
merge markers showed the lines in the opposite order.