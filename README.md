# krstudent@system59-OptiPlex-3020:~$ git config user.name
Student
student@system59-OptiPlex-3020:~$ git config user.email
pjskrishna12@gmail.com
student@system59-OptiPlex-3020:~$ 
student@system59-OptiPlex-3020:~$ pwd 
/home/student
student@system59-OptiPlex-3020:~$ cd desktop
bash: cd: desktop: No such file or directory
student@system59-OptiPlex-3020:~$ cd Desktop
student@system59-OptiPlex-3020:~/Desktop$ pwd
/home/student/Desktop
student@system59-OptiPlex-3020:~/Desktop$ mkdir dec7
student@system59-OptiPlex-3020:~/Desktop$ pwd
/home/student/Desktop
student@system59-OptiPlex-3020:~/Desktop$ cd dec7
student@system59-OptiPlex-3020:~/Desktop/dec7$ pwd
/home/student/Desktop/dec7
student@system59-OptiPlex-3020:~/Desktop/dec7$ touch j.txt
student@system59-OptiPlex-3020:~/Desktop/dec7$ ls
j.txt
student@system59-OptiPlex-3020:~/Desktop/dec7$ git init
Initialized empty Git repository in /home/student/Desktop/dec7/.git/
student@system59-OptiPlex-3020:~/Desktop/dec7$ s
s: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ ls
j.txt
student@system59-OptiPlex-3020:~/Desktop/dec7$ ls -a
.  ..  .git  j.txt
student@system59-OptiPlex-3020:~/Desktop/dec7$ git status
On branch master

Initial commit

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	j.txt

nothing added to commit but untracked files present (use "git add" to track)
student@system59-OptiPlex-3020:~/Desktop/dec7$ git add .
student@system59-OptiPlex-3020:~/Desktop/dec7$ git add j.tct
fatal: pathspec 'j.tct' did not match any files
student@system59-OptiPlex-3020:~/Desktop/dec7$ git add j.txt
student@system59-OptiPlex-3020:~/Desktop/dec7$ git status
On branch master

Initial commit

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   j.txt

student@system59-OptiPlex-3020:~/Desktop/dec7$ git commit -m "enosh"
[master (root-commit) d23d1c5] enosh
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 j.txt
student@system59-OptiPlex-3020:~/Desktop/dec7$ git log
commit d23d1c5c434b06fe0cbd91d84cde73b5eb1975dd
Author: Student <pjskrishna12@gmail.com>
Date:   Tue Dec 7 10:40:17 2021 +0530

    enosh
student@system59-OptiPlex-3020:~/Desktop/dec7$ git log --oneline
d23d1c5 enosh
student@system59-OptiPlex-3020:~/Desktop/dec7$ git log --twoline
fatal: unrecognized argument: --twoline
student@system59-OptiPlex-3020:~/Desktop/dec7$ git log --oneline
d23d1c5 enosh
student@system59-OptiPlex-3020:~/Desktop/dec7$ git log d23d1c5 enosh
fatal: ambiguous argument 'enosh': unknown revision or path not in the working tree.
Use '--' to separate paths from revisions, like this:
'git <command> [<revision>...] -- [<file>...]'
student@system59-OptiPlex-3020:~/Desktop/dec7$ d23d1c5 enosh
d23d1c5: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ git log d23d1c5
commit d23d1c5c434b06fe0cbd91d84cde73b5eb1975dd
Author: Student <pjskrishna12@gmail.com>
Date:   Tue Dec 7 10:40:17 2021 +0530

    enosh
student@system59-OptiPlex-3020:~/Desktop/dec7$ d23d1c5 d23d1c5 d23d1c5 
d23d1c5: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ git remote
student@system59-OptiPlex-3020:~/Desktop/dec7$ git remote add ramesh  https://github.com/KANNA07123/file_2.git
student@system59-OptiPlex-3020:~/Desktop/dec7$ git remote
ramesh
student@system59-OptiPlex-3020:~/Desktop/dec7$ git branch
* master
student@system59-OptiPlex-3020:~/Desktop/dec7$ git push ramesh  master
Username for 'https://github.com': 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
Password for 'https://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@github.com': 
Counting objects: 3, done.
Writing objects: 100% (3/3), 205 bytes | 0 bytes/s, done.
Total 3 (delta 0), reused 0 (delta 0)
remote: 
remote: Create a pull request for 'master' on GitHub by visiting:
remote:      https://github.com/KANNA07123/file_2/pull/new/master
remote: 
To https://github.com/KANNA07123/file_2.git
 * [new branch]      master -> master
