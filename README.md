## GitHub + jekyll 搭建Blog

为项目创建Github Pages，利用现有主题，快速创建。

**一次成功的操作步骤：**

1. 在GitHub上新建项目 `jekyll-demo`，
然后我们为这个项目创建Github Pages，（这里不是为用户）
2. （可选）在本地安装所需软件，[安装 - Jekyll • 简单静态博客网站生成器](http://jekyllcn.com/docs/installation/ "安装 - Jekyll • 简单静态博客网站生成器")   参考这里，安装4个软件。   
3. 打包下载主题： < https://github.com/streetturtle/jekyll-clean-dark.git> ，更多主题见 [Jekyll Themes](http://jekyllthemes.org/ "Jekyll Themes")
4. 更改该主题的配置文件： `_config.yml`
  ```
  url: http//faner.gitlab.io
  # 下面的路径该为你的项目路径
  baseurl: `/jekyll-demo`
  # GitHub 图标指向自己
  github: fandean
  ```
5. 进入主题文件夹：`git init`初始化git仓库，
6. 创建分支： `git branch gh-pages`；该项目的github pages文件需位于gh-pages分支中  
7. 跟踪所有文件: `git add .`  
8. 提交： `git commit -m "my jekyll"`    
9. 添加远程仓库：(改为自己的地址)`git remote add origin https://github.com/FanDean/fandean.github.io.git`    
10. 推送本地git库到远程仓库： `git push origin gh-pages` 
11. 在浏览器输入`fandean.github.io/jekyll-demo` 即可打开网站。

之后的博客文章在`_post`文件夹中更新、添加即可。


