
marina.kovacevic@DK-MKO MINGW64 ~
$ git status
fatal: not a git repository (or any of the parent directories): .git

marina.kovacevic@DK-MKO MINGW64 ~
$ git status
fatal: not a git repository (or any of the parent directories): .git

marina.kovacevic@DK-MKO MINGW64 ~
$ pwd
/c/Users/marina.kovacevic

marina.kovacevic@DK-MKO MINGW64 ~
$ cd ..

marina.kovacevic@DK-MKO MINGW64 /c/Users
$ cd Emptydir
bash: cd: Emptydir: No such file or directory

marina.kovacevic@DK-MKO MINGW64 /c/Users
$ ls
'All Users'@  'Default User'@   admin/           desktop.ini
 Default/      Public/          administrator/   marina.kovacevic/

marina.kovacevic@DK-MKO MINGW64 /c/Users
$ cd marina.kovacevic/

marina.kovacevic@DK-MKO MINGW64 ~
$ list
bash: list: command not found

marina.kovacevic@DK-MKO MINGW64 ~
$ ls
'3D Objects'/
 4test.png
 Anwendungsdaten@
 AppData/
'Application Data'/
 Contacts/
 Cookies@
'Creative Cloud Files'/
 Desktop/
 Documents/
 Downloads/
 Druckumgebung@
'Eigene Dateien'@
 Empty/
 Emptydir/
 Favorites/
 Links/
'Lokale Einstellungen'@
 Music/
 NTUSER.DAT
 NTUSER.DAT{b306d550-7061-11ed-a219-047c16633655}.TM.blf
 NTUSER.DAT{b306d550-7061-11ed-a219-047c16633655}.TMContainer00000000000000000001.regtrans-ms
 NTUSER.DAT{b306d550-7061-11ed-a219-047c16633655}.TMContainer00000000000000000002.regtrans-ms
 Netzwerkumgebung@
 OneDrive/
'OneDrive - Blackbird Robotersysteme GmbH'/
 Passwords.kdbx
 Pictures/
 Recent@
'Saved Games'/
 Searches/
 SendTo@
 Simple1/
 Startmenü@
 Videos/
 Vorlagen@
 exercise/
 folder/
 learngit/
 ntuser.dat.LOG1
 ntuser.dat.LOG2
 ntuser.ini

marina.kovacevic@DK-MKO MINGW64 ~
$ git status
fatal: not a git repository (or any of the parent directories): .git

marina.kovacevic@DK-MKO MINGW64 ~
$ git clone https://github.com/platformerin/Simple1
fatal: destination path 'Simple1' already exists and is not an empty directory.

marina.kovacevic@DK-MKO MINGW64 ~
$ git clone https://github.com/platformerin/novirepo1.git
Cloning into 'novirepo1'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.

marina.kovacevic@DK-MKO MINGW64 ~
$ git status
fatal: not a git repository (or any of the parent directories): .git

marina.kovacevic@DK-MKO MINGW64 ~
$ pwd
/c/Users/marina.kovacevic

marina.kovacevic@DK-MKO MINGW64 ~
$ cd novirepo1/

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ mkdir novrepodoc1

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ ls
README.md  novrepodoc1/

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ git add .

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Turn this message off by running
hint: "git config advice.addEmptyPathspec false"

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ git add .

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ git push
Everything up-to-date

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ git ls
git: 'ls' is not a git command. See 'git --help'.

The most similar command is
        lfs

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ ls
README.md  novrepodoc1/

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ ls
README.md  docs.md  novrepodoc1/

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ add .
bash: add: command not found

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ git add .

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   docs.md


marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ git commit .-m "Added dome text"
error: pathspec '.-m' did not match any file(s) known to git
error: pathspec 'Added dome text' did not match any file(s) known to git

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ git commit -m "Added dome text"
[main 3bf3799] Added dome text
 Committer: Marina Kovacevic <marina.kovacevic@blackbird-robotics.de>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly:

    git config --global user.name "Your Name"
    git config --global user.email you@example.com

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 6 insertions(+)
 create mode 100644 docs.md

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ git push origin
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 20 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 399 bytes | 399.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/platformerin/novirepo1.git
   5c1925b..3bf3799  main -> main

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ ls
README.md  docs.md  novrepodoc1/

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ mv docs.md documents.md

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ ls
README.md  documents.md  novrepodoc1/

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    docs.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        documents.md

no changes added to commit (use "git add" and/or "git commit -a")

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ git add .

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ git commit -m "promjena imena u documents.md"
[main 5f3cfb9] promjena imena u documents.md
 Committer: Marina Kovacevic <marina.kovacevic@blackbird-robotics.de>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly:

    git config --global user.name "Your Name"
    git config --global user.email you@example.com

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 0 insertions(+), 0 deletions(-)
 rename docs.md => documents.md (100%)

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ git push origin
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 20 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 295 bytes | 295.00 KiB/s, done.
Total 2 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/platformerin/novirepo1.git
   3bf3799..5f3cfb9  main -> main

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    documents.md

