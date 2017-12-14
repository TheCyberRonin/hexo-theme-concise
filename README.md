# Concise

### Premise

The theme uses less compilation, but Hexo uses  [hexo-renderer-stylus](https://github.com/hexojs/hexo-renderer-stylus). Download [hexo-renderer-less](https://github.com/hexojs/hexo-renderer-less) and uninstall hexo-renderer-stylus
```bash
$ npm install hexo-renderer-less --save
```

If you're not using `hexo-renderer-stylus`,  uninstall it with: 
```bash
$ npm uninstall hexo-renderer-stylus --save
```

### Installation

``` bash
$ git clone https://github.com/TheCyberRonin/hexo-theme-concise.git themes/concise
```

**This theme requires Hexo 2.4 or higher**

### Initial setup

1. In the `_config.yml` file, change the  `theme` to `concise`.
2. Copy the `themes/concise/_config.example.yml` config file and rename it to `themes/concise/_config.yml`

### Update

``` bash
cd themes/concise
git pull
```

## Config

Modify `themes/concise/_config.yml`

``` yml
# Content
excerpt_link: Read more

# Sidebar
author:
  name: #your name
  work: #what you do(profession)
  location: #location

# Disqus 
disqus:
  enable: true
  shortname:  #short name from Disqus
  # count: true
```

- **excerpt_link** - Read more display text
- **sidebar** - Configure owner display information on the sidebar
- **Disqus** - In order to use comments, you need to register on [Disqus](https://disqus.com/) yourself and get the shortname.

You can disable comments on a single article by setting `comments` to  `false`, it's `true` by default：
```md
---
title: Hello World
date: 2017-10-20 20:00:00
comments: true
---
```
