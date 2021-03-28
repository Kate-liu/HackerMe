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

- 什么是Django 

  - Django是一个开放源代码的Web应用框架，由Python写成。
  - 采用了MTV的框架模式，即模型M（Model），视图V（View）和模版T（Template）。
  - 它最初是被开发来用于管理劳伦斯出版集团旗下的一些以新闻内容为主的网站的，即CMS（内容管理系统）软件。并于2005年7月在BSD许可证下发布。 

- 创建第一个项目 

  - 安装Django环境
    - Python –m pip install django
  - 创建第一个项目
    - django-admin startproject mysite
  - 命令行命令
    - ls -l
    - dir
    - tree ./
    - cd mysite/
  - 启动
    - python manage.py runserver 0.0.0.0:8000

- 项目文件介绍：

  - manage.py
    - Django用于管理本项目的命令行工具。
  - _\_init__.py
    - 一个普通的包初始化模块。
  - settings.py
    - Django项目的配置文件 ， 本项目引用的组件，项目名， 数据库配置， 时间、语言 ，静态文件访问地址和存储路径。
  - wsgi.py 
    - Web Server gateway interface
    - 接口信息用于服务器部署。 

- Django应用注册及建立 

  - django-admin startapp firstapp 

  - 注册 app，添加 template 路径，开放外部主机访问权限

    - mysite/settings.py

      - ```python
        ALLOWED_HOSTS = ['*']  # 允许外部主机访问
        
        INSTALLED_APPS = [
            'django.contrib.admin',
            'django.contrib.auth',
            'django.contrib.contenttypes',
            'django.contrib.sessions',
            'django.contrib.messages',
            'django.contrib.staticfiles',
            'mysite',  # 注册 mysite
        ]
        
        TEMPLATES = [
            {
                'BACKEND': 'django.template.backends.django.DjangoTemplates',
                'DIRS': [os.path.join(BASE_DIR, 'template')],  # 添加路径模板
                'APP_DIRS': True,
                'OPTIONS': {
                    'context_processors': [
                        'django.template.context_processors.debug',
                        'django.template.context_processors.request',
                        'django.contrib.auth.context_processors.auth',
                        'django.contrib.messages.context_processors.messages',
                    ],
                },
            },
        ]
        ```

  - Django应用添加URL映射关系 

    - firstapp/views.py
      - 添加函数
    - mysite/urls.py
      - 添加路径映射 URL
    - 启动应用
      - python manage.py runserver 0.0.0.0:8000
    - 访问
      - http://127.0.0.1:8000/helloworld

- 数据库迁移与创建账号 

  - 迁移数据，初始化数据表
    - python manage.py makemigrations 
    - python manage.py migrate 
  - 在mysite 目录下创建 管理员 账号 
    - python manage.py createsuperuser 
  - 启动应用
  - 访问
    - http://127.0.0.1:8000/admin/
    - 用户名：root
    - 密码：root



### HTTP协议基础 

#### HTTP协议是怎么工作的 

- HTTP协议定义了Web客户端如何从Web服务器请求Web页面，以及服务器如何把Web页面传送给客户端。
- 客户端连接到Web服务器
  - 一个HTTP客户端，通常是浏览器，与Web服务器的HTTP端口（默认为80）建立一个TCP套接字连接。
- 发送HTTP请求
  - 通过TCP套接字，客户端向Web服务器发送一个文本的请求报文，一个请求报文由请求行、请求头部、空行和请求数据 4部分组成。
- 服务器接受请求并返回HTTP响应
  - Web服务器解析请求，定位请求资源。服务器将资源复本写到TCP套接字，由客户端读取。
  - 一个响应由状态行、响应头部、空行（请求空行）和响应数据（请求体）4部分组成。
- 释放连接TCP连接
  - 若connection 模式为close，则服务器主动关闭TCP连接，客户端被动关闭连接，释放TCP连接。
  - 若connection 模式为keepalive，则该连接会保持一段时间，在该时间内可以继续接收请求。
- 客户端浏览器解析HTML内容 



#### HTTP协议 

- 请求方法
  - GET和POST是最常见的HTTP方法，除此以外还包括DELETE、HEAD、OPTIONS、PUT、TRACE。
  - 不过，当前的大多数浏览器只支持GET和POST
- 常见的报文头的属性有很多 

![1616894719841](HackerMeWeb.assets/1616894719841.png)



#### GET vs POST 

- 从参数的传递方面来看,GET请求的参数是直接拼接在地址栏URL的后面,而POST请求的参数是放到请求体里面的。
- 从长度限制方面来看,GET请求有具体的长度限制,一般不超过1024KB,而POST理论上没有,但是浏览器一般有个界限。
- 从安全方面来看,GET请求相较于POST,因为数据都是明文显示在URL上面的,所以安全和私密性不如POST。
- 从本质上来说，GET和POST都是TCP连接，并无实质的区别。但是由于HTTP/浏览器的限定，导致它们在应用过程中体现出了一些不同。GET产生一个数据包，POST产生两个数据包。对于GET请求，浏览器会把http header 和 data 一并发出去,服务器响应200(返回数据)。而对于POST，浏览器先发送header，服务器响应100 continue，浏览器再发送data，服务器响应200 ok。 



