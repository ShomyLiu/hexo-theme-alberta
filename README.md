A new theme for [Hexo] based on [Alberta](https://github.com/ken8203/hexo-theme-alberta/).

- [Preview](http://selfboot.cn/)

## Installation

### Install

``` bash
$ git clone https://github.com/xuelangZF/hexo-theme-alberta.git themes/alberta
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
    author: selfboot
    email: xuezaigds@gmail.com
    site: http://selfboot.cn

# donate 
donate:
  enable: true
  text: 欣赏此文？支持一下吧
  wechat: http://xuelangzf-github.qiniudn.com/weixin.jpg
  alipay: http://xuelangzf-github.qiniudn.com/zhifubao.jpg
```

- **menu** - Navigation menu, you need to `hexo new page 'about'` for the about page.
- **menu_icon** - Navigation icon
- **rss** - RSS link
- **excerpt_link** - "Read More" link at the bottom of excerpted articles. `false` to hide the link.
- **google_analytics** - Google Analytics ID
- **copyright** - Setting about copyright.  Can add `copyright: false` to disable copyright in one specified post.
- **donate** - Setting about donate.  Can add `donate: false` to disable copyright in one specified post.


