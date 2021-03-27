# Hacker Me Web

## Web 安全基础

### HTML

#### HTML开发工具 

- Visual Studio Code
- Atom
- Sublime Text
- Vim

![1616830983487](HackerMeWeb.assets/1616830983487.png)

- 前端开发是创建Web页面或App等前端界面呈现给用户的过程。
  - HTML，CSS 及 JavaScript
- 网页制作是Web1.0时代的产物，早期网站主要内容都是静态，以图片和文字为主，用户使用网站的行为也以浏览为主。
- 随着互联网技术的发展和HTML5、CSS3 的应用，现代网页更加美观，交互效果显著，功能更加强大。 



#### HTML入门介绍 

- 为什么前后端分离？
  - 性能问题 & 学习成本
  - 将原本服务端的得计算，转移到用户端
- 前后端的走向？
  - 前端：页面表现，速度流畅，兼容性，用户体验等等
  - 后端：三高（高并发，高可用，高性能），安全，存储，业务等等 
- HTML 是什么？
  - HTML（ HyperText Markup Language）即超文本标记语言，是用来构建网页的一种语言。
  - HTML是一整套标记标签构成的标记语言，而非编程语言。
  - HTML用于承载网页的内容（文本、图片、语音、视频）。
- 通俗的讲：
  - 使用HTML标记标签与纯文本按规则构建的文档，通常也称为网页。 
- 文档—>网页
  - 浏览器通过对HTML文档解析，根据标签的顺序，按指定标签对应的规则显示纯文本内容。 



#### HTML网页结构 

- 一个标准的HTML页面由以下三个部分组成:
  - ① HTML版本声明
  - ② HTML头部
  - ③ HTML主体 

![1616831716511](HackerMeWeb.assets/1616831716511.png)

- HTML版本声明 :
  - 标签<!DOCTYPE html>
  - 它不是 HTML 标签，而是指示web 浏览器关于页面使用哪个 HTML 版本进行编写的指令。 
- HTML头部部分:
  - 标签 <head> </head>
  - 涉及页面标题、字符集、样式、链接等内容

```html
<titile> 页面标题必须存在
<base>   为所有链接指定默认地址
<link>   定义文档与外部资源之间的关系
<style>  定义样式信息
<script> 定义客户端脚本，比如 JavaScript
<meta>   定义关于 HTML 文档的元数据，用于规定页面的描述、关键词、文档的作者等。搜索引擎引擎会利meta元素的 name 和 content 属性来索引页面。 
```

- HTML主体部分：
  - 标签<body></body>
  - 浏览器展现给用户的内容，包括标题、文本、段落、链接、图片、媒体等，所有的页面内容都由HTML主体部分标签来实现。 
  - 标签之间可按照规则嵌套。 

```html
<p>hello</p>           标识一个段落
<a href=“url”>text</a> 标识一个链接文本
<ol><ul><li>           列表项相关
<table><tr><td>        表格项相关
<img>                  标识一个图片信息
<b><i>                 字体相关标签
<form><input>          表单相关标签
```



#### HTML标签/元素/属性 

- 标签
  - HTML页面由标签和内容组成，标签一般是成对出现，由开始和结束标签组成，如：


```html
<p></p>
<img/>
```

- 元素
  - HTML元素指的是开始标签到结束标签的所有代码，包括开始结束标签，如：

```html
<p>hello</p>
```

- 属性
  - 属性一般描述于开始标签中，用于对元素提供附加信息如：

```html
<img src=“image/geektime.png” width=30% height=30% alt=“图片加载失败" />
```



#### HTML练习

- github：HackerMeCode\HTML\HTMLDemo1.html
- github：HackerMeCode\HTML\HTMLDemo2.html



#### HTML学习资料

- https://developer.mozilla.org/zh-CN/docs/Web/HTML



### CSS

#### CSS入门介绍 

- 层叠样式表（英文全称：Cascading Style Sheets）是一种用来表现HTML（标准通用标记语言的一个应用）或 XML（标准通用标记语言的一个子集）等文件样式的计算机语言。
- CSS 能够对网页中元素位置的排版进行像素级精确控制，支持几乎所有的字体字号样式，拥有对网页对象和模型样式编辑的能力。 



#### CSS学习资料

- https://developer.mozilla.org/zh-CN/docs/Web/CSS



### JavaScript

#### JavaScript入门介绍 

- JavaScript是什么？
  - JavaScript，是可插入 HTML 页面，可以由绝大多数现代浏览器执行的轻量级的编程语言。
  - JavaScript 基于原型编程、多范式的动态脚本语言，并且支持面向对象、命令式和声明式（如函数式编程）风格。