no changes added to commit (use "git add" and/or "git commit -a")

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ git add .

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        deleted:    documents.md


marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ git com^Ct -m "izbrisan documents.md fajl"

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ git commit -m "izbrisan documents.md fajl"
[main 06ce7cc] izbrisan documents.md fajl
 Committer: Marina Kovacevic <marina.kovacevic@blackbird-robotics.de>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly:

    git config --global user.name "Your Name"
    git config --global user.email you@example.com

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 6 deletions(-)
 delete mode 100644 documents.md

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 20 threads
Compressing objects: 100% (1/1), done.
Writing objects: 100% (2/2), 263 bytes | 263.00 KiB/s, done.
Total 2 (delta 0), reused 1 (delta 0), pack-reused 0
To https://github.com/platformerin/novirepo1.git
   5f3cfb9..06ce7cc  main -> main

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ git log --online
fatal: unrecognized argument: --online

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ git log --oneline
06ce7cc (HEAD -> main, origin/main, origin/HEAD) izbrisan documents.md fajl
5f3cfb9 promjena imena u documents.md
3bf3799 Added dome text
5c1925b Initial commit

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ git chekout 3bf3799
git: 'chekout' is not a git command. See 'git --help'.

The most similar command is
        checkout

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ git checkout 3bf3799
git: 'chekcout' is not a git command. See 'git --help'.

The most similar command is
        checkout

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ git checkout 3bf3799
git: 'chekckut' is not a git command. See 'git --help'.

