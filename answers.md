git version 2.43.0
user.name=SamGajewski user.email=Samuel.a.gajewski@gmail.com
When you type git add --help it brings up a description and a synopsis of how the git add file command works.
When typing in the git status command it reveals the untracked files, anser.md and README.md
After tracking the file and issuing the git status command it now shows the file in "changes to be commited" the file that is in that section is called README.md
After tracking the file answers.md they now both appear in green under the section "changes to be commited".
After doing the "Initial Commit" and issuing the status command again, it shows up with the on branch master and it shows that answer.md file has been modified.
no changes added to commit (use "git add" and/or "git commit -a")samuelgajewski@samskilaptop:~/git-lab$ git log commit 80aafe95ccbd6c45999822a2716e455d9e337a15 (HEAD -> master) Author: SamGajewski <Samuel.a.gajewski@gmail.com> Date:   Wed Sep 3 16:40:49 2025 -0400 
On branch main Your branch is up to date with 'origin/main'. Changes not staged for commit:   (use "git add <file>..." to update what will be committed)   (use "git restore <file>..." to discard changes in working directory)         modified:   answers.md no changes added to commit (use "git add" and/or "git commit -a")
When I looked at the README.md file the changes I made online to github did show up in the terminal.
When I try and put in git push again it gives me an error because it has things that I don't have locally.
The changes that I made on git hub were shown when I looked at the README.md
samuelgajewski@samskilaptop:~/CS2400/git-lab-2$ ls -a .  ..  .git  .gitignore  README.md
