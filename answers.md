1. What command do you use to setup a git repository inside of your folder?
git init
2. What command do you use to ask git to start tracking a file?
git add <filename>
3. What command do you use to ask git to move your file from the staging area to the repository?
git commit -m "description of changes"
4. What command do you use to get updates from a remote repository?
git clone <github url>
5. What command do you use to send your work to a remote repository?
git push origin master

1. What command do you use to unstage a file?
git reset -- filename
2. What command do you use to change your files back to how they were after a commit?
git revert HEAD
3. Why is it important to use `--` when chaging files back to a previous state? For example, in the command `git checkout 123482 -- index.html`
It specifies which file to change, rather than changing every file in the directory.
4. Why might you want to reset your files back to a previous commit?
Often times there will be mistakes within the file spotted after committment. Resetting the files may remove your most recent progress, but it will restore the previous commit, allowing you to correct the file.