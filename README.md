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






