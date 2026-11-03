Error 1:
cd Notes
No such file or directory
Reason 1: Linux is case sensitive
Fix 1: cd notes

Error 2:rm notes
cannot remove 'notes':Is a directory
Reason 2:Deleting a folder needs
Fix 2: rm -r notes

Error 3: unable to push changes
Reason 3: GitHub has changes I don't have.
Fix 3: git pull --rebase (download the commits from GitHub)
git push (then push)
