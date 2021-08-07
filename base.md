1. 配置
git config -- global user.name "Nicholas"
git config -- global user.email "Nicholas@xx.com"


2. 操作
git init 


3. 添加到仓库
git add base.md

git commit -m "本次提交描述"

添加到仓库完成 有一个版本


4. 查看所有版本
git log
git log --pretty=oneline

5. 查看仓库状态
git status


6. 撤销
git reset


7. 版本回退
git reset --hard 12345


8. git reflog 
所有git 仓库 操作记录


<!-- 生成ssh-key -->
 ssh-keygen -t rsa -b 4096 -C "your_email@example.com"


关联远程仓库
 git remote add origin git@github.com:wengjielong/git-text.git


git branch -M main

推送到远程仓库
git push -u origin main


第一次拿别人的项目所有代码
git clone git@github.com:wengjielong/git-text.git

以后每次更新代码用
git pull
