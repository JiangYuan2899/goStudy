# Go语言学习笔记

[大牛博客地址](https://www.liwenzhou.com)

从0到1开发Go语言程序


## 查看相关配置命令
go env
![0fe1ecb52f3983db64b519c6f3be6fb6.png](en-resource://database/5998:1)

## 项目结构
src-域名（通常是github地址）-作者名（公司里面写项目组名）--项目名---模块名

## 编译
使用go build
1.在项目目裂下执行g0build
2.在其他路径下行go build，需要在后面加上项目的路径（项目路径从GOPATH/SC后开始写起，编译之后的可执行文件就保存在当前目录下）
3.go build-o hello.exe