#### Jsp、servlet阶段心得体会

在对Jsp的学习中，要掌握的东西很多，它和Js比起来方便了很多，不需要像Js那样要把方法等等的一系列语句从主体中提取出来，整个放到另外的一个区域里面。而且Jsp的功能性比Js强，数据类型的指定也比Js细致很多，总的来说，Jsp和java更为接近，但Jsp又不及java那么简洁。Jsp的有点事可以直接响应客户端请求，而动态生成 HTML、XML 或其他格式文档的Web网页，这是java所不能做到的。它对于网页功能的实现是有很多的，而此次任务中，所需用到的Jsp功能其实是很有局限性的。

对于servlet，我所理解的是：Servlet是可以运行在Web服务器上的程序，它是作为来自 Web 浏览器或其他HTTP客户端的请求和HTTP服务器上的数据之间的中间层。它读取来自客户端的数据：html表单，然后处理表单中的信息，并生成结果，再将结果发送到浏览器，形成所制作的网页。

此次任务的实现，主要是将自己写的各个Jsp：登录界面、登陆成功后的界面、登录失败的界面，在通过输入验证后用xml配好路径，将它们联系起来。在做这个的时候，由于路径没配对，报了很多次404错误，后来改改查查，才渐渐解决。而最难以理解的知识点是Filter实现拦截功能，在学知识点的时候总是看不懂，对任务中拦截怎么写也很久没有思路。去网上搜索了很多关于拦截的实例后，才慢慢理解了有关Filter的作用和方法。

昨天，老师给我们开会的时候说到一个例子让我很受影响：在做任务的时候，若任务的时间是三天，而我们在第二天时就将它做完了，但这并不能称得上是真正的完成了任务，因为对于一个好的功能的实现，其中的代码是不断完善与重构的。在不断地调试、完善的过程中，功能才会不断的改善。所以，不到第三天的最后，代码就有时间不断的重构、不断的优化。