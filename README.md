AngularJSWeb
============

AngularJS开发下一代Web应用


AngularJS是一款来自Google的前端JS框架，它的核心特性有：MVC、双向数据绑定、指令和语义化标签、模块化工具、依赖注入、HTML模板，以及对常用工具的封装，例如$http、$cookies、$location等。AngularJS框架的体积非常小，但是设计理念和功能却非常强大，值得前端开发者深入学习。
本书对AngularJS框架的核心特性做了全面的介绍，包括常用的开发工具和开发环境。作为国内第一本关于AngularJS的书籍，本书是学习AngularJS的必备入门工具。


*前言 . vii
**第1 章 AngularJS 简介 . 1
一些概念 . 2
客户端模板  2
Model View Controller（MVC） . 3
数据绑定  4
依赖注入  5
指令  6
实例：购物车 . 6
接下来 . 9
第2 章 AngularJS 应用骨架 .11
调用Angular . 11
加载脚本  11
使用ng-app 声明Angular 的边界  12
Model View Controller  12
模板和数据绑定  15
显示文本  16
表单输入  16
浅谈非入侵式JavaScript  19
列表、表格以及其他迭代型元素 . 22
隐藏和显示  24
CSS 类和样式 . 25
反思src 和href 属性  27
表达式  28
区分UI 和控制器的职责  28
利用$scope 暴露模型数据 . 29
使用$watch 监控数据模型的变化 . 30
watch() 中的性能注意事项 . 33
使用Module（模块）组织依赖关系  35
我需要多少个模块呢  38
使用过滤器格式化数据 . 39
使用路由和$location 切换视图  40
index.html . 41
list.html  42
detail.html  42
controllers.js . 42
与服务器交互 . 43
使用指令修改DOM  45
index.html . 46
controllers.js . 46
校验用户输入 . 47
继续前进 . 48
第3 章 使用AngularJS 进行开发 .49
项目结构 . 49
工具  52
各种IDE  52
运行你的应用 . 53
使用Yeoman  53
不使用Yeoman . 54
AngularJS 下的测试  54
Karma . 55
单元测试 . 57
端到端/ 集成测试 . 58
编译  60
其他好用的工具  62
调试  62
Batarang . 62
Yeoman ：优化你的工作流程  65
安装Yeoman  66
运行服务器  66
添加新的路由、视图和控制器 . 66
关于测试  67
构建项目  67
与RequireJS 集成 . 68
第4 章 一款AngularJS 应用剖析 .77
应用  77
模型、控制器和模板之间的关系  78
模型  79
控制器、指令及服务  80
服务  80
指令  84
控制器  86
模板  90
测试  96
单元测试  96
场景测试  100
第5 章 与服务器交互 .101
利用$http 进行通信  101
进一步配置请求 . 103
设置HTTP 头 . 104
缓存响应  105
转换请求和响应 . 106
单元测试 . 107
使用RESTful 资源  108
声明  111
自定义方法  111
别用回调！（除非你真的需要它们） . 112
简化服务端操作 . 112
ngResource 单元测试 . 113
$q 和Promise  114
拦截响应 . 115
安全性措施 . 116
JSON 漏洞  116
XSRF  117
第6 章 指令 119
指令和HTML 校验 . 119
API 概览 . 120
为你的指令命名 . 121
用来定义指令的对象  122
内嵌  126
compile 和link 函数 . 126
作用域  128
操作DOM 元素  132
控制器  134
继续前进 . 137
第7 章 其他注意点 139
$location . 139
HTML5 模式和Hashbang 模式  142
AngularJS Module 类的方法 . 145
Main 方法在哪里  145
加载和依赖  146
快捷方法  146
使用$on、$emit 和$broadcast 在作用域之间进行交互 . 149
Cookies . 150
国际化和本地化  151
在AngularJS 里面应该怎么做 . 152
怎样才能让一切运行起来呢  152
常见问题  153
HTML 无害化和Sanitize 模块  153
Linky  155
第8 章 速查和技巧 157
封装jQuery Datepicker . 157
ng-model  159
绑定select  159
调用select  159
例子中的其他内容 . 160
Teams List 应用：过滤器和控制器的交互  161
搜索框  165
下拉框  165
复选框  165
迭代器  165
AngularJS 中的文件上传  166
使用Socket.IO  169
简单的分页服务  172
与服务端协作及登录  175
结论  179
索引 .181
