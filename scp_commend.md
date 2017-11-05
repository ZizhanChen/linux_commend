## 1 ssh      
 $ ssh username@remotehost 
 用shh登陆服务器。

## 2、scp 
 命令scp基于SSH协议，可以将本地文件拷贝到远程服务上的指定目录，格式如下：
 
 $ scp filename username@remotehost:remotedirectory
 
 执行：$ scp ipmsg.log admin@10.25.1.202:/home/admin