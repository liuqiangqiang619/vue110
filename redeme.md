每一次备份都会把当前备份者的信息存储起来
1： git init //配置信息

2： git config --global user.name “xiaoqiang”           //配置git用户姓名

3： git config --global user.email “xiaoqiang@qq.com”   //配置用户邮箱

4： git add ./redeme.me          //把你要备份的文件放入仓库门口

5： git commit -m "修改了什么东西，做了什么事情"         //把仓库门口的文件放入到房间中     并且说明做了些什么事情（-m）

6:  git status   //查看有没有修改过文件，或者有没有把文件放到门口（绿色：放了/红色没有放）

7：  git add ./         //把所有文件放到门口

8：  git commit  --all  -m "一次性放到仓库中"       // 把所有修改的文件放到仓库

9：  clear          // 清除之前所有命令记录显示

10： git log        //查看修改的记录、日志

11： git log --oneline      //  可以看到简介版的记录、日志

12： git  reset  --hard  Head~0   //  回退到第几个版本   （Head~0：表面退回到第一个版本）

13：git reset  --hard   5dfde08         //  用版本号来指定回退到哪个版本

14： git reflog         //打印对版本号切换操作的记录、和之前提交的版本号

15： git branch dev         //创建分支，防止做到一半提交上去不能运行。  dev: 是创建分支的名字

16： git branch             //查看创建的分支

17： git checkout   dev        //创建完了之后 需要切换到dev中编写未完成的代码

18： git checkout  master       //完成了未完成的代码之后需要提交到仓库，切换到  master 

19:  git merge  dev             //合并dev的代码