student@system59-OptiPlex-3020:~/Desktop/dec7$ 
student@system59-OptiPlex-3020:~/Desktop/dec7$ Personal access tokens
Personal: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ 
student@system59-OptiPlex-3020:~/Desktop/dec7$ Tokens you have generated that can be used to access the GitHub API.
No command 'Tokens' found, did you mean:
 Command 'tokens' from package 'openafs-client' (universe)
Tokens: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ Make sure to copy your personal access token now. You won’t be able to see it again!
No command 'Make' found, did you mean:
 Command 'make' from package 'make' (main)
 Command 'make' from package 'make-guile' (universe)
 Command 'jake' from package 'node-jake' (universe)
 Command 'rake' from package 'rake' (main)
 Command 'cake' from package 'cakephp-scripts' (universe)
 Command 'fake' from package 'fake' (universe)
Make: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ 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
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: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ Personal acces
Personal: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ Personal access tokens
Personal: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ 
student@system59-OptiPlex-3020:~/Desktop/dec7$ Tokens you have generated that can be used to access the GitHub API.

Personal access tokens

Tokens you have generated that can be used to access the GitHub API.
Make sure to copy your personal access token now. You won’t be able to see it again!
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
Personal accesNo command 'Tokens' found, did you mean:
 Command 'tokens' from package 'openafs-client' (universe)
Tokens: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ Make sure to copy your personal access token now. You won’t be able to see it again!
No command 'Make' found, did you mean:
 Command 'cake' from package 'cakephp-scripts' (universe)
 Command 'jake' from package 'node-jake' (universe)
 Command 'make' from package 'make' (main)
 Command 'make' from package 'make-guile' (universe)
 Command 'fake' from package 'fake' (universe)
 Command 'rake' from package 'rake' (main)
Make: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ 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
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: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ Personal acces
Personal: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ Personal access tokens

Personal access tokens

Tokens you have generated that can be used to access the GitHub API.
Make sure to copy your personal access token now. You won’t be able to see it again!
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
Personal accesPersonal: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ 
student@system59-OptiPlex-3020:~/Desktop/dec7$ Tokens you have generated that can be used to access the GitHub API.
No command 'Tokens' found, did you mean:
 Command 'tokens' from package 'openafs-client' (universe)
Tokens: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ Make sure to copy your personal access token now. You won’t be able to see it again!

Personal access tokens

Tokens you have generated that can be used to access the GitHub API.
Make sure to copy your personal access token now. You won’t be able to see it again!
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
Personal accesNo command 'Make' found, did you mean:
 Command 'make' from package 'make-guile' (universe)
 Command 'make' from package 'make' (main)
 Command 'cake' from package 'cakephp-scripts' (universe)
 Command 'jake' from package 'node-jake' (universe)
 Command 'rake' from package 'rake' (main)
 Command 'fake' from package 'fake' (universe)
Make: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ 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
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: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ Personal acces

Personal access tokens

Tokens you have generated that can be used to access the GitHub API.
Make sure to copy your personal access token now. You won’t be able to see it again!
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
Personal accesPersonal: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ Personal access tokens
Personal: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ 
student@system59-OptiPlex-3020:~/Desktop/dec7$ Tokens you have generated that can be used to access the GitHub API.
No command 'Tokens' found, did you mean:
 Command 'tokens' from package 'openafs-client' (universe)
Tokens: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ Make sure to copy your personal access token now. You won’t be able to see it again!
No command 'Make' found, did you mean:
 Command 'cake' from package 'cakephp-scripts' (universe)
 Command 'fake' from package 'fake' (universe)
 Command 'make' from package 'make-guile' (universe)
 Command 'make' from package 'make' (main)
 Command 'rake' from package 'rake' (main)
 Command 'jake' from package 'node-jake' (universe)
Make: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ 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

Personal access tokens

