# 订阅阅读器测试项目

使用测试框架Jasmine测试订阅阅读器。

## 参考
- [Jasmine](http://jasmine.github.io/2.1/introduction.html)

## 如何运行
- 下载该文件
- 打开文件夹
- 使用浏览器打开index.html文件
- 屏幕中会显示测试结果

## 测试内容
** RSS Feeds 
- 所有的源来保证有链接字段而且链接不是空的
- 所有的源来保证有有名字字段而且不是空的
** The menu
- 保证菜单元素默认是隐藏的
- 保证当菜单图标被点击的时候菜单会切换可见状态
** Initial Entries
- 保证 loadFeed 函数被调用而且工作正常
** New Feed Selection
- 保证当用 loadFeed 函数加载一个新源的时候内容会真的改变

