# text.txt
one
two
PS C:\Users\sindh\pav> git remote add pav https://github.com/Nigamak/pav.git
PS C:\Users\sindh\pav> git pull project-1 main
fatal: 'project-1' does not appear to be a git repository
fatal: Could not read from remote repository.
Please make sure you have the correct access rights
and the repository exists.
PS C:\Users\sindh\pav> git pull pav main
remote: Enumerating objects: 4, done.
remote: Counting objects: 100% (4/4), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 934 bytes | 133.00 KiB/s, done.
From https://github.com/Nigamak/pav
* branch
main
-> FETCH_HEAD
* [new branch] main
-> pav/main
Updating f1bab64..34faa98
Fast-forward
project-1 | 1+
1 file changed, 1 insertion(+)
create mode 100644 project-1
PS C:\Users\sindh\pav> git checkout -b saturn
Switched to a new branch 'saturn'
PS C:\Users\sindh\pav> git push origin saturn
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'saturn' on GitHub by visiting:
remote: https://github.com/Nigamak/pav/pull/new/saturn
remote:
To https://github.com/Nigamak/pav.git
* [new branch] saturn -> saturn
PS C:\Users\sindh\pav> git checkout saturn
Already on 'saturn'
PS C:\Users\sindh\pav> git add new
fatal: pathspec 'new' did not match any files PS C:\Users\sindh\pav> git add project-1
On branch saturn
PS C:\Users\sindh\pav> git commit -m "yes its added

On branch saturn
nothing to commit, working tree clean
PS C:\Users\sindh\pav> git status
On branch saturn
nothing to commit, working tree clean
PS C:\Users\sindh\pav> git commit -am "yess"
On branch saturn
nothing to commit, working tree clean
PS C:\Users\sindh\pav> git status
On branch saturn
nothing to commit, working tree clean
PS C:\Users\sindh\pav> git push origin saturn
Everything up-to-date
PS C:\Users\sindh\pav> git merge saturn stars
merge: stars not something we can merge
PS C:\Users\sindh\pav> git merge saturn main
Already up to date.
PS C:\Users\sindh\pav> git clone https://github.com/Nigamak/new_fork.git
Cloning into 'new_fork'
remote: Enumerating objects: 9, done.
remote: Counting objects: 100% (9/9), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 9 (delta 0), reused 9 (delta 0), pack-reused 0
Receiving objects: 100% (9/9), done.
PS C:\Users\sindh\pav> git pull From https://github.com/Nigamak/pav
f1bab64..34faa98
main
->
origin/main
[new branch]
stars
->
* There is no tracking information for the current branch.
origin/stars
Please specify which branch you want to merge with.
See git-pull(1) for details.
git pull <remote> <branch>
If you wish to set tracking information for this branch you can do so with:
git branch --set-upstream-to=<remote>/<branch> saturn
PS C:\Users\sindh\pav> cd new_fork
PS C:\Users\sindh\pav\new_fork> git pull
Already up to date.