- 它和Web安全有什么关系？
  - 作为一种脚本语言，由它引申出的 XSS 攻击，文件上传漏洞，常年占据 OWASP Top10。
- Node.js
  - 简单的说 Node.js 就是运行在服务端的 JavaScript。
  - Node.js 是一个基于Chrome JavaScript 运行时建立的一个平台。
  - Node.js 是一个事件驱动 I/O 服务端 JavaScript 环境，基于 Google 的 V8 引擎，V8 引擎执行 Javascript 的速度非常快，性能非常好。 
- JavaScript 功能 
  - ① 做出反应 
  - ② 改变HTML内容 
  - ③ 改变HTML样式 
  - ④ 验证输入 



#### JavaScript练习

- github：HackerMeCode\JavaScript\JavaScriptDemo.html



#### JavaScript学习资料

- JavaScript：https://developer.mozilla.org/zh-CN/docs/Web/JavaScript
- Node.js：https://developer.mozilla.org/zh-CN/docs/Glossary/Node.js





### Web App

#### Web App是什么？

- Web App（或Web应用程序）运行于网络和标准浏览器上，基于网页技术开发实现特定功能的应用。
  - 前端：HTML，CSS，JavaScript
  - 后端：Java，Python，PHP
  - 数据库：MySQL，Oracle，MongoDB
  - 容器：Windows(IIS)，Linux(Nginx, Apache)
  - 协议：TCP，DNS，HTTP，HTTPS 
  



#### 从浏览器输入网址到看到网页，这个过程发生了什么？ 

  - 用户： 
    - 浏览器输入了一个地址 
    - 浏览器显示了一个网页 
- 显示网页的原理：
  - 客户输入URL，DNS解析URL得出IP地址，根据IP地址找出对应服务器
  - 客户机通过TCP/IP协议建立到Web服务器的TCP链接
  - 客户机向Web服务器发送HTTP请求报文，请求服务器里资源的资源文档
  - Web服务器接收到客户机的HTTP请求报文，然后向客户机发出HTTP响应报文 
  - 如果请求的是HTML文档，Web服务器会将对应目录下相应的HTML文档打开，然后将文档的响应内容发送给客户机。
  - 如果请求的是PHP文件，那么Web服务器自身是不能处理PHP动态语言脚本文件的，然后就会寻找并委托PHP应用服务器，PHP应用服务器会将Web服务器请求的PHP文件解析成HTML静态代码，然后将HTML静态代码发送给Web服务器，最后Web服务器会将HTML静态代码发送客户机。
  - 如果请求的资源是访问数据库，则Web服务器会通过PHP应用服务器去访问数据库。 
  - 客户机解析HTML静态文档
  - 客户机与服务器断开链接 



#### 常见的 Web 服务器有哪些？

  - Apache HTTP Server（简称Apache）是Apache软件基金会的一个开放源代码的网页服务器软件，可以在大多数电脑操作系统中运行，由于其跨平台和安全性被广泛使用，是最流行的Web服务器软件之一。
  - Nginx（发音同engine x）是一个网页服务器，它能反向代理HTTP, HTTPS, SMTP, POP3, IMAP的协议链接，以及一个负载均衡器和一个HTTP缓存。Nginx是一款面向性能设计的HTTP服务器，相较于Apache、lighttpd具有占有内存少，稳定性高等优势。
  - IIS是Internet Information Server的缩写。它是微软公司主推的服务器。
  - Lighttpd是一个德国人领导的开源Web服务器软件,具有非常低的内存开销、CPU占用率低、效能好以及丰富的模块等特点。
  - Tomcat是Apache软件基金会的Jakarta项目中的一个核心项目，由Apache、Sun和其他一些公司及个人共同开发而成。Tomcat技术先进、性能稳定，而且免费，因而深受Java爱好者的喜爱并得到了部分软件开发商的认可，成为目前比较流行的Web应用服务器。 

​    

#### Python实现简单服务器 

- 程序，参见：github：HackerMeCode\WebApp\python_imple_server.py
- 执行命令：python python_imple_server.py
- 不同浏览器显示了不同的控制台结果：
  - Chrome Browser
  - Firefox Browser
  - Microsoft Edge Browser



#### 什么是框架

- Web应用框架（Web application framework）是一种开发框架，用来支持动态网站、网络应用程序及网络服务的开发。其类型有基于请求的和基于组件的两种框架。
- 有助于减轻网页开发时共通性活动的工作负荷，例如许多框架提供数据库访问接口、标准样板以及会话管理等，可提升代码的可再用性。 
- 提供了某应用领域通用完备功能（除去特殊应用的部分）的底层服务的程序集合。 
  - 前端：jQuery、Bootstrap、React.js、Vue.js
  - 后端：Spring MVC、Django、Flash、Tornado



#### Python建站 

























