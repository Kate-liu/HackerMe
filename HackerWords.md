# Hacker Words

- WAF（Web 应用程序防火墙）
- OGNL 语言（Object-Graph Navigation Language，对象图导航语言）
  - OGNL充斥在Struts2前后台数据传递与存储的方方面面，给Struts2中数据的处理带来了极大的方便
  - 它是一门表达式语言，除了用来设置和获取Java对象的属性之外，另外提供诸如集合的投影和过滤以及lambda表达式等
- Apache 软件基金会
- 银行卡 CVV 码
  - CVV，即 Card Verification Value
  - VISA CVV和MC CVC都是由卡号、有效期和服务约束代码生成的3位或4位数字，一般写在卡片磁条的2磁道用户自定义数据区里面。
  - 通常在信用卡背面看到的后三位数字，其实是CVV2，并非CVV代码。
- Poison Ivy 远程管理工具
- 数据证书
- VPN
- 双因子验证
- 物理身份验证
  - 到银行柜台拿身份证重置密码
- 彩虹表（rainbow table）
  - 反查出明文
- Contrast Security 安全公司
- 自动化测试
  - API 级别的测试
  - UI 自动化测试
  - 集成的自动化测试
  - 单元测试
- 安全级别高
  - 安全审计
  - 安全监控
  - 安全访问
  - 加密存放
  - 被加密的数据和用于加密的密钥是由不同的人来管理
- 非对称加密安全性防护
  - 密钥的自动化更换
  - 密钥一定要做到随机生成
  - 在外部系统调用 100 次或是第一个小时后就自动更换加密的密钥
- DDoS 攻击
- DoS（Denial of Service，拒绝服务）攻击
- 对称加密算法
  -  加密和解密使用的是同一个密钥
  -  高效
  -  DES、IDEA、AES、国密 SM1 和 SM4
- 非对称加密算法
  - 加密和解密使用不同的密钥，公钥和私钥
  - 正向计算很容易，反向推倒则无解
  - 解决密钥分发的问题
  - 但是效率不高
  - RSA、ECC 和国密 SM2
- 散列算法
  - 对任意长度的输入，计算出一个定长的 id
  - 不可逆性
  - 鲁棒性（同样的消息生成同样的摘要）、唯一性（不存在两个不同的消息，能生成同样的摘要
  - MD5、SHA、国密 SM3
    - SHA 分为 SHA-1 和 SHA-2 两个版本
    - SHA-2 256 是目前比较安全的散列算法
  - 加”盐“
    - 一串随机的字符，是可以公开的
- 单点登录（Single Sign On，SSO）
  - CAS（Central Authentication Service，集中式认证服务）流程
  - JWT（JSON Web Token）
  - OAuth（Open Authorization）
  - OpenID（Open Identity Document）
- 访问控制机制
  - DAC、role-BAC、ruleBAC、MAC
  - DAC（Discretionary Access Control，自主访问控制）
  - role-BAC（role Based Access Control，基于角色的访问控制）
  - rule-BAC（rule Based Access Control，基于规则的访问控制）
  - MAC（Mandatory Access Control，强制访问控制）
- 威胁评估的步骤
  - 识别数据、识别攻击、识别漏洞
- XSS 攻击（Cross-Site Scripting，跨站脚本攻击）
  - 反射型 XSS
    - 产生在前后端一体的网页应用中
  - 基于 DOM 的 XSS 
  - 持久型 XSS
    - 又叫作存储型 XSS
- XSS 攻击防护
  - 验证输入 OR 验证输出
  - 编码
  - 检测和过滤
  - CSP
    - CSP（Content Security Policy，内容安全策略）
    - 在服务端返回的 HTTP header 里面添加 一个 Content-Security-Policy 选项
- SOP（Same Origin Policy，同源策略）
  - window.location 来执行跳转操作
- SQL 的 PrepareStatement 将解析和执行分开
  -  PHP 中，使用 PDO（PHP Data Objects）
  - C# 中，使用 OleDbCommand 
  - Java 中，使用 prepareStatement
  - 通过字符串拼接来构造 SQL语句，没有将解析和执行分开
- CSRF（Cross-Site Request Forgery，跨站请求伪造）攻击
  - CSRFToken 防护手段
    - CSRFToken 是服务端随机生成返回给浏览器的
  - 二次验证 防护手段
    - 输入支付密码
- SSRF（Server Side Request Forgery，服务端请求伪造）攻击
  - 内网穿透
- POP，Property Oriented Programming
  - 恶意的调用链
-  RASP（Runtime Application Self-Protection，实时程序自我保护）
  - 检测到应用中的非正常代码执行操作
- 黑盒（Black Box Testing，功能测试）
  - 在不获取代码的情况下，直接运行应用，然后对应用的请求和响应进行扫描
- 白盒（White Box Testing，结构测试）
  - 直接获取到线上的源代码，然后对它进行扫描
  - 检测代码漏洞或者逻辑漏洞
- 间接的信息泄漏方式
  - 错误信息泄漏
  - 返回信息泄漏
  - 注释信息泄漏
- 直接的信息泄漏方式
  - 版本管理工具中的隐藏文件
  - 上传代码到 GitHub
