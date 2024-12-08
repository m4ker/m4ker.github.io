# Node.js 常用模块汇总

## Web

- express
- koa

## 工具库

- underscore
- lodash



## Web Socket

- socket.io

## ORM

- sequalize

## 模板引擎

- Jade
- ejs
- twig

## REST

- Restify

## Web 爬虫

- Cheerio/Request

## Blog

- hexo

## BBS

- nodeclub

## Web 幻灯片

- Cleaver

## Oauth 认证

- Passport

## 定时任务

- cron ？
- later

## 浏览器环境

- browserify




## DB

- mongoose
- redis ?
- mysql ?

## html 解析器
- zombie


## 客户端
backbone
angular
metor


log4js

Connect 中间件

- co 
- n

gulp
grund

测试

forever

tty.js

Retry 重试策略
Marked


Less
Stylus
Sass

Uglify 文件压缩

Layzr 图片延迟加载

fancybox

commander 命令行程序

wind.js  异步编程


moment

bower


1、underscore 3820 packages
提供set的交、并、差、补，提供简单的模版算法，提供各种排序。

2、async 2912 packages
异步库，具体说起来可以用一本书来说

3、request 2474 packages
HTTP请求库，缓存、并发、多客户端，写client以及各种爬虫都会依赖的库

4、optimist 1831 packages
命令行解析库

5、express 1821 packages
http server？过于低级，还是用一下express，能让你的生命美好一些，中等复杂度

6、commander 1692 packages
类似于optimist

7、coffee-script 1620 packages
coffee-script

8、colors 1290 packages 
unix终端下显示颜色的库，利于调试和一些特殊场景

9、mkdirp 910 packages
一次性建立目标文件夹，而不是mkdir...cd...mkdir...cd...mkdir这样的模式

10、lodash 901 packages
类似于underscore，更轻量级，更快

11、uglify-js 804 packages
js的压缩器

12、jade 730 packages
express的一个主要模板引擎

13、socket.io 706 packages
webscoket通讯，node.js实现的准官配

14、connect 689 packages
express中间件

15、redis 669 packages
redis的client

16、debug 642 packages
debug辅助模块

17、q 595 packages
异步promise库

18、mime 552 packages
MIME处理库

19、glob 542 packages
通配符文件列表模块

20、node-uuid 527 packages
生成uuid的模块

21、moment 491 packages
时间处理模块，生成类似于：发表于12分钟前这类的string

22、winston 444 packages
调试、log类模块

23、through 442 packages
对stream的封装类

24、ejs 423 packages
express的另一个模板类

25、mongodb 421 packages
mogondb的client

26、mongoose 393 packages
mogondb的client

27、grunt 374 packages
前端构建工具

28、less 353 packages
前端构建工具

29、stylus 346 packages
前端构建工具

30、xml2js 339 packages
较为严格的将xml=>js对象的类

31、cheerio 338 packages
jquery的node.js轻量级实现

32、handlebars 337 packages
Mustache无逻辑模版语言的实现

33、semver 327 packages
npm以及package.json解析版本号时的辅助模块，更为语义化

34、jsdom 324 packages
cheerio的重量级严格实现

35、marked 323 packages
markdown实现

36、wrench 314 packages
递归文件、文件夹操作一体化解决方案

37、pkginfo 300 packages
包信息解析器

38、yeoman-generator 293 packages
yeoman的生成器

39、mocha 287 packages
mocha测试框架

40、rimraf 276 packages
rm -rf

41、underscore.string 274 packages
unserscore的string扩展

42、js-yaml 219 packages
yaml操作类

43、backbone 217 packages
backbone框架

44、browserify 203 packages
js压缩器

45、esprima 197 packages
ECMAScript解析器

46、nopt 197 packages
opt解析

47、mysql 193 packages
mysql的client

48、superagent 182 packages
http request库

49、ws 179 packages
webscoket库

50、oauth 173 packages
oauth认证库

51、readable-stream 173 packages
stream处理库

52、cli-color 171 packages
color库

53、prompt 171 packages
提示符库

54、http-proxy 168 packages
http的一个proxy

55、minimatch 168 packages
通配符实现

56、fs-extra 167 packages
文件操作相关工具库

57、hiredis 167 packages
c的redis client，官配库hiredis的node绑定，redis库可选安装，自动使用

58、jquery 164 packages
jquery实现

59、nconf 164 packages
conf，配置文件管理库

60、should 162 packages
测试框架should

61、passport 159 packages
认证类集合工具库

62、validator 158 packages
后端验证库

63、nodemailer 153 packages
邮件库

64、eventemitter2 152 packages
事件库

65、qs 148 packages
querystring

66、clean-css 147 packages
css库

67、temp 145 packages
临时文件操作库

68、requirejs 142 packages
加载辅助库

69、step 141 packages
异步串行化

70、npm 140 packages
npm

71、when 138 packages
又一个promise库

72、mustache 137 packages
mustache模版库

73、inherits 136 packages
继承工具库

74、shelljs 134 packages
shell化

75、socket.io-client 134 packages
socket.io的node client

76、watch 128 packages
watch库

77、xtend 128 packages
扩展js object的工具类库，兼容各种游览器

78、passport-oauth 127 packages
认证类库

79、nib 124 packages
Stylus工具

80、bindings 123 packages
绑定类库时的帮助类

81、vows 122 packages
异步测试框架vows

82、dateformat 121 packages
处理各类日期的函

83、formidable 121 packages
处理form的工具类

84、chai 120 packages
测试框架

85、log4js 120 packages
日志库

86、pg 118 packages
pg的client

87、tar 116 packages
打包工具类

88、hogan.js 113 packages
mustache编译器

89、canvas 111 packages
canvas的服务端实现

90、ncp 109 packages
递归文件拷贝

91、consolidate 108 packages
模版类

92、event-stream 105 packages
事件类，stream辅助

93、knox 103 packages
Amazon的S3 client

94、sprintf 103 packages
sprintf的node.js版

95、findit 102 packages
递归遍历目录树工具类

96、jshint 102 packages
js静态分析器

97、required-keys 102 packages
js object，key检查器

98、escodegen 100 packages
ECMAScript代码生成

99、node-static 98 packages
静态文件服务器

100、nodeunit 98 packages
单元测试框架


