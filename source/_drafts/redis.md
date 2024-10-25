# 使用redis
## 安装
## 启动redis
1. 进入redis文件夹
启动
``` shell
   redis-server redis.conf
```
2. 查看redis-server监听的端口号

``` shell
ps aux | grep redis-server
```
如果在  127.0.0.1:6379
说明本地连接

3. 进入redis输入命令
``` shell 
 redis-cli
```  