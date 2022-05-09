felic@LAPTOP-HUB0AQ1B MINGW64 ~/OneDrive/Desktop/Ironferdi (main)
$ git checkout -b classmate
Switched to a new branch 'classmate'

felic@LAPTOP-HUB0AQ1B MINGW64 ~/OneDrive/Desktop/Ironferdi (classmate)
$ touch felicia.txt

felic@LAPTOP-HUB0AQ1B MINGW64 ~/OneDrive/Desktop/Ironferdi (classmate)
$ echo " I enrolled Ironhack's Data analytics bootcamp because i need to find a job soon" > felicia.txt

felic@LAPTOP-HUB0AQ1B MINGW64 ~/OneDrive/Desktop/Ironferdi (classmate)
$ git add .
warning: LF will be replaced by CRLF in felicia.txt.
The file will have its original line endings in your working directory

felic@LAPTOP-HUB0AQ1B MINGW64 ~/OneDrive/Desktop/Ironferdi (classmate)
$ git commit -m "my new branch"
[classmate 4cbe622] my new branch
 1 file changed, 1 insertion(+)
 create mode 100644 felicia.txt

felic@LAPTOP-HUB0AQ1B MINGW64 ~/OneDrive/Desktop/Ironferdi (classmate)
$ git add felicia.txt

felic@LAPTOP-HUB0AQ1B MINGW64 ~/OneDrive/Desktop/Ironferdi (classmate)
$ git commit -m "my new branch"
On branch classmate
nothing to commit, working tree clean

felic@LAPTOP-HUB0AQ1B MINGW64 ~/OneDrive/Desktop/Ironferdi (classmate)
$  git remote add origin
usage: git remote add [<options>] <name> <url>

    -f, --fetch           fetch the remote branches
    --tags                import all tags and associated objects when fetching
                          or do not fetch any tag at all (--no-tags)
    -t, --track <branch>  branch(es) to track
    -m, --master <branch>
                          master branch
    --mirror[=(push|fetch)]
                          set up remote as a mirror to push to or fetch from


felic@LAPTOP-HUB0AQ1B MINGW64 ~/OneDrive/Desktop/Ironferdi (classmate)
$  git push -u
fatal: The current branch classmate has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin classmate


felic@LAPTOP-HUB0AQ1B MINGW64 ~/OneDrive/Desktop/Ironferdi (classmate)
$ git push --set-upstream origin classmate
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 355 bytes | 355.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'classmate' on GitHub by visiting:
remote:      https://github.com/Leecia-2864/Ironferdi/pull/new/classmate
remote:
To https://github.com/Leecia-2864/Ironferdi.git
 * [new branch]      classmate -> classmate
branch 'classmate' set up to track 'origin/classmate'.

felic@LAPTOP-HUB0AQ1B MINGW64 ~/OneDrive/Desktop/Ironferdi (classmate)