Tokens you have generated that can be used to access the GitHub API.
Make sure to copy your personal access token now. You won’t be able to see it again!
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
Personal acces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: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ Personal acces
Personal: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ Personal access tokens
Personal: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ 
student@system59-OptiPlex-3020:~/Desktop/dec7$ Tokens you have generated that can be used to access the GitHub API.

Personal access tokens

Tokens you have generated that can be used to access the GitHub API.
Make sure to copy your personal access token now. You won’t be able to see it again!
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
Personal accesNo command 'Tokens' found, did you mean:
 Command 'tokens' from package 'openafs-client' (universe)
Tokens: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ Make sure to copy your personal access token now. You won’t be able to see it again!
No command 'Make' found, did you mean:
 Command 'jake' from package 'node-jake' (universe)
 Command 'cake' from package 'cakephp-scripts' (universe)
 Command 'make' from package 'make-guile' (universe)
 Command 'make' from package 'make' (main)
 Command 'fake' from package 'fake' (universe)
 Command 'rake' from package 'rake' (main)
Make: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ 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
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: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ Personal acces
Personal: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ Personal access tokens

Personal access tokens

Tokens you have generated that can be used to access the GitHub API.
Make sure to copy your personal access token now. You won’t be able to see it again!
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
Personal accesPersonal: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ 
student@system59-OptiPlex-3020:~/Desktop/dec7$ Tokens you have generated that can be used to access the GitHub API.
No command 'Tokens' found, did you mean:
 Command 'tokens' from package 'openafs-client' (universe)
Tokens: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ Make sure to copy your personal access token now. You won’t be able to see it again!
No command 'Make' found, did you mean:
 Command 'cake' from package 'cakephp-scripts' (universe)
 Command 'fake' from package 'fake' (universe)
 Command 'make' from package 'make-guile' (universe)
 Command 'make' from package 'make' (main)
 Command 'jake' from package 'node-jake' (universe)
 Command 'rake' from package 'rake' (main)
Make: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ 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
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: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ Personal acces
Personal: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ Personal access tokens
Personal: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ 
student@system59-OptiPlex-3020:~/Desktop/dec7$ Tokens you have generated that can be used to access the GitHub API.
No command 'Tokens' found, did you mean:
 Command 'tokens' from package 'openafs-client' (universe)
Tokens: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ Make sure to copy your personal access token now. You won’t be able to see it again!
No command 'Make' found, did you mean:
 Command 'jake' from package 'node-jake' (universe)
 Command 'fake' from package 'fake' (universe)
 Command 'make' from package 'make' (main)
 Command 'make' from package 'make-guile' (universe)
 Command 'cake' from package 'cakephp-scripts' (universe)
 Command 'rake' from package 'rake' (main)
Make: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ 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
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: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ Personal acces
Personal: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ Personal access tokens
Personal: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ 
student@system59-OptiPlex-3020:~/Desktop/dec7$ Tokens you have generated that can be used to access the GitHub API.
No command 'Tokens' found, did you mean:
 Command 'tokens' from package 'openafs-client' (universe)
Tokens: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ Make sure to copy your personal access token now. You won’t be able to see it again!
No command 'Make' found, did you mean:
 Command 'cake' from package 'cakephp-scripts' (universe)
 Command 'rake' from package 'rake' (main)
 Command 'fake' from package 'fake' (universe)
 Command 'jake' from package 'node-jake' (universe)
 Command 'make' from package 'make' (main)
 Command 'make' from package 'make-guile' (universe)
Make: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ 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
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: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ Personal acces
Personal: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ Personal access tokens
Personal: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ 
student@system59-OptiPlex-3020:~/Desktop/dec7$ Tokens you have generated that can be used to access the GitHub API.
No command 'Tokens' found, did you mean:
 Command 'tokens' from package 'openafs-client' (universe)
