# 任务一（初始git）
A:添加已有项目到GitHub
##1:去github上创建自己的Repository
##2:克隆文件到本地（git  clone）     本地去修改
##3：将项目的所有文件添加到仓库中（git add .  之后     git add  文件名）
##4：提交到仓库（git commit -m "注释语句"）
##5：将本地的仓库关联到GitHub，后面的https改成刚刚自己的地址（git remote add origin https://github.com/zlxzlxzlx/Test.git）添加到远程项目，别名为origin
##6：上传github之前pull一下（git pull origin master）》》》》》》/在推送前看看别人有没有推送
##7：上传代码到GitHub远程仓库（git push -u origin master）
B:更新代码
##1:查看当前的git仓库状态，可以使用(git status)
##2:更新全部(git add *)
##3:接着输入git commit -m "更新说明"(git commit -m "更新说明")
##4:先git pull,拉取当前分支最新代码(git pull)
##5:push到远程master分支上(git push origin master)
#:github常用命令
git push origin master //把本地源码库push到Github上
git pull origin master //从Github上pull到本地源码库
git config --list //查看配置信息
git status //查看项目状态信息
git branch //查看项目分支
git checkout -b host//添加一个名为host的分支
git checkout master //切换到主干
git merge host //合并分支host到主干
git branch -d host //删除分支host
