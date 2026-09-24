## 9.23作业
1.在终端打开git bash，然后输入git init；

2.3.  git add homework.md 就是将md文件加入暂存区，然后git commit -m"  " 就是将暂存区中的内容提交到本地仓库中，-m"  "是提交信息，可以自己填写，也可以不填写，如果填写了，那么在git log中可以看到提交信息。

4.5. git remote add origin https://github.com/jayfan0712ly/Software-Engineering-and-Practice-By-Jay-Fan.git 将我的github仓库地址添加到本地仓库中，实现关联。

6.7.8.体现在建立仓库以及上传过程中。

9.使用git fetch origin，然后git merge origin/master，文件可能成为
```text
<<<<<<< HEAD
print("我在本地增加的功能")
=======
print("别人在远程增加的功能")
>>>>>>> origin/master
```
根据自己的需求保留语句并删除多余符号。


10.使用git merge 语句合并。