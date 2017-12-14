# RSS 订阅器

基于 Web 的 RSS 反馈阅读 应用程序

# 如何添加源

打开 `js/app.js` 给数组添加一个 包含名称和链接的源对象

 ```
 var allFeeds = [
     {
         name: 'Udacity Blog',
         url: 'http://blog.udacity.com/feed'
     }, {
         name: 'CSS Tricks',
         url: 'http://feeds.feedburner.com/CssTricks'
     }
 ];
 ```
