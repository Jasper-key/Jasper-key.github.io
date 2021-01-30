---

title: Jekyll与Github搭建个人博客
data: 2021-01-29 17:00:00
categoty: Website
tags:
- Jekyll
- Git
- 教程
description: 此文章记录了本博客的搭建过程

---

# 一、搭建流程
    本教程适用于Windows操作系统

## 1. 创建github主页
1.1 创建主页看此教程：[官方文档 1](https://pages.github.com/)  
1.2 域名解析看此教程：[官方文档 2](https://docs.github.com/en/github/working-with-github-pages/managing-a-custom-domain-for-your-github-pages-site)

## 2. 本地环境
需要安装的依赖请看[官方文档](http://jekyllcn.com/docs/installation/)，下面说下注意事项，避坑！！！  
Nodejs和Python的安装请看其他教程，本文不再赘述。

    2.1 git bush
        - window 使用git bush来输入命令会避掉很多坑，特别是对window支持不是特别好的程序！
    2.2 ruby
        - 版本2.5.8（本来装的是2.7，编译主题时，提示版本需要<2.6）
        - 安装的路径不能有中文，安装面板已提示
        - 无脑 Next
        - 最后出现命令窗口，提示输入[1、2、3]时，按123的顺序 Enter
        - 安装完后更换源：https://gems.ruby-china.com/  （看第一个模块：如何使用？，更新gem命令可不执行，后面有提示再弄也行）

    2.3 RubyGems
        - 解压在某个目录中
        - 进入Gemfile根目录，输入命令：ruby setup.rb
        - 更换源：https://gems.ruby-china.com/  （看第二个模块：如果你使用 Gemfile 和 Bundler）
    







