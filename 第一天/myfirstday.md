  前端这个东西用处很大，现在很多地方的需求也很大，但真正在学校层面能够做好教学的又非常少，要么很多的老师自己明白是个什么东西但是讲不出来，要么根本老师自己都没有丰富的项目经历，事实上这种东西还是要我们跟着实际做过项目的，经验丰富的老师一起进行学习才能够做好的，并且学习嘛，是一个持之以恒的过程，半途而废的人实在是太多了，我现在是真的想要做好一次，学好一次，给自己两个月，六十多天的时间，我还真不信自己就一定会比别人差了，都是人搞出来的东西，又不是什么天书之类的晦涩难懂（￣︶￣）↗　
	
正文分割线———————————————————————————————

首先html全程是超文本标记语言，是一种简单的标记语言，说来惭愧，当年高中的时候微机老师就讲过这个东西（当年还简单地做了几个小网站实现了简单的链接变色等效果，现在全忘了。）话说回来，什么是标记语言呢，所谓的标记语言，指的就是把我们说话的每一个部分都具体罗列出来，比如小明说一句“普通家庭pony马”其实是省略了很多内容的，我们不用刻意打引号就知道“普通家庭”是一句反讽，但如果换成了标记语言呢，就变成了：
《小明说》
《反讽内容开始》普通家庭《/反讽内容结束》
《这要用英语》pony《/英语结束了》
《这是姓氏名称》马《/姓氏名称结束》
《/小明说完了》
当然可以不止于此，在小明说中间除了直接说明内容还可以添加其他的状态形容词，比如强调重音：
《小明说》
《反讽内容开始》《重音》普通家庭《/重音结束》《/反讽内容结束》
《这要用英语》pony《/英语结束了》
《这是姓氏名称》马《/姓氏名称结束》
《/小明说完了》
再比如这时候pony马过来了，小明必须轻声细语
《小明说》
《反讽内容开始》《重音》普通家庭《/重音结束》《/反讽内容结束》
《轻声细语》
《这要用英语》pony《/英语结束了》
《这是姓氏名称》马《/姓氏名称结束》
《/轻声细语技术》
《/小明说完了》

看，这就是标记语言，是不是非常的方便，真实的html语言呢，就是，把同一个标签的用同一个英文单词表示，但在结束的位置添加 “/” 符号，就构成了基本的html结构。但是固定的一个结构可以表示，不是固定的结构呢，那么就得使用css层叠式样式表进行记录了，比如知乎有几千万个网页（假设的），那么是否每一个网页都需要规定字体，颜色，大小等内容呢，显然不是，那么我们就可以使用一个固定的模板对其进行规定，之后的内容就套模板就完事了，就像做ppt一样，网上找好模板，做的内容套进去就完事了.

那么JavaScript（简称js）又是什么呢，首先这是一个脚本型语言，可以制作后台的东西也可以制作前台的东西，并且已经成为了绝大多数浏览器的一个标准，用于绘制一些精美的图画内容和一些动态效果，这样复杂多变的东西使用简单的结构化的html进行标注显然是不够的，同时js还可以进行异步加载，什么是异步，顾名思义，就是同一个网页上的内容不是同时输出到你的电脑的，也就是根据需要进行加载，最简单的例子，淘宝网站上那么多的商品，一口气全部显示出来，那得多慢呀，所以很多时候是在上方的搜索结果先显示，下方的内容往往会慢半拍，这也是权衡取舍性能和显示效果之后得到的最优解，至于什么内容先显示，什么后显示，那就是js定制的范畴了，同时在远程的web服务器上，web server和web framework（web server使用的ppt模板）负责管理如何从数据库调取网页内容并将网页内容整理并输出给客户端，服务器中的“操作系统+web framework（ppt模板）+数据库类型+服务器脚本”就是一套web服务器的体系架构，通常有：

·LAMP（穷，不太在乎性能的使用，绝大多数小型web服务都想这样）：Linux + Apache + MySQL + PHP（P还可能是Python或Perl。有时候L会改成W=Windows。），也就是服务器上的操作系统是 Linux，Web Server 用 Apache，数据库用 MySQL，服务器脚本用 PHP语言

·J2EE（硬上java就完事了）：Java 世界的架构，通常是企业用的（银行、大型公司,.etc），比较常见地还会搭配一种 UNIX 做操作系统，Apache 做 Web Server，Tomcat 转换 JSP 到 Java 给服务器程序用（其实它也自带 Web Server），Oracle 数据库等等。不一定拿来建站，常常用来提供企业里的各种需要用到网络的业务。

·神奇的MEAN架构（没准是未来发展的趋势，可以降低学习成本）：MongoDB做数据库，Express做 Web Framework，Angular 做前端的 JavaScript 框架，Node.js 用于编写 Web Server。神奇之处在于这几个东西的语言都是 JavaScript （MongoDB的实现不是，但与外界沟通用的语言是）。


参考：https://www.zhihu.com/question/22689579/answer/22318058
					 https://www.w3school.com.cn/html/index.asp
					 https://m.runoob.com/html/
