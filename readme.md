``` python
D:\git\MyDoc\Scripts>git init
Initialized empty Git repository in D:/git/MyDoc/Scripts/.git/

D:\git\MyDoc\Scripts>git add -A
warning: in the working copy of 'این طوری نرو.md', LF will be replaced by CRLF the next time Git touches it

D:\git\MyDoc\Scripts>git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   "\330\247\333\214\331\206 \330\267\331\210\330\261\333\214 \331\206\330\261\331\210.md"


D:\git\MyDoc\Scripts>git commit -m "min"
[master (root-commit) 05a7c0c] min
 1 file changed, 9 insertions(+)
 create mode 100644 "\330\247\333\214\331\206 \330\267\331\210\330\261\333\214 \331\206\330\261\331\210.md"

D:\git\MyDoc\Scripts>git push https://github.com/Babimetro/myscripts.git
fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream https://github.com/Babimetro/myscripts.git master

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


D:\git\MyDoc\Scripts>git push https://github.com/Babimetro/myscripts.git master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 437 bytes | 218.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Babimetro/myscripts.git
 * [new branch]      master -> master


```