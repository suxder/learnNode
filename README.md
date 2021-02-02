# learnNode

## 一、基本的cmd命令与环境变量

## 1.cmd命令

- dir ： 列出当前路径的目录
- md ：在当前路径创建一个空文件夹
- rm  ：删除指定的文件夹
- cd   ：切换到指定的路径

## 2.环境变量



## 二、模块化

1.特点

- 每一个js文件都是一个模块
- 每一个js文件都是一个具有五个形参的函数

2.五个形参

- exports 该对象用来向外暴露变量或者函数
- require 函数，用来引入其他的模块
- module 代表该模块本身
- module.exports == exports
- __filename 该模块的绝对路径
- __dirname 该模块所在文件夹的绝对路径