Tokens: command not foundstudent@system59-OptiPlex-3020:~$ git config user.name
Student
student@system59-OptiPlex-3020:~$ git config user.email
pjskrishna12@gmail.com
student@system59-OptiPlex-3020:~$ 
student@system59-OptiPlex-3020:~$ pwd 
/home/student
student@system59-OptiPlex-3020:~$ cd desktop
bash: cd: desktop: No such file or directory
student@system59-OptiPlex-3020:~$ cd Desktop
student@system59-OptiPlex-3020:~/Desktop$ pwd
/home/student/Desktop
student@system59-OptiPlex-3020:~/Desktop$ mkdir dec7
student@system59-OptiPlex-3020:~/Desktop$ pwd
/home/student/Desktop
student@system59-OptiPlex-3020:~/Desktop$ cd dec7
student@system59-OptiPlex-3020:~/Desktop/dec7$ pwd
/home/student/Desktop/dec7
student@system59-OptiPlex-3020:~/Desktop/dec7$ touch j.txt
student@system59-OptiPlex-3020:~/Desktop/dec7$ ls
j.txt
student@system59-OptiPlex-3020:~/Desktop/dec7$ git init
Initialized empty Git repository in /home/student/Desktop/dec7/.git/
student@system59-OptiPlex-3020:~/Desktop/dec7$ s
s: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ ls
j.txt
student@system59-OptiPlex-3020:~/Desktop/dec7$ ls -a
.  ..  .git  j.txt
student@system59-OptiPlex-3020:~/Desktop/dec7$ git status
On branch master

Initial commit

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	j.txt

nothing added to commit but untracked files present (use "git add" to track)
student@system59-OptiPlex-3020:~/Desktop/dec7$ git add .
student@system59-OptiPlex-3020:~/Desktop/dec7$ git add j.tct
fatal: pathspec 'j.tct' did not match any files
student@system59-OptiPlex-3020:~/Desktop/dec7$ git add j.txt
student@system59-OptiPlex-3020:~/Desktop/dec7$ git status
On branch master

Initial commit

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   j.txt

student@system59-OptiPlex-3020:~/Desktop/dec7$ git commit -m "enosh"
[master (root-commit) d23d1c5] enosh
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 j.txt
student@system59-OptiPlex-3020:~/Desktop/dec7$ git log
commit d23d1c5c434b06fe0cbd91d84cde73b5eb1975dd
Author: Student <pjskrishna12@gmail.com>
Date:   Tue Dec 7 10:40:17 2021 +0530

    enosh
student@system59-OptiPlex-3020:~/Desktop/dec7$ git log --oneline
d23d1c5 enosh
student@system59-OptiPlex-3020:~/Desktop/dec7$ git log --twoline
fatal: unrecognized argument: --twoline
student@system59-OptiPlex-3020:~/Desktop/dec7$ git log --oneline
d23d1c5 enosh
student@system59-OptiPlex-3020:~/Desktop/dec7$ git log d23d1c5 enosh
fatal: ambiguous argument 'enosh': unknown revision or path not in the working tree.
Use '--' to separate paths from revisions, like this:
'git <command> [<revision>...] -- [<file>...]'
student@system59-OptiPlex-3020:~/Desktop/dec7$ d23d1c5 enosh
d23d1c5: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ git log d23d1c5
commit d23d1c5c434b06fe0cbd91d84cde73b5eb1975dd
Author: Student <pjskrishna12@gmail.com>
Date:   Tue Dec 7 10:40:17 2021 +0530

    enosh
student@system59-OptiPlex-3020:~/Desktop/dec7$ d23d1c5 d23d1c5 d23d1c5 
d23d1c5: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ git remote
student@system59-OptiPlex-3020:~/Desktop/dec7$ git remote add ramesh  https://github.com/KANNA07123/file_2.git
student@system59-OptiPlex-3020:~/Desktop/dec7$ git remote
ramesh
student@system59-OptiPlex-3020:~/Desktop/dec7$ git branch
* master
student@system59-OptiPlex-3020:~/Desktop/dec7$ git push ramesh  master
Username for 'https://github.com': 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
Password for 'https://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@github.com': 
Counting objects: 3, done.
Writing objects: 100% (3/3), 205 bytes | 0 bytes/s, done.
Total 3 (delta 0), reused 0 (delta 0)
remote: 
remote: Create a pull request for 'master' on GitHub by visiting:
remote:      https://github.com/KANNA07123/file_2/pull/new/master
remote: 
To https://github.com/KANNA07123/file_2.git
 * [new branch]      master -> master
student@system59-OptiPlex-3020:~/Desktop/dec7$ 
student@system59-OptiPlex-3020:~/Desktop/dec7$ Personal access tokens
Personal: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ 
student@system59-OptiPlex-3020:~/Desktop/dec7$ Tokens you have generated that can be used to access the GitHub API.
No command 'Tokens' found, did you mean:
 Command 'tokens' from package 'openafs-client' (universe)
