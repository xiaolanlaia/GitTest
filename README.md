> 一、撤销push提交，保留本地代码
~~~
1、git log 查看提交记录
2、wq退出log查看
3、git reset --soft<想撤销的提交的上一条提交的版本号>
4、git push origin <分支名> -f
~~~

> 二、push到远程的提交，怎么变基到其他分支

~~~
rebase
~~~

> 三、回撤拉取别人的代码

~~~
1、git reflog
2、git reset --hard <拉取之前一个提交记录的版本号>
~~~

