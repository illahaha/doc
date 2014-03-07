#git 配置#
---
*    GIT配置
---
##GIT配置##
1.配置本地配置
  git config --local user.name "your name"
  git config --local email "your email"

  git config --list

2.远程配置
  github 上创建一个仓库，使用命令:
  git clone http://github.com/xxx/xxx.git
  注意:
  使用https://github.com/xxx/xxx.git clone下来的库，提交的时候需要配置证书
  使用http://github.com/xxx/xxx.git  clone下来的版本库，提交的时候需要输入用户名密码

3.远程版本库配置
  git remote add origin git@github.com/xxx/xxx

4.提交
  git add . 添加所有更改
  git commit -am "xxx" 本地提交
  git push origin master 远程提交
