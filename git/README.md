# 待解决问题

GitHub，码云都是根据git 客户端的用户名和邮箱进行贡献统计

[Git 和 GitHub 的 username，Email](https://blog.csdn.net/sinat_36710456/article/details/80189687)

尽量将git客户端的用户名、邮箱和github账号的用户名、邮箱设置为完全一致；

可以设置当前库的用户名和密码





是不是git  clone 之后，谁都可以修改代码，并push 到master？



GitHub 账号问题，如何保证代码不被别人随意修改？

git 公司账号，个人账号



##### git  查看本地用户密码



git clone 时，https和SSH 的区别？

https 需要验证用户名和密码，而SSH需要先添加SSH key ，然后提交

之所以不需要输入账号信息，是因为在git pull 或 git push 时输入过账号密码，已经将账号信息保存在windows的管理凭据中（可设置账号保存的时效）



[Git 本地记住密码与清空密码](https://blog.csdn.net/s735819795/article/details/90376586)

`` 记住密码 `` 

``git config --global credential.helper wincred``



``清空本地密码``

``git credential-manager uninstall``



## git，github,gitlab 之间的关系



开发git后，没有GitHub阶段，Linux的代码是怎么维护？



注意：

git是不能管理空的文件夹的，文件夹里必须有文件才能add



本地添加远程仓库

git remote add origin git@github.com:wangjiax9/beautifulDay.git