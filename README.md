# -1. python基本语法
2. python中关于爬虫的几个重要的内置库，urllib/http/Cookie等
3. 学习正则表达式，beautifulsoup等解析网页的工具或包
4. 利用上几步学习的至少爬取比较简单的网站
5. 学习利用工具分析网页请求流程，学习模拟登录，
6.多线程多进程
7. 爬虫框架



1.http:(1)当用户在地址输入了网址，发送网络请求的过程
2.get请求
（1）方便，
（2）缺点： 不安全，明文，参数长度有限

  post请求
  （1）安全
  （2）数据整体没有限制
  （3）可以上传文件，百度云（上传，使用post）
  
  put
  delete
  head（请求头 响应头)
  (1)request head: 
  
  
  
  1.传参：
  (1).get传参：解释器ascii码没有汉字，要靠url转译。 urllib.parse.quote(url,safe = "string.printable")
  (2).字典传参：urllib.parse.urlencode()
  
  post传参：urllib.request.openurl(url,data)
  hendler:
  User-Agent:
  
  2. IP代理：
  （1）免费/收费的IP
  （2）IP分类：
      透明：对方知道我们真实的IP
      匿名：对方不知道我们真实的IP，但是知道我使用了 代理
      高匿：对方不知道我们真实的IP，也不知道我们使用了代理
   http端口80
   https端口443
