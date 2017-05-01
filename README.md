   跨站脚本攻击(Cross Site Scripting)，为不和层叠样式表(Cascading Style Sheets, CSS)的缩写混淆，故将跨站脚本攻击缩写为XSS。
   恶意攻击者往Web页面里插入恶意Script代码，当用户浏览该页之时，嵌入其中Web里面的Script代码会被执行，从而达到恶意攻击用户的目的,
   还有另外一种产常见的就是CSRF。    

主要分类：

    反射型：发出请求时，XSS代码出现在URL中，作为输入 提交到服务器端，服务器端解析响应之后，XSS代码随着响应内容一起传回给浏览器，
    最后浏览器解析执行XSS代码。

    存储型：存储型XSS和反射型XSS的差别在于,提交的代码会存储在服务器中(例如数据库,内存,文件系统等),
    下次请求页面是不用再提交XSS代码。

特点：  

    1.耗时间
    2.有一定几率不成功
    3.没有响应的软件自动攻击
    4.需要有一定的语言基础
    5.这是一种被动的攻击手法