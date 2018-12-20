# zblog

## 项目介绍
zblog-hexo

#### zblog博客地址
    http://zuot.gitee.io/zblog

####
    hexo


#### hexo博客 安装教程
    
    npm install hexo --save
    npm install hexo-server --save
    
    配置 hexo s 后页面空白
    npm install hexo-renderer-ejs --save
    npm install hexo-renderer-stylus --save
    npm install hexo-renderer-marked --save
    
    配置git
    npm install --save hexo-deployer-git
    
    aath 主题依赖
    npm install --save hexo-renderer-sass
    


### 部署命令
#### 提交gitee
    hexo clean && hexo g && hexo d

#### 清理&编译&启动服务
    hexo clean && hexo g && hexo s

#### 然后打开页面显示的是：
    <%- partial('_partial/head') %> <%- partial('_partial/header') %>
    <%- body %> <% if (theme.sidebar && theme.sidebar !== 'bottom'){ %>
    <%- partial('_partial/sidebar') %> <% } %> <%- partial('_partial/footer') %>
    <%- partial('_partial/mobile-nav') %> <%- partial('_partial/after-footer') %>
    原因： Hexo无法解析模板文件
    解决方案： 使用以下的命令
    npm install hexo-renderer-ejs --save
    npm install hexo-renderer-stylus --save
    npm install hexo-renderer-marked --save
#### 白板和Cannot GET / 几个字
    原因：
    由于2.6以后就更新了，我们需要手动配置些东西，我们需要输入下面三行命令：
    npm install hexo-renderer-ejs --save
    npm install hexo-renderer-stylus --save
    npm install hexo-renderer-marked --save

#### GitHub 域名解析

zsatot
/
zlove.github.io
zsatot
/
zwww.github.io

satott
/
tozuo.github.io
satott
/
tzuo.github.io


tozuo
/
zlink.github.io
tozuo
/
tblog.github.io


