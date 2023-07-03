# Git_GitHub
Tutorial

git --version

git config --global user.name "Name Sername"
#
git config --global user.email "zzzzz@xxxx.yy"

git config -l
#
ls -la  # run from ~ directory (find file .gitconfig)
#
cat .gitconfig # run from ~ directory

# How to work with the local repository

mkdir myproject/
#
ls
#
cd myproject/
#
ls
#
git init # This command tells git to start watching the current directory and record all changes in files
#
ls -la # This command will show you .git file
#
ls -la .git/ # This command will shows you what .git include
#
git status # This command shows you the current status/current changes
#
echo "Source file1" > file1.txt # this command will create a text file with the string "Source file1". You can use the command "cat file1.txt" to check what it contains
#
echo "Source file2" > file2.txt
#
git status
#
git add . | git add * | git add file1.txt # These three commands allow you to add all files or only one(file1.txt) P.S// Choose only one of them. "|" - Separator
#
git status # Input this to see what happened
#
git commit -m "My initial commit, this is Version1.0"
#
Let's do some editing:
#
nano file1.txt # Edit it and save
#
echo "Source file3" > file3.txt # Add third file
#
git status
#
git add .
#
git commit -m "Added file3 and updated file1"
#
git log # History of all commits
#
git log -1 # Last commit
#
git log -1 -p # Shows all changes which were done with this commit
#
nano file1.txt # Make some changes to it
#
git status
#
cat file1.txt
#
git checkout -- file1.txt # Cancel all changes
#
cat file1.txt
#
git status
#
How works git diff
-
echo "qwertyqwerty" > newfile1.txt
#
git status
#
git add .
#
git status
#
git diff --staged # Show the difference between stage "Staged" and the last commit. This would be written to log after commit.
#
Configurations for ignoring files:
-









