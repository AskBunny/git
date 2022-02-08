# git

**General** <br />
Create directory mkdir folder <br />
Create a file> touch fileA.txt <br />
Open notepad> notepad fileA.txt <br />
Clear> cmd+k <br />

**Git** <br />
Access config file> git config --global --edit <br />
All files> git add . <br />
Track > git status <br />
Commit> git commit -m "initial commit" <br />
Displays more information about repositary> git remote -v <br />

**Log** <br />
Show log > git log <br />
Condensed version of the log> git log --oneline <br />
Shows two logs> git log --oneline -2 <br />

**Branches** <br />
List all the branches > git branch <br />
Move one to another > git checkout branchname <br />
Create a new branch > git branch branchname <br />
git branch and directly enter > git checkout -b branchname <br />
Delete git branch > git checkout -d branchname <br />

**Merge**  <br />
Merge one branch with another (current branch) > git merge branchname  <br />

**Git ignore**  <br />
Create file > touch .gitignore  <br />
Now add the file name in .gitignore (secret.txt), git won't track. Can add .gitignore in .gitignore, will not show in git status  <br />

**Push branch**  <br />
Open the branch > git checkout dev  <br />
Push > git push -u origin dev  <br />

**Clone**  <br />
Clone remote repositary> git clone url  <br />

**readme.md**  <br />
Open > vim readme.md  <br />
Insert = i, Exit = esc, colon, w, q  <br />
Check the changes > cat readme.md  <br />