#### HTTP请求方法和响应代码 

![1616894968238](HackerMeWeb.assets/1616894968238.png)

![1616894988927](HackerMeWeb.assets/1616894988927.png)



### Web 安全溯源 

#### Web安全的起源 

- Web应用全部都是建立在HTTP协议基础上，是对HTTP协议的实际应用。
- Web应用在实现HTTP协议的过程中，没有做足够充足强大的约束，导致攻击者能够利用其中的薄弱环节进行攻击。 

![1616895500534](HackerMeWeb.assets/1616895500534.png)



#### Web安全攻防要点 

![1616895805998](HackerMeWeb.assets/1616895805998.png)

#### Web 安全的本质是什么 

- 应用问题？
- 协议问题？
- 都不是！！！



#### 安全溯源 

- 信任问题
  - 前端输入不可信
- Web安全根本在于，Web应用在实现HTTP协议的过程中，没有做足够充足强大的约束，导致攻击者能够利用其中的薄弱环节进行攻击。 



### Web渗透工具 

#### Burp Suite 

- Burp Suite是用于攻击Web应用程序的集成平台框架。 它包含了许多Web安全相关工具， 也同时设计了接口，满足了安全人员自行拓展程序功能的需求。 
- Burp功能
  - Proxy——是一个拦截HTTP/S的代理服务器，作为一个在浏览器和目标应用程序之间的中间人，允许你拦截，查看，修改在两个方向上的原始数据流。
  - Intruder——是一个定制的高度可配置的工具，对web应用程序进行自动化攻击，如：枚举标识符，收集有用的数据，以及使用fuzzing 技术探测常规漏洞。
  - Repeater——是一个靠手动操作来补发单独的HTTP 请求，并分析应用程序响应的工具。
  - Sequencer——是一个用来分析那些不可预知的应用程序会话令牌和重要数据项的随机性的工具。
  - Decoder——是一个进行手动执行或对应用程序数据者智能解码编码的工具。
  - Comparer——是一个实用的工具，通常是通过一些相关的请求和响应得到两项数据的一个可视化的“差异”。 
- 下载安装
  - https://portswigger.net/burp/communitydownload
- 设置代理 
  - Proxy -> Intercept -> 关闭 Intercept is on
  - Proxy -> Options -> 本地 8080端口 
  - 浏览器：选项 -> 网络设置 -> 手动配置代理 -> HTTP 代理，端口
- 设置代理 - Mac 
  - 系统偏好设置 -> 网络 -> 高级 -> 代理 -> 网页代理（HTTP）
- 代理 - Windows 
  - 网络代理管理 -> 使用代理服务器



#### curl 

- curl 是一个功能强大灵活的网络工具，使用url的形式传输数据， 支持 HTTPS，IMAP，POP3，RTSP，SCP，FTP， FTPS，TFTP， SMTP以及SMB， Telnet等协议。
- 多用于用在抓取网页、网络监控等方面的开发，解决开发中遇到的问题。 
- Mac 自带
- windows 安装
  - https://curl.se/download.html
  - 将解压路径添加至环境变量
- 命令：
  - curl www.baidu.com
  - curl www.baidu.com -I
  - man curl
  - curl -h
  - curl ifconfig.co
  - curl ifconfig.co -v
- curl 使用场景小览 
  - -A参数指定客户端的用户代理标头，即User-Agent。
  - -b参数用来向服务器发送 Cookie。
  - -c参数将服务器设置的 Cookie 写入一个文件。
  - -d参数用于发送 POST 请求的数据体。
  - -e参数用来设置 HTTP 的标头Referer，表示请求的来源。 
  - -F参数用来向服务器上传二进制文件。
  - -G参数用来构造 URL 的查询字符串。
  - -H参数添加 HTTP 请求的标头。 



#### Postman 

- Postman是一款功能强大的网页调试与发送网页HTTP请求的工具
- 不仅可以调试简单的CSS、HTML、脚本等简单的网页基本信息，它还可以发送几乎所有类型的HTTP请求
- 可视化版本的curl
- 使用非常傻瓜，所见即所得
- 下载安装
  - https://www.postman.com/downloads/



#### HackBar 

- Firefox 浏览器插件，包含一些常用的工具。(SQL injection,XSS,加密等)，可以利用它，快速构建一个HTTP请求，或者用它快速实现某种算法等，多用于手工测试Web漏洞。 
- 安装
  - Firefox 浏览器 -> 附加组件 -> 寻找更多组件Wappalyzer -> 添加组件



#### Wappalyzer 

- Wappalyzer是一款功能强大的、且非常实用的网站技术分析插件，通过该插件能够分析目标网站所采用的平台构架、网站环境、服务器配置环境、JavaScript框架、编程语言等参数。
- 官网：https://www.wappalyzer.com/ 
- 支持平台：Firefox，Edge，Chrome
- 安装
  - 插件管理直接安装













































