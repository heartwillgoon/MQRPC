
# MQRPC
使用MQ及Protoful执行内部代替Http请求
注意:
1.此处并不是重新制造轮子,而是为了从底层逐渐搭建起一个能够运行起来的框架,能够让更多的程序员知道底层运行的原理
2.能够解决问题是更好,但是需要专门的时间和精力去维护,这个代码量太庞大,后期可能会优化结构,但是应该不会根据框架添加中间件
3.在说明:这个项目只是为了在内部使用RPC项目而写的一套整体的项目,如果单纯抽出来,使用mq+protoful+.net core肯定比这个项目
  要好,但是这个项目就是为了还原微软项目从传输协议着手,到.net core中间件,到mvc源码解析,能够看到.毕竟现在网上大部分代码
  要嘛会比较难,看半天看不懂,要嘛就是太简单,项目都运行不起来.此项目就是为了让c#程序员有一套程序能够从底层出发,并且能够
  debugger起来的项目,希望能够帮助大家理解中间件+mvc+ioc项目.如果后期感觉可以的话,可以去看看蒋金楠的博客及书,了解后
  就能够看微软开源的项目代码了
4.重新说明,这个项目只是为了更好的帮助中级工程师阅读源码,并不是特地去造轮子,也并不是特地想做啥,就是为了能够有一个整合的
  代码把项目从头到尾跑起来而已,细节蒋金楠大神已经讲得很好了,如果看我写的辣眼睛,去看看他的博客,买买他的书.
