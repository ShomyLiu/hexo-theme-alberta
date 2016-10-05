
修改如下:
- 加入每篇文章的toc
- 加入标签&分类页面, 关于
- 加入leancloud 阅读量统计

---
A new theme for [Hexo] based on [Alberta](https://github.com/ken8203/hexo-theme-alberta/).

- [Preview](http://shomy.cn/)

## Installation

### Install

``` bash
$ git clone git@github.com:ShomyLiu/hexo-theme-alberta.git
```

### Enable

Modify `theme` setting in `_config.yml` to `alberta`.

## Configuration

``` yml
# Header
menu:
  Home: /
  Archives: /archives
  About: /about
rss: /atom.xml

# Menu Icon
menu_icon:
  Home: fa-home
  Archives: fa-archive
  About: fa-user

# Content
excerpt_link: Read More


# Personal Image
your_img: your_image_url

# Miscellaneous
google_analytics:
favicon: /favicon.png
google_plus:

# copyright
copyright:
    enable: true
    author: Shomy
    email: shomyliu@gmail.com
    site: http://shomy.top

```

- **menu** - Navigation menu, you need to `hexo new page 'about'` for the about page.
- **menu_icon** - Navigation icon
- **rss** - RSS link
- **excerpt_link** - "Read More" link at the bottom of excerpted articles. `false` to hide the link.
- **google_analytics** - Google Analytics ID
- **copyright** - Setting about copyright.  Can add `copyright: false` to disable copyright in one specified post.
- **donate** - Setting about donate.  Can add `donate: false` to disable copyright in one specified post.
