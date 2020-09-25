hexo-theme-freemind.386.second

### 基于`hexo-theme-freemind.386`二次封装的hexo主题。
===

* [Demo](https://www.liuguisheng.vip/)
* [使用说明](https://www.liuguisheng.vip/2020/01/09/%E7%A8%8B%E5%BA%8F%E5%91%98%E6%A0%87%E9%85%8D-%E4%BD%BF%E7%94%A8hexo-github%E6%90%AD%E5%BB%BA%E4%B8%AA%E4%BA%BA%E5%8D%9A%E5%AE%A2/)

## 版本要求 ##

* Hexo >= 3.0
* [hexo-tag-bootstrap](https://github.com/wzpan/hexo-tag-bootstrap) >= 0.0.8 (optional)


## 更新说明 ##

- 添加了`gitalk`评论系统。[添加方法](https://www.liuguisheng.vip/2020/09/25/hexo%E5%8D%9A%E5%AE%A2%E6%B7%BB%E5%8A%A0gitalk%E8%AF%84%E8%AE%BA%E7%B3%BB%E7%BB%9F/)



## 使用方法 ##

1) 初始化主题:

``` 
$ git clone git@github.com:qisi007/hexo-theme-freemind.386.second.git
```

2) 拷贝主题到博客目录的`themes`目录下，并更名为`freemind`

3) 下载 [hexo-tag-bootstrap](https://github.com/wzpan/hexo-tag-bootstrap):

``` sh
$ npm install hexo-tag-bootstrap --save
```

4) 下载 [hexo-generator-search](https://github.com/paichyperiondev/hexo-generator-search):

``` sh
$ npm install hexo-generator-search --save
```

5)初始化所有依赖

``` sh
$ cd freemind
$ npm install 
```


## 更新主题 ##

``` sh
$ cd themes/freemind
$ git pull
```

## hexo基本命令 ##

描述 | 命令 | 缩写
--- | --- | --- 
生成静态页面 | hexo generate | hexo g
开启服务 | hexo server | hexo s
部署到github | hexo deploy | hexo d
新建文章 | hexo new "articleName" | -
新建页面 | hexo new page "htmlName" | -
查看帮助 | hexo help | - 
查看hexo版本号 | hexo version

## 组合命令 ##
描述 | 命令 |
--- | --- |  
生成页面并预览 | hexo s -g | 
生成页面并上传到github | hexo d -g | 



图标更换地址： https://www.bootcss.com/p/font-awesome/#