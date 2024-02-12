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
