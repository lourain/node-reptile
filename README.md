# nodejs爬取av资源 #

>nodejs的一个小玩具，才入门node，昨天看到别人用python爬了个av网站，于是我也试着用node来尝试下。

## 分为两种模式 ##

> 1.首页最新资源 
> 2.选择制定的av序号，按顺序下载 

**安装模块**

    npm install
        
### 1.首页最新资源模式(快速上手) ###

    node index.js
    
> 补充：如果想要当前此刻最新的资源的话，请先执行如下代码，会将首页资源插入到数据库中，再执行index.js文件

    node url.js
    
### 2.选择制定的av序号，按顺序下载 ###

> 这个模式会有两个参数：第一个为你想从第几部开始下载，第二个为往后下载多少部，比如从第50部开始，往后下载2部：

    node index.js 50 2

