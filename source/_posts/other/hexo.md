---
title: hexo 标签不显示问题
tags: 
- hexo
---

## tags 标签不显示

* 新建一个页面，命名为 tags 。命令如下：

```bash
hexo new page "tags"
```

* 编辑刚新建的页面，将页面的类型设置为 tags ，主题将自动为这个页面显示标签云。页面内容如下：(type: "tags" 一定要加引号) 

    title: 标签
    date: 2018-09-07 11:45:56
    type: "tags"
    comments: false

* 在菜单中添加链接。编辑 主题配置文件 ，添加 tags 到 menu 中，如下:

``` yml
menu:
  home: /
  archives: /archives
  tags: /tags
```