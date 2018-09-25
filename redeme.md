每一次备份都会把当前备份者的信息存储起来
1：git init //配置信息

2：git config --global user.name “xiaoqiang”           //配置git用户姓名

3：git config --global user.email “xiaoqiang@qq.com”   //配置用户邮箱

4：git add ./redeme.me          //把你要备份的文件放入仓库门口

5：git commit -m "修改了什么东西，做了什么事情"         //把仓库门口的文件放入到房间中     并且说明做了些什么事情（-m）

6:git status   //查看有没有修改过文件，或者有没有把文件放到门口（绿色：放了/红色没有放）

7：  git add ./         //把所有文件放到门口

8：  git commit  --all  -m "一次性放到仓库中"       // 把所有修改的文件放到仓库

9：  clear          // 清除之前所有命令记录显示

10： git log        //查看修改的记录、日志

11： git log --oneline      //  可以看到简介版的记录、日志

12： git  reset  --hard  Head~0   //  回退到第几个版本   （Head~0：表面退回到第一个版本）
