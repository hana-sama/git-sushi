<!-- cheet sheet 

--make new branch and move to the new branch
git checkout -b <****>

--move to different branch
git checkout <****>

-- check status
git status

-- initialize git
git init  

-- stage all files or folder
git add .

-- commit files staged
git commit - m "comment"

-- push to the repository
git push origin/<branch name>

-- delete branch
git brandh -D <branch name>

-- move to previous branch

git checkout -

-- rename branch name
git branch -m(odifty) <new name>

-- restore from the staging area to unstaged
git restore --staged <file name>

-- restore specific file entirely
git restore <filename>

-- unstage file from the staged area
git reset

-- check differential
git diff --cached

-- show local branch
git branch

-- show all brancches including remote brancches
git branch -a

-- download remote repository and add to local working repository
git checkout -t remotes/origin/<branch name>

-- confirm differential between current branch with specific branch
git diff <br name>..<target branch name>

-- fast-forward merge target branch into working branch
git merge <target branch name>

-- not fast-forward merge
git merge --no-ff <target branch name>

-- display git log
git log
-- display only one line log
git log --oneline

-- display oneliner log in graph style
git log --onlien --graph

-- annul merge 
git reset --hard ORIG_HEAD

-- search certain word
grep -r(recursively) <search term> .(current directory)

-- search word via git command
git grep <search term>

-- display multriple files in the directory
git ls-files

-- display log history retroactively
git log -p <filename>

-- track commit history who made certain changes to certain files
git blame <file name>
-->