# web 与 Http

- web 页： 由一些对象组成。
- 对象可以是 HTML 文件，JPEG 文件，JAVA 小程序，声音剪辑文件。
- web 页包含一个基本的 HTML 文件，该基本 HTML 文件又包含若干对象的引用（链接）。
- 通过 URL 对每个对象进行引用。 访问协议，用户名、口令字、端口等。
- URL 格式 Port://user:psw@www.someschool.edu/somedepth/pic.gif:port

## http 概况

HTTP:超文本传输协议

- web 的应用层协议
- 客户/服务端模式
  - 客户：请求、接收和显示，web 对象的浏览器。
  - 服务端：对请求进行响应，发送对象的 web 服务器。
- 使用 TCP
- http 是无状态的

HTTP 1.0 :RFC1945 （非持久）
HTTP 1.1 :RFC2068 （持久）

- 非 pipeline (在上一个链接回来之后再请求) 一次只有一个。
- pipeline 还没回来的时候就接着发送请求。

### http 请求报文

- 两种类型的 http 报文 请求、响应
- http 请求报文 （ASCII)人能阅读

### 用户服务器状态 cookies

cookies 的四个部分

- 1.在 http 响应报文中又一个 cookie 的首部行
- 2.在 http 请求报文含有一个 cookie 的首部行
- 3.在用户端系统中保留又一个 cookie 文件，由用户浏览器保存
- 4.在 web 站点后哟一个后端数据库。

### web 缓存

- 缓存既是客户端又是服务端
- 通常缓存是由 ISP 安装

为什么要使用？

- 降低客户端的请求响应时间
- 可以打打减少一个机构内部网络与 Internet 介入链路上的流量。
- 互联网大量采用了缓存：可以是较弱的 ICP 也能提供有效内容。
