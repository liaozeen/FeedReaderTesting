## 项目简介

本项目使用Jasmine来为RSS阅读器编写测试用例，用于检测应用代码运行是否符合预期。

## 如何运行项目

1.[下载项目到本地](https://github.com/liaozeen/FeedReaderTesting/archive/master.zip)，并解压

2.打开index.html，运行项目。在页面最下面可以看到用Jasmine测试的结果

3.本项目的测试用例有：
#### RSS源的定义，即应用中的 allFeeds 变量
- 测试allFeeds是否被定义并且不是空的
- 测试allFeeds的属性url是否被定义并且不是空的
- 测试allFeeds的属性name是否被定义并且不是空的

#### 菜单栏的测试
- 测试菜单栏默认是隐藏的
- 测试当菜单图标被点击时会切换可见状态，再次点击时切换到隐藏状态

#### 测试loadFeed 函数
- 测试loadFeed 函数是否被调用而且工作正常
-测试loadFeed 函数加载一个新源时内容会改变

4.打开 jasmine/spec/feedreader.js ,可查看测试用例代码