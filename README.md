# hexo-theme-jelly

 A wonderful, elegant and eye-protected light theme for hexo. Adapted from two previous themes, [Yilia](https://github.com/litten/hexo-theme-yilia) and [smackdown](https://github.com/smackgg/hexo-theme-smackdown), it has made lots of changes in the UI, fixed some bugs and added other features.

## Preview

### Site

[preview site](https://preccrepad.github.io/)

### Screenshots

<img src="https://i.loli.net/2021/07/30/kRNe5HVwBFYs2US.png" alt="preview1.png" style="zoom:50%;" />



<img src="https://i.loli.net/2021/07/30/2Mzt45ZIVc6XAPQ.png" alt="preview2.png" style="zoom:50%;" />



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
  # rss: "/atom.xml"
  # zhihu: "#"
  # weibo: "#"
  # douban: "#"
  # facebook: "#"
  # google: "#"
  # twitter: "#"
  # linkedin: "#"

# Set rss to false to disable feed link
# Leave rss as blank to use site's feed link, and install hexo-generate-feed
# Set rss to specific value if you have burned your feed already
rss: /atom.xml

# you can modify the value of excerpt_link to whatever you like
excerpt_link: learn more
fancybox: true
mathjax: false

# enable the animation effect, recommended
animate: true

# whether to open the link in the new window
open_in_new: false

favicon: /img/favicon.ico

# your avatar's url
avatar: 

# NetEase Cloud Music (wangyiyun of course)
music:
  enable: false
  # id of a certain music on NetEase Cloud Music
  id: 

# if you need to enable disqus, set 'disqus_shortname' to your disqus username
# disqus_shortname:

# whether to enable tagcloud
tagcloud: true

# whether to enable leancloud to count visitors
leancloud_visitors:
  enable: false
  app_id: your_app_id
  app_key: your_app_key

# whether to enable the friend links, if not, set 'friends' to false and do not add any link
# friends: false
friends:
  github: https://github.com/
# a brief introduction to yourself
aboutme: I'm a developer.

```

Uncomment the lines that are commented out in the `_config.yml` file according to your needs.

Use `<!-- more -->` to specify which part to be revealed in the home page.

Add a `.jpg` picture and rename it `bg.jpg` and put it in the `themes/jelly/source/img` as your background picture (must be that name, or you should change the name in the `style.styl` file in the css directory).

## Recent Update



## Bug fixed

2021.7.30 - table display overflow



