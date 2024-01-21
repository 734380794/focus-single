
## 项目介绍

1. 项目下载
```
git clone https://github.com/gogf/focus-single.git
cd focus-single
```

2. 更新配置文件
修改 database.default config
```
manifest/config/config.yaml
```

3. 导入Db
Import manifest/document/focus.sql to your Mysql

4. 运行项目
```
gf run main.go
```

接下来打开 http://127.0.0.1:8003/
```
user:     goframe
password: 123456
```
5. hack工具编译配置

```
build:
name:     "focus"   项目名称
arch:     "amd64"   内核
system:   "linux,darwin,windows"    平台    
packSrc: "manifest,resource" 资源打包
```
```
gf build  命令打包文件
```
6. 接口文档
```
http://127.0.0.1:8003/apidoc
```
7.参考文档
官方文档：https://goframe.org
学习笔记：https://gitee.com/unlimited13/code
B站视频：https://www.bilibili.com/video/BV1Uu4y1u7kX



