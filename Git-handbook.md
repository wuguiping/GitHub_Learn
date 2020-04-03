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

# 远程仓库

1. 注册 GitHub 帐号

2. 创建 SSH Key

```
ls ~/.ssh/id_rsa " 私钥
ls ~/,ssh/id_rsa.pub " 公钥

ssh-keygen -t rsa -C "yourmain@example.com"
```

3. 上传公钥到 GitHub

4. 提交本地仓库到 GitHub

`git push origin master`

5. 从远程库克隆

`git clone https://github.com/yours/test`

# 创建与合并分支

1. 查看分支
`git branch`

2. 创建分支
`git branch name`

3. 切换分支
`git checkout name`

4. 创建切换分支
`git checkout -b name`

5. 合并某分支到当前分支
`git merge name`

6. 删除分支
`git branch -d name`


