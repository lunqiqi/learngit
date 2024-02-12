# Git bash 命令  
## Git 初始化  
~~~shell
git init
~~~
## 当前状态查看  
~~~shell
git status
~~~  
## 查看修改记录  
~~~shell
git diff git_cmd.md
~~~  
add之后git diff 不会有输出。  
## 查看历史版本  
~~~shell
git log git_cmd.md
git log --pretty=oneline # 简介输出
~~~
## 退回上一个版本  
~~~shell
git reset --hard HEAD^ # head^可替换成对应版本号，退回到相应制定版本
~~~  
## 关联远程仓库  
~~~shell
git remote add origin git@server-name:path/repo-name.git
~~~  

## 远程仓库提交  
~~~shell
git push origin master
~~~  
## 远程仓库克隆到本地  
~~~shell
git clone git@github.com:lunqiqi/gitskills.git #替换具体仓库的ssh地址
~~~  
## 创建新分支  
~~~shell
git checkout -b dev
#新版本
git switch -c dev
~~~  
## 切换分支
~~~shell
git checkout master
#新版本
git switch master
~~~  
## 合并分支  
~~~shell
git merge dev
~~~  
## 查看分支状态  
~~~shell
git branch
~~~  
## 删除分支  
~~~shell
git branch -d dev
~~~  
## 创建标签  
~~~shell
git tag -a v1.0 -m "first vision"
~~~  
## 查看标签  
~~~shell
git tag
~~~  
## 推送标签  
~~~shell
git push origin v1.0
~~~  

