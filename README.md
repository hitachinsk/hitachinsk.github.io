# 介绍

感谢[tmaize](https://github.com/TMaize/tmaize-blog)发布的这款主题

一款 jekyll 主题（[GitHub 地址](https://github.com/TMaize/tmaize-blog)），简洁纯净(主题资源请求<20KB)，未引入任何框架，秒开页面，支持自适应，支持全文检索

你可以到[TMaize Blog](http://blog.tmaize.net/)查看主题效果，欢迎添加友链

# 版本说明

主题更新帮助

1. 备份`_config.yml, posts, _posts, CNAME`文件，然后删除整个项目目录(.git 不要删)

2. 下载 [release](https://github.com/TMaize/tmaize-blog/releases)的最新版本，解压到你的项目中

3. 删除`posts, _posts, CNAME`文件，把刚刚备份的再复制回来

4. 打开备份的`_config.yml`和最新的`_config.yml`,对比配置把一些配置项复制回来

5. 提交 git，主题更新到最新 😎

## V1.0

- 精简代码 35 files changed, 829 insertions(+), 1043 deletions(-)

- 整体样式细节调整，移动端自动引入 Consolas 字体

- menu 改成中文，取消移动端 menu 的 fix 布局

- `_data` 的配置文件移动到`_config.yml` 中

- 修复全局搜索不支持尖括号

- 删除留言板，切换到吐个槽

## V1.1

- 移动 sitemap.xml,search.xml 到`static/xml`

- 新增 RSS 订阅

## V1.2

- 样式微调

- 修复一个全局搜索的 bug

# 项目配置

1. 如果使用自己的域名，`CNAME`文件里的内容请换成你自己的域名，然后 CNAME 解析到`用户名.github.com`

2. 如果使用 GitHub 的的域名，请删除`CNAME`文件,然后把你的项目修改为`用户名.github.io`

3. 修改`pages/about.md`中关于我的内容

4. 修改`_config.yml`文件，具体作用请参考注释

5. 清空`post _posts`目录下所有文件，注意是清空，不是删除这两个目录

6. 网站的 logo 和 favicon 放在了`static/img/`下，替换即可，大小无所谓，图片比例最好是 1:1

7. 如果你是把项目 fork 过去的，想要删除我的提交记录可以先软重置到第一个提交，然后再提交一次，最后强制推送一次就行了

# 使用

文章放在`_posts`目录下，命名为`yyyy-MM-dd-xxxx-xxxx.md`，内容格式如下

```yaml
---
layout: mypost
title: 标题
categories: [分类1, 分类2]
---
文章内容，Markdown格式
```

文章资源放在`posts`目录，如文章文件名是`2019-05-01-theme-usage.md`，则该篇文章的资源需要放在`posts/2019/05/01`下,在文章使用时直接引用即可。当然了，写作的时候会提示资源不存在忽略即可

```md
![这是图片](xxx.png)

[xxx.zip 下载](xxx.zip)
```