The most similar command is
        checkout

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ git checkout ^[[200~3bf3799~
error: pathspec '?[200~3bf3799~' did not match any file(s) known to git

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ git checkout 3bf3799
Note: switching to '3bf3799'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by switching back to a branch.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -c with the switch command. Example:

  git switch -c <new-branch-name>

Or undo this operation with:

  git switch -

Turn off this advice by setting config variable advice.detachedHead to false

HEAD is now at 3bf3799 Added dome text

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 ((3bf3799...))
$ git checkout master
error: pathspec 'master' did not match any file(s) known to git

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 ((3bf3799...))
$ git checkout master
error: pathspec 'master' did not match any file(s) known to git

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 ((3bf3799...))
$ gi checkout main
bash: gi: command not found

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 ((3bf3799...))
$ git checkout main
Previous HEAD position was 3bf3799 Added dome text
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ git log --oneline
06ce7cc (HEAD -> main, origin/main, origin/HEAD) izbrisan documents.md fajl
5f3cfb9 promjena imena u documents.md
3bf3799 Added dome text
5c1925b Initial commit

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ git checkout 3bf3799
Note: switching to '3bf3799'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by switching back to a branch.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -c with the switch command. Example:

  git switch -c <new-branch-name>

Or undo this operation with:

  git switch -

Turn off this advice by setting config variable advice.detachedHead to false

HEAD is now at 3bf3799 Added dome text

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 ((3bf3799...))
$ ls
README.md  docs.md  novrepodoc1/

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 ((3bf3799...))
$ git tag -a tempTag -m "kAD SAM DODAO NOVI TAG"

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 ((tempTag))
$ git tag
tempTag

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 ((tempTag))
$ git checkout main
Previous HEAD position was 3bf3799 Added dome text
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ ls
README.md  novrepodoc1/

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ git checkout tags/tempTag
Note: switching to 'tags/tempTag'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by switching back to a branch.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -c with the switch command. Example:

  git switch -c <new-branch-name>

Or undo this operation with:

  git switch -

Turn off this advice by setting config variable advice.detachedHead to false

HEAD is now at 3bf3799 Added dome text

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 ((tempTag))
$ ls
README.md  docs.md  novrepodoc1/

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 ((tempTag))
$ git push origin tempTag
Enumerating objects: 1, done.
Counting objects: 100% (1/1), done.
Writing objects: 100% (1/1), 190 bytes | 190.00 KiB/s, done.
Total 1 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/platformerin/novirepo1.git
 * [new tag]         tempTag -> tempTag

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 ((tempTag))
$ git push origin tempTag
Everything up-to-date

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 ((tempTag))
$ pwd
/c/Users/marina.kovacevic/novirepo1

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 ((tempTag))
$ git tag -a mojDrugiTag -m "ide medo u ducan nije reko dobar dan"

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 ((mojDrugiTag))
$ git checkout tags/<mojDrugiTag>
bash: syntax error near unexpected token `newline'

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 ((mojDrugiTag))
$ git checkout tags/<mojDrugiTag>
bash: syntax error near unexpected token `newline'

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 ((mojDrugiTag))
$ git tag
mojDrugiTag
tempTag

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 ((mojDrugiTag))
$ git tag -a mojDrugiTag^Cm "ide medo u ducan nije reko dobar dan"

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 ((mojDrugiTag))
$ git tag
mojDrugiTag
tempTag

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 ((mojDrugiTag))
$ git checkout

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 ((mojDrugiTag))
$ git push origin
fatal: You are not currently on a branch.
To push the history leading to the current (detached HEAD)
state now, use

    git push origin HEAD:<name-of-remote-branch>


marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 ((mojDrugiTag))
$ git log --oneline
3bf3799 (HEAD, tag: tempTag, tag: mojDrugiTag) Added dome text
5c1925b Initial commit

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 ((mojDrugiTag))
$ pwd
/c/Users/marina.kovacevic/novirepo1

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 ((mojDrugiTag))
$ ls
README.md  docs.md  novrepodoc1/

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 ((mojDrugiTag))
$ pwd
/c/Users/marina.kovacevic/novirepo1

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 ((mojDrugiTag))
$ ls
README.md  docs.md  novrepodoc1/  tagiranje.txt

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 ((mojDrugiTag))
$ git add .

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 ((mojDrugiTag))
$ git status
HEAD detached at tempTag
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   tagiranje.txt


marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 ((mojDrugiTag))
$ git push origin
fatal: You are not currently on a branch.
To push the history leading to the current (detached HEAD)
state now, use

    git push origin HEAD:<name-of-remote-branch>


marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 ((mojDrugiTag))
$ git commit tagiranje.txt
Aborting commit due to empty commit message.

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 ((mojDrugiTag))
$ git commit tagiranje.txt -m "kommiting tagiranje"
[detached HEAD abbd10c] kommiting tagiranje
 Committer: Marina Kovacevic <marina.kovacevic@blackbird-robotics.de>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly:

    git config --global user.name "Your Name"
    git config --global user.email you@example.com

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 10 insertions(+)
 create mode 100644 tagiranje.txt

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 ((abbd10c...))
$ git push origin
fatal: You are not currently on a branch.
To push the history leading to the current (detached HEAD)
state now, use

    git push origin HEAD:<name-of-remote-branch>


marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 ((abbd10c...))
$ git checkout main
Warning: you are leaving 1 commit behind, not connected to
any of your branches:

  abbd10c kommiting tagiranje

If you want to keep it by creating a new branch, this may be a good time
to do so with:

 git branch <new-branch-name> abbd10c

Switched to branch 'main'
Your branch is up to date with 'origin/main'.

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ ls
README.md  novrepodoc1/

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ git tag
mojDrugiTag
tempTag

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ git checkout tag
error: pathspec 'tag' did not match any file(s) known to git

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ git checkout tags/mojDrugiTag
Note: switching to 'tags/mojDrugiTag'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by switching back to a branch.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -c with the switch command. Example:

  git switch -c <new-branch-name>

Or undo this operation with:

  git switch -

Turn off this advice by setting config variable advice.detachedHead to false

HEAD is now at 3bf3799 Added dome text

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 ((mojDrugiTag))
$ ls
README.md  docs.md  novrepodoc1/

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 ((mojDrugiTag))
$ git log --oneline
3bf3799 (HEAD, tag: tempTag, tag: mojDrugiTag) Added dome text
5c1925b Initial commit

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 ((mojDrugiTag))
$ git checkout 3bf3799
HEAD is now at 3bf3799 Added dome text

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 ((mojDrugiTag))
$ ls
README.md  docs.md  novrepodoc1/

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 ((mojDrugiTag))
$ git tag
mojDrugiTag
tempTag

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 ((mojDrugiTag))
$ git checkout main
Previous HEAD position was 3bf3799 Added dome text
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ ls
README.md  novrepodoc1/

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ git checkout tags/<mojDrugiTag>
bash: syntax error near unexpected token `newline'

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ git checkout tags/<mojDrugiTag >
bash: syntax error near unexpected token `newline'

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ ls
README.md  novrepodoc1/

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ ^C

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 (main)
$ git checkout tags/mojDrugiTag
Note: switching to 'tags/mojDrugiTag'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by switching back to a branch.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -c with the switch command. Example:

  git switch -c <new-branch-name>

Or undo this operation with:

  git switch -

Turn off this advice by setting config variable advice.detachedHead to false

HEAD is now at 3bf3799 Added dome text

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 ((mojDrugiTag))
$ ls
README.md  docs.md  novrepodoc1/

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 ((mojDrugiTag))
$ git push origin mojDrugiTag
Enumerating objects: 1, done.
Counting objects: 100% (1/1), done.
Writing objects: 100% (1/1), 198 bytes | 198.00 KiB/s, done.
Total 1 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/platformerin/novirepo1.git
 * [new tag]         mojDrugiTag -> mojDrugiTag

marina.kovacevic@DK-MKO MINGW64 ~/novirepo1 ((mojDrugiTag))
$
