前端环境搭建方法
================

### 前端环境：nodejs + gruntjs（完成less编译 + css压缩 + js压缩）

1. 安装nodejs请参考：<http://howtonode.org/how-to-install-nodejs>
2. 安装gruntjs请参考：<http://www.gruntjs.org/article/getting_started.html>

### 具体安装和使用方法

1. 确保安装完nodejs
2. 可在任意目录下执行：`npm install –g grunt-cli`用来安装gruntjs
3. 在前端环境路径中执行：`grunt`即可编译less + 压缩编译后的css + 压缩js，如果文件发送变化，也将实时编译
