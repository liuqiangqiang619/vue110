每一次备份都会把当前备份者的信息存储起来
1：git init //配置信息

2：git config --global user.name “xiaoqiang”           //配置git用户姓名

3：git config --global user.email “xiaoqiang@qq.com”   //配置用户邮箱

4：git add ./redeme.me          //把你要备份的文件放入仓库门口

5：git commit -m "修改了什么东西，做了什么事情"         //把仓库门口的文件放入到房间中     并且说明做了些什么事情（-m）

6:git status   //查看有没有修改过文件，或者有没有把文件放到门口（绿色：放了/红色没有放）
