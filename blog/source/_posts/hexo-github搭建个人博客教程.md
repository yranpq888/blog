---
title: hexo+github搭建个人博客教程
date: 2018-07-24 11:34:10
tags:
---
### 一、hexo
1. 特点：快速、简洁且高效的博客框架
2. 环境：基于node（v8.11.2）
(1)、环境及检测：
win+r输入cmd回车
cmd窗口输入node -v回车
如果提示node不是内部或者外部命令，则需要安装node
(2)、安装node环境：
在百度输入node，进入第一个node.js官网，下载8.11.3LTS，然后下载好了直接安装msi文件点
[下载](https://nodejs.org/zh-cn/) 下载8.11.3版本
双击下载得到的mis文件，全程next安装
node -v 查看版本
### 二、安装git(版本控制器)
[下载](https://git-scm.com/)
百度里面输入git打开git官网在右下角有一个电脑显示器上有Download下载按钮
### 三、安装hexo
cmd命令：
```
npm install hexo-cli -g
```
  npm:基于node的包管理器，类似于ios的app store
  如果npm可以下载安装需要的插件或者框架
  install：安装、导入
  -g：表示全局安装(在任何的目录都可以使用)   
```
C:\Users\web>npm install hexo-cli -g
C:\Users\web\AppData\Roaming\npm\hexo -> C:\Users\web\AppData\Roaming\npm\node_modules\hexo-cli\bin\hexo
npm WARN optional SKIPPING OPTIONAL DEPENDENCY: minimist@0.0.8 (node_modules\hexo-cli\node_modules\mkdirp\node_modules\minimist):
 npm WARN optional SKIPPING OPTIONAL DEPENDENCY: EEXIST: file already exists, mkdir 'C:\Users\web\AppData\Roaming\npm\node_modules\hexo-cli\node_modules\mkdirp'
npm WARN optional SKIPPING OPTIONAL DEPENDENCY: File exists: C:\Users\web\AppData\Roaming\npm\node_modules\hexo-cli\node_modules\mkdirp
npm WARN optional SKIPPING OPTIONAL DEPENDENCY: fsevents@1.2.4 (node_modules\hexo-cli\node_modules\fsevents):
npm WARN notsup SKIPPING OPTIONAL DEPENDENCY: Unsupported platform for fsevents@1.2.4: wanted {"os":"darwin","arch":"any"} (current: {"os":"win32","arch":"x64"})

+ hexo-cli@1.1.0
removed 115 packages and updated 98 packages in 48.125s
```
注：有黄色标记可以不管
### 四、初始化一个博客项目
鼠标右击新建一个Git Bash Here
```
    $ hexo init blog

    INFO  Cloning hexo-starter to ~\Desktop\个人博客\blog
    Cloning into 'C:\Users\web\Desktop\个人博客\blog'...
    remote: Counting objects: 65, done.
    remote: Total 65 (delta 0), reused 0 (delta 0), pack-reused 65
    Unpacking objects: 100% (65/65), done.
    Submodule 'themes/landscape' (https://github.com/hexojs/hexo-theme-landscape.git                                                      ) registered for path 'themes/landscape'
    Cloning into 'C:/Users/web/Desktop/个人博客/blog/themes/landscape'...
    remote: Counting objects: 824, done.
    INFO  Bye!objects:  27% (228/824), 244.01 KiB | 2.00 KiB/s
    warning: Clone succeeded, but checkout failed.
    You can inspect what was checked out with 'git status'
    and retry the checkout with 'git checkout -f HEAD'
```
1. hexo init 项目名
2. 切换到项目目录
  cd 项目名
3. 安装项目依赖包
nmp install
4. 启动服务
    hexo s








            