Tokens: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ Make sure to copy your personal access token now. You won’t be able to see it again!
No command 'Make' found, did you mean:
 Command 'make' from package 'make' (main)
 Command 'make' from package 'make-guile' (universe)
 Command 'jake' from package 'node-jake' (universe)
 Command 'rake' from package 'rake' (main)
 Command 'cake' from package 'cakephp-scripts' (universe)
 Command 'fake' from package 'fake' (universe)
Make: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ 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
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: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ Personal acces
Personal: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ Personal access tokens
Personal: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ 
student@system59-OptiPlex-3020:~/Desktop/dec7$ Tokens you have generated that can be used to access the GitHub API.

Personal access tokens

Tokens you have generated that can be used to access the GitHub API.
Make sure to copy your personal access token now. You won’t be able to see it again!
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
Personal accesNo command 'Tokens' found, did you mean:
 Command 'tokens' from package 'openafs-client' (universe)
Tokens: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ Make sure to copy your personal access token now. You won’t be able to see it again!
No command 'Make' found, did you mean:
 Command 'cake' from package 'cakephp-scripts' (universe)
 Command 'jake' from package 'node-jake' (universe)
 Command 'make' from package 'make' (main)
 Command 'make' from package 'make-guile' (universe)
 Command 'fake' from package 'fake' (universe)
 Command 'rake' from package 'rake' (main)
Make: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ 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
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: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ Personal acces
Personal: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ Personal access tokens

Personal access tokens

Tokens you have generated that can be used to access the GitHub API.
Make sure to copy your personal access token now. You won’t be able to see it again!
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
Personal accesPersonal: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ 
student@system59-OptiPlex-3020:~/Desktop/dec7$ Tokens you have generated that can be used to access the GitHub API.
No command 'Tokens' found, did you mean:
 Command 'tokens' from package 'openafs-client' (universe)
Tokens: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ Make sure to copy your personal access token now. You won’t be able to see it again!

Personal access tokens

Tokens you have generated that can be used to access the GitHub API.
Make sure to copy your personal access token now. You won’t be able to see it again!
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
Personal accesNo command 'Make' found, did you mean:
 Command 'make' from package 'make-guile' (universe)
 Command 'make' from package 'make' (main)
 Command 'cake' from package 'cakephp-scripts' (universe)
 Command 'jake' from package 'node-jake' (universe)
 Command 'rake' from package 'rake' (main)
 Command 'fake' from package 'fake' (universe)
Make: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ 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
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: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ Personal acces

Personal access tokens

Tokens you have generated that can be used to access the GitHub API.
Make sure to copy your personal access token now. You won’t be able to see it again!
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
Personal accesPersonal: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ Personal access tokens
Personal: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ 
student@system59-OptiPlex-3020:~/Desktop/dec7$ Tokens you have generated that can be used to access the GitHub API.
No command 'Tokens' found, did you mean:
 Command 'tokens' from package 'openafs-client' (universe)
Tokens: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ Make sure to copy your personal access token now. You won’t be able to see it again!
No command 'Make' found, did you mean:
 Command 'cake' from package 'cakephp-scripts' (universe)
 Command 'fake' from package 'fake' (universe)
 Command 'make' from package 'make-guile' (universe)
 Command 'make' from package 'make' (main)
 Command 'rake' from package 'rake' (main)
 Command 'jake' from package 'node-jake' (universe)
Make: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ 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

Personal access tokens

Tokens you have generated that can be used to access the GitHub API.
Make sure to copy your personal access token now. You won’t be able to see it again!
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
Personal acces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: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ Personal acces
Personal: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ Personal access tokens
Personal: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ 
student@system59-OptiPlex-3020:~/Desktop/dec7$ Tokens you have generated that can be used to access the GitHub API.

Personal access tokens

Tokens you have generated that can be used to access the GitHub API.
Make sure to copy your personal access token now. You won’t be able to see it again!
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
Personal accesNo command 'Tokens' found, did you mean:
 Command 'tokens' from package 'openafs-client' (universe)
