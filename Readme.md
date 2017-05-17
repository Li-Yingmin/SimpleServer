### 测试禁用是否成功的html

#### (1）下载virtualenv

#### (2）克隆项目

```bash
$ git clone https://github.com/Li-Yingmin/SimpleServer.git
```
####  (3)激活python3虚拟环境
```bash
$ source 目录/SimpleServer/bin/activate
```
####  (4)本地执行简单的Server
进入  目录/SimpleServer/myproj
执行语句：
```bash
$ python3 -m http.server 8089
```
则会在浏览器`0.0.0.0:8089`看到html页面