# Git 基本概念

- Workspace 	工作区
- Index/Stage	暂存区
- Repository	仓库区
- Remote	远程仓库

# 如何操作

```
git config --global user.name "your name"
git config --global user.name "your email"
cd git_directory
git init
vim your_file
git add your_file
git commit -m "commit"
git status
vim your_file
git diff your_file
git commit -m "add"
git status
git log 
git log -pretty=oneline
git reset --hard HEAD^
git reset --hard HEAD^^
git reset --hard HEAD~3
git reflog
git checkout -- your_file

```


