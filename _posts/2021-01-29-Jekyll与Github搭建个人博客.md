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

创建主页看此教程：[官方文档 1](https://pages.github.com/)  

域名解析看此教程：[官方文档 2](https://docs.github.com/en/github/working-with-github-pages/managing-a-custom-domain-for-your-github-pages-site)

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

    2.4 安装Jekyll及其他命令
        - 安装：gem install jekyll
        - 创建新站点（cd 目标目录）：jekyll new blogname
        - 启动服务：jekyll serve
        - 浏览器访问站点：127.0.0.1:4000
        - 
        - 详细命令：https://www.jekyll.com.cn/docs/usage/
    
    2.5 主题
        - 将目标主题clone到本地即可

    2.6 写文章
        - 可使用【2.4新创建的新站点】或者clone新主题
        - _posts目录中创建如下格式文件名几即可：【YEAR-MONTH-DAY-title.MD】(年-月-日-标题名.markdown文件后缀)
        - 文件开头，三根横杠的标识块必须写，详情看文档：https://www.jekyll.com.cn/docs/front-matter/

    2.7 使用
        - 在站点根目录，执行git提交系列命令，再看看github有没有更新，等几分钟再访问站点即可！

# 二、感受

> 能在自己的电脑上使用熟悉的编辑器写作还是蛮舒服的，之前试过其他博客，大多数写作都要在网页上完成，每次想写作，就要经过以下几个流程：打开浏览器->输入域名->登录->选择菜单...  
现在只需要打开编辑器->创建文件->写作->上传~搞定

> 上传到github比自己的小服务器更靠谱，哈哈哈

开始吧







