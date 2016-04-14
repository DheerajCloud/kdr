# k
Dheeraj@VinRaj MINGW64 ~/Desktop
$ git clone https://github.com/DheerajCloud/kdr.git
Cloning into 'kdr'...
remote: Counting objects: 3, done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
Checking connectivity... done.

Dheeraj@VinRaj MINGW64 ~/Desktop
$ git config user,name
error: key does not contain a section: user,name

Dheeraj@VinRaj MINGW64 ~/Desktop
$ git config user.name

Dheeraj@VinRaj MINGW64 ~/Desktop
$ git config user.email

Dheeraj@VinRaj MINGW64 ~/Desktop
$ git status
fatal: Not a git repository (or any of the parent directories): .git

Dheeraj@VinRaj MINGW64 ~/Desktop
$ cd kdr

Dheeraj@VinRaj MINGW64 ~/Desktop/kdr (master)
$ git status
On branch master
Your branch is up-to-date with 'origin/master'.
nothing to commit, working directory clean

Dheeraj@VinRaj MINGW64 ~/Desktop/kdr (master)
$ touch index.html

Dheeraj@VinRaj MINGW64 ~/Desktop/kdr (master)
$ git status
On branch master
Your branch is up-to-date with 'origin/master'.
Untracked files:
  (use "git add <file>..." to include in what will be committed)

        index.html

nothing added to commit but untracked files present (use "git add" to track)

Dheeraj@VinRaj MINGW64 ~/Desktop/kdr (master)
$ git add index.html

Dheeraj@VinRaj MINGW64 ~/Desktop/kdr (master)
$ git status
On branch master
Your branch is up-to-date with 'origin/master'.
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        new file:   index.html


Dheeraj@VinRaj MINGW64 ~/Desktop/kdr (master)
$ git commit -m "First page"
[master 26aa4cd] First page
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 index.html

Dheeraj@VinRaj MINGW64 ~/Desktop/kdr (master)
$ git log
commit 26aa4cdf0ab51d99eca6e334db87826d007b7cf2
Author: dheeraj kalakonda <dheeraj kalakonda>
Date:   Wed Apr 13 23:54:04 2016 -0500

    First page

commit 2070c79ba893c1879491e2aad8d23cd766d50721
Date:   Wed Apr 13 23:27:54 2016 -0500

    Initial commit

Dheeraj@VinRaj MINGW64 ~/Desktop/kdr (master)
$ git push origin master
Logon failed, use ctrl+c to cancel basic credential prompt.
Username for 'https://github.com/':

Dheeraj@VinRaj MINGW64 ~/Desktop/kdr (master)
$ git push origin master
Counting objects: 3, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 268 bytes | 0 bytes/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/DheerajCloud/kdr.git
   2070c79..26aa4cd  master -> master

Dheeraj@VinRaj MINGW64 ~/Desktop/kdr (master)
$ git pull
remote: Counting objects: 3, done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
From https://github.com/DheerajCloud/kdr
   26aa4cd..0ac1098  master     -> origin/master
Updating 26aa4cd..0ac1098
Fast-forward
 index.html | 1 +
 1 file changed, 1 insertion(+)

Dheeraj@VinRaj MINGW64 ~/Desktop/kdr (master)
$
dr
