### HTTP

#### 通过命令行查看html
```curl -L http://www.baidu.com```

#### 服务器(server)
硬件(电脑)
软件(程序)

#### DNS(domain name service)
我们可以想象一下,DNS存储了域名和IP的对应数据
例如
baidu.com -> 123.125.114.144

这里需要说明一下, 一个域名可以对应多个IP

##### DNS是什么?
+ 输入: 域名
+ 输出: IP
+ 一个域名对应的IP是由域名的所有者指定的
+ 改hosts可以手动指定域名对应的IP
+ DNS可能有缓存

##### 端口是什么?
0-1023是保留端口, 我们一般自己设置的话从1024端口开始使用, 只有服务器管理员可以使用保留端口0-1023
下面的端口必须背下来
21 - FTP
80 - HTTP
53 - DNS
443- HTTPS
1080 - socks

#### 请求
查看带响应头的响应
```curl -D - http://wwww.baidu.com```
