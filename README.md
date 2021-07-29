# hexo-theme-jelly

 A wonderful, eye-protected light theme for hexo. Adapted from two previous themes, [Yilia](https://github.com/litten/hexo-theme-yilia) and [Smackdown](https://github.com/smackgg/hexo-theme-smackdown), it has made some changes in the UI.

 ## Installation method

 ```
 git clone https://github.com/preccrep/hexo-theme-jelly.git themes/jelly
 ```

## Config

Modify the `_config.yml` file in your blog's root directory:

```
theme: jelly
```

## Update

Enter your blog's root directory in the terminal, and

```
cd themes/jelly
git pull
```

## Theme Config

The theme config file is in the `themes/jelly` directory. Open the `_config.yml` file and you will see:

```yaml
# Header
menu:
  Home: /
  Archives: /archives

# links with icon in the left-column bar
subnav:
  # github: "#"
  # mail: "#"
  # rss: "#"
  # zhihu: "#"
  # weibo: "#"
  # douban: "#"
  # facebook: "#"
  # google: "#"
  # twitter: "#"
  # linkedin: "#"

# it is the relative path of the .xml file, the default path is in the source directory
rss:

# you can modify the value of excerpt_link to what you like
excerpt_link: learn more
fancybox: true
mathjax: true

# open the animation effect, true recommended
animate: true

# whether to open the link in the new window
open_in_new: false

# 百度统计、谷歌统计
# baidu_tongji: true
# google_analytics: true

favicon: /img/jelly.png

# your avatar's url
avatar: /img/avatar.jpeg



#是否开启多说评论，填写你在多说申请的项目名称 duoshuo: duoshuo-key
#若使用disqus，请在博客config文件中填写disqus_shortname，并关闭多说评论
# duoshuo: your duoshuo id

# 是否开启云标签
tagcloud: true

# 是否开启文章阅读量
leancloud_visitors:
  enable: false
  app_id: your_app_id
  app_key: your_app_key

# 是否开启友情链接
# 不开启
# friends: false
# 开启
friends:
  github: https://github.com/
# 是否开启“关于我”
aboutme: I'm an engineer.

```

Uncomment the lines that are commented out in the `_config.yml` file according to your needs.

Use `<!-- more -->` to specify which part to be revealed in the home page.

## Recent Update



## Bug fixed





