# jsp+servlet阶段心得
    本次servlet和jsp的学习主要是为之后的数据库学习打下一定的基础，servlet主要是一个把数据库和网页前端联系到一起的媒介，进行各种页面之间的跳转。其实所谓servlet和jsp也就是java语言和HTML界面的结合应用，让界面里使用java逻辑，java语言中写界面。
##### 一、心路体会
* 这次学习过后我终于有了一个对于前端后端大概的一个概念，在我以往的以为里，以为前端更多就只是界面设计而后端完成功能代码与界面方块。现在我才明白主要区分开来前端后端的并不是这些，而是服务器、数据库的连接。前端主要负责用户直观看的和使用的界面，后端负责的主要就是对功能的实现以及不同界面之间的跳转，判断等等。
##### 二、学到的知识
* 首先学到的让我理解了最久的东西就是filter的使用，虽然在教程上百度上对于filter都很很详细的一套讲解，但是我开始还是无法理解其意思，不明白所谓拦截是怎么的拦法以及他与servlet的判断过程有什么本质上的意义与区别。学了很久一直修改数据才大概理解到了使用filter的意义所在，其本质既然是过滤器，那其实就是过滤掉非登录界面传过来访问该页面的请求，使其无法直接访问。
* 然后学到的页面的跳转，从一个jsp界面跳转到另一个jsp界面，其中我在使用sendRedirect的过程中发现了一个很有趣的事情就是在同一界面中当sendRedirect执行的时候，所有的alert都会失效，而其他的跳转页面则不会。
* 最后学到的就还有只是知道了一个新写界面的东西，就是button-radius，可以用于让div等等原本的顶点变成圆弧。只是在使用是，使用button-radius直接调四个顶点的圆弧没有效果，所以我只能一个一个的调，不明白原因是不是因为版本原因。