Tokens: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ Make sure to copy your personal access token now. You won’t be able to see it again!
No command 'Make' found, did you mean:
 Command 'jake' from package 'node-jake' (universe)
 Command 'cake' from package 'cakephp-scripts' (universe)
 Command 'make' from package 'make-guile' (universe)
 Command 'make' from package 'make' (main)
 Command 'fake' from package 'fake' (universe)
 Command 'rake' from package 'rake' (main)
Make: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ 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
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: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ Personal acces
Personal: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ Personal access tokens

Personal access tokens

Tokens you have generated that can be used to access the GitHub API.
Make sure to copy your personal access token now. You won’t be able to see it again!
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
Personal accesPersonal: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ 
student@system59-OptiPlex-3020:~/Desktop/dec7$ Tokens you have generated that can be used to access the GitHub API.
No command 'Tokens' found, did you mean:
 Command 'tokens' from package 'openafs-client' (universe)
Tokens: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ Make sure to copy your personal access token now. You won’t be able to see it again!
No command 'Make' found, did you mean:
 Command 'cake' from package 'cakephp-scripts' (universe)
 Command 'fake' from package 'fake' (universe)
 Command 'make' from package 'make-guile' (universe)
 Command 'make' from package 'make' (main)
 Command 'jake' from package 'node-jake' (universe)
 Command 'rake' from package 'rake' (main)
Make: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ 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
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: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ Personal acces
Personal: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ Personal access tokens
Personal: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ 
student@system59-OptiPlex-3020:~/Desktop/dec7$ Tokens you have generated that can be used to access the GitHub API.
No command 'Tokens' found, did you mean:
 Command 'tokens' from package 'openafs-client' (universe)
Tokens: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ Make sure to copy your personal access token now. You won’t be able to see it again!
No command 'Make' found, did you mean:
 Command 'jake' from package 'node-jake' (universe)
 Command 'fake' from package 'fake' (universe)
 Command 'make' from package 'make' (main)
 Command 'make' from package 'make-guile' (universe)
 Command 'cake' from package 'cakephp-scripts' (universe)
 Command 'rake' from package 'rake' (main)
Make: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ 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
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: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ Personal acces
Personal: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ Personal access tokens
Personal: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ 
student@system59-OptiPlex-3020:~/Desktop/dec7$ Tokens you have generated that can be used to access the GitHub API.
No command 'Tokens' found, did you mean:
 Command 'tokens' from package 'openafs-client' (universe)
Tokens: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ Make sure to copy your personal access token now. You won’t be able to see it again!
No command 'Make' found, did you mean:
 Command 'cake' from package 'cakephp-scripts' (universe)
 Command 'rake' from package 'rake' (main)
 Command 'fake' from package 'fake' (universe)
 Command 'jake' from package 'node-jake' (universe)
 Command 'make' from package 'make' (main)
 Command 'make' from package 'make-guile' (universe)
Make: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ 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
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: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ Personal acces
Personal: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ Personal access tokens
Personal: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ 
student@system59-OptiPlex-3020:~/Desktop/dec7$ Tokens you have generated that can be used to access the GitHub API.
No command 'Tokens' found, did you mean:
 Command 'tokens' from package 'openafs-client' (universe)
Tokens: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ Make sure to copy your personal access token now. You won’t be able to see it again!
No command 'Make' found, did you mean:
 Command 'make' from package 'make-guile' (universe)
 Command 'make' from package 'make' (main)
 Command 'rake' from package 'rake' (main)
 Command 'fake' from package 'fake' (universe)
 Command 'jake' from package 'node-jake' (universe)
 Command 'cake' from package 'cakephp-scripts' (universe)
Make: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ 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
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: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ Personal acces

student@system59-OptiPlex-3020:~/Desktop/dec7$ Make sure to copy your personal access token now. You won’t be able to see it again!
No command 'Make' found, did you mean:
 Command 'make' from package 'make-guile' (universe)
 Command 'make' from package 'make' (main)
 Command 'rake' from package 'rake' (main)
 Command 'fake' from package 'fake' (universe)
 Command 'jake' from package 'node-jake' (universe)
 Command 'cake' from package 'cakephp-scripts' (universe)
Make: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ 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
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: command not found
student@system59-OptiPlex-3020:~/Desktop/dec7$ Personal acces

