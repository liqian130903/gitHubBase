版本控制器：
    git和svn的区别：
	svn：集中式
	git：分布式

识别用户名和密码：
$ git config --global user.name "Your Name"
$ git config --global user.email "email@example.com"

通过 git init 命令把当前的目录变成一个仓库

注意：dir修改为ls  使用ls -ah可以查看隐藏文件

版本库添加文件：
   git add filename
版本库提交文件
   git commit -m ‘备注’
查看版本库状态：
   git status
查看文件的修改： 需要文件没有被添加和提交才可以查看
   git diff
查看历史版本
   git log 
   简化输出信息：git log --pretty=oneline
回退或回到某个版本
   git reset --hard HEAD^ (版本代码)