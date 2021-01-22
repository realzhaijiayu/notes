推荐阅读：https://www.cnblogs.com/mengxiangji/p/11297718.html

1. DNS解析
2. TCP连接
3. 发送HTTP请求
4. 服务器处理请求
5. 浏览器解析渲染页面
6. 连接结束

说人话：
在浏览器中输入url，浏览器通过 DNS 解析得到对应的 ip 地址，通过得到的 ip 地址，在互联网上找到对应的服务器，然后客户端三次握手与服务器建立 TCP 连接。TCP 连接建立之后，客户端向服务器发送 HTTP 请求报文，服务器对该请求做出响应，返回响应报文，浏览器拿到该响应报文，对其进行解析渲染展示。最后四次挥手使得连接结束。

对应的 issue 位置：https://github.com/realzhaijiayu/notes/issues/14