- 0 day
  - 中文译为“零日”
  - 在插件发布修复漏洞的安全补丁之前，黑客就已经知道漏洞细节的漏洞
  - “0 day”就是只有黑客知晓的未公开漏洞
- 插件
  - 是第三方的插件、依赖库、工具和框架等的统称
- 虚拟补丁
  - 在不对应用插件进行升级的情况下，有效阻止攻击流量
  - 在前置的网络或系统中，对针对插件漏洞的攻击流量进行检测和拦截即可，大部分防火墙、IPS 等安全防御工具，都会提供虚拟补丁的功能
- 公开漏洞库
  - CVE（Common Vulnerabilities &Exposures，公共漏洞和暴露）
  - CWE（Common Weakness Enumeration，通用缺陷列表）
  - CVSS（Common Vulnerability Scoring System，通用漏洞评分系统）
  - NVD（National Vulnerability Database，国家信息安全漏洞库）
  - CNVD(China National Vulnerability Database，中国国家信息安全漏洞库）
- 权限提升（Privilege Escalation）
  - 通过漏洞攻击或者利用弱密码，获取到其他用户的权限
  - 在获取了新的用户权限之后，黑客就能够以新用户的身份去窃取和篡改数据，进行非法的操作了
  - 水平提升
    - 获取了另外一个“平级”用户的权限
    - 普通用户被盗号
  - 垂直提升
    - 应用的管理员或系统的 ROOT 权限
- 后门
  - 当黑客通过权限提升，成功获取到一个高级别的权限后，为了保留这个权限，黑客会在应用中留下一个隐藏的进程，下次只要黑客想再次进入，就可以通过这个进程来连通，而不需要再次去绕过各种安全流程
  - 在不经过正常流程的情况下，就直接获得一些权限。
  - 正常的应用中可能也会留下一些“后门”以备特殊情况，微软曾进行过一次打击盗版 Windows 的行动，当时国内的盗版 Windows 在同一时间出现了黑屏现象
  - 木马（Trojan）
    - 一些外表看起来正常，但会对应用和系统进行破坏的服务和进程
    - “灰鸽子”木马，“灰鸽子”就能在应用运行的时候监控应用的全部操作了（屏幕、键盘、摄像头等）
  - Rootkit
    - Rootkit 会驻扎于内核中，通过修改内核的逻辑来完成“后门”的功能
  - WebShell
    - 把“后门”留在正常的 Web 服务中
    - <?php @eval($_POST['shell']);?>)
  - 常驻于系统后台方式
    - 定时任务（crontab）或者开机启动项（inittab、rc.local）的配置中，加上“后门”的执行命令
- 权限提升和持久化防护
  - 最小权限原则
    - 给每一个用户和进程等，只分配它们需要用到的权限
  -  IDS（Intrusion Detection System，入侵检测系统）
    - 对黑客的异常行为进行检测
    - 分析正常用户和黑客在网络层或者主机层中的行为异同，来识别黑客的攻击





# Exploit

- CVE-2017-5638
  - Apache Struts 2 中 RCE 的远程代码执行漏洞
  - 安恒信息的 Nike Zheng 发现
  - 2017 年 3 月 7 日上报
  - Equifax 中招
  - https://nvd.nist.gov/vuln/detail/CVE-2017-5638
  - Apache Struts 2 的 Jakarta Multipart parser 插件存在远程代码执行漏洞，攻击者可以在使用该插件上传文件时，修改 HTTP 请求头中的 Content-Type 值来触发漏洞，最后远程执行代码。
  - 默认情况下 Jakarta 是启用的。
  - 注入点是在 JakartaMultiPartRequest.java 的 buildErrorMessage 函数中，这个函数里的 localizedTextUtil.findText 会执行 OGNL 表达式，从而导致命令执行（注：可以参看 Struts 两个版本的补丁“2.5.10.1 版补丁”“2.3.32 版补丁”），使客户受到影响。
  - 参考演示程序：
    - https://github.com/xsscx/cve-2017-5638
    - https://github.com/mazen160/struts-pwn
- CVE-2017-9804
  - Apache Struts 2 漏洞
- CVE-2017-9805
  - Apache Struts 2 远程代码执行漏洞。
  - 国外安全研究组织 lgtm.com 的安全研究人员发现
  - 漏洞原因是 Struts 2 REST 插件使用带有 XStream 程序的 XStream Handler 进行未经任何代码过滤的反序列化操作，所以在反序列化 XML payloads 时就可能导致远程代码执行。
- CVE-2017-9793 
  - Apache Struts 2 漏洞
- CVE-2017-12611
  - Apache Struts 2 漏洞
- magic quotes
  - 旧版本的 PHP 中，就存在“magic quotes”的漏洞
  - 因为 PHP 无法处理某些编码的字符而导致崩溃
- CVE-2016-5195
  - 脏牛 漏洞
  - Linux 系统漏洞，这个漏洞可以实现提权操作，也就是让低权限的用户获得较高权限
- CVE-2014-0160
  - 心脏滴血 漏洞
  - 加解密插件 OpenSSL 中的漏洞，OpenSSL 曾为所有 HTTPS 网站提供数据加密保护
  - 这个漏洞让任何人都可以通过网络读取 OpenSSL 系统内存中的数据，解密所有的加密流量



















