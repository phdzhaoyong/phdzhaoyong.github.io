---
title: "自学Hugo+Github+Markdown"
date: 2019-12-28T20:33:50+08:00
draft: false
author: "Admin"
---

以下行文的结构框架为：

> Hugo
> 
> - 网站图标

Hugo

参考地址 [https://jingyan.baidu.com/article/adc8151326554bb722bf7373.html](https://jingyan.baidu.com/article/adc8151326554bb722bf7373.html)

放在根目录下的static文件夹下的img文件夹内的图片通过hugo后直接拷贝到public文件夹下img目录下。通过修改config.toml文件中logogile = 指令成功更换logo图标，以及修改faviconfile = 指令成功更换icon文件。

一个不错的hugo学习网站[http://www.g-var.com/posts/translation/hugo/hugo-9-sections/](http://www.g-var.com/posts/translation/hugo/hugo-9-sections/)

网上很少 有中文的入门教程，制作这个教程也是想帮助想使用hugo建站的小白们，少走弯路。



> github
> 
> - github pages

## Github

### Github Pages

第一步 创建一个仓库
命名方式为 账号 + .github.io ，例如我的仓库名为：phdzhaoyong.github.io

第二步 在仓库里添加CNAME文件
有两总方式：

第一种：在仓库里添加一个文件，命名为 CNAME，文件名大写且没有后缀；文件里填写要绑定的域名且不要包含Http://和www

第二种：进入setting设置中，找到 github pages-Custom domain添加域名www.renren.team后保存即可。同时在code仓库里系统自动创建了CNAME文件，并且里面添加了subdomain域名。

第三步 域名解析
在新网购买的域名，添加解析CNAME即可。--网站可以正常访问了，恭喜你成功了。

> Markdown
> 
> - 基础篇
> 
> - 进阶篇

## 基础篇[^mark text]

[^mark text]:一款不错的编辑器。

使用编辑器会使撰写文章变的轻松许多，但是并不是很多功能都能胜任。例如注脚的使用。

参考网站为[https://www.runoob.com/markdown/md-tutorial.html](https://www.runoob.com/markdown/md-tutorial.html)

```markdown
创建脚注格式类似这样  [^RUNOOB]。 
[^RUNOOB]: 菜鸟教程 -- 学的不仅是技术，更是梦想！！！
```

### 标题的符号使用

使用#标记标题字号大小，#号越多标题越小。

### 换行的符号使用

撰写本文的时候使用的marktext工具，此工具使用空行表示重新开始一个段落。

 喜欢的IDE工具输入命令hugo new blog/a.md

### 首行缩进妙用

首行缩进的办法，在中文文章撰写中通常需要首行缩进，但是markdown语法中没有这个考虑，在网上看到一个帖子说用全角状态下输入两个空格即可。试了一下还真行。



## 进阶篇

```html
<kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Del</kbd>  重启电脑
```

<kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Del</kbd>  重启电脑

