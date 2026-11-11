---
title: "如何在ob中调用big pickle"
date: 2026-05-20 22:51
author: 月半宵夜趣
url: https://mp.weixin.qq.com/s/Eu7PtuJvmettQcMhsqCqJw
---
作为和opencode最适配的原生模型，big pickle的速度是相当不错的，但是在OB里big pickle不会自动跑到模型可选的列表的，那为了继续用这个免费的模型，薅大厂羊毛，就得手动把他加进来，这个问题opencode自己是解决不了的，只能手动，不然一直问他他会答非所问。

去https://opencode.ai/zh  注册账号，然后申请API，这里是免费的

复制好API以后回到OB中，去opencode找到供应商：

![](https://mmbiz.qpic.cn/mmbiz_png/Fr4ehPkklc9DciaeaEjjLdpv7TBE5D1fVbdGBRzRK8Jvq1b27BntZdjYvQRPytLVlnGLgOsh2v6tDezXngF7kATk4CqJ93T0VDVH6pxalkFo/640?wx_fmt=png&from=appmsg)

第一个zen就是供应商

然后再去手动选big pickple

![](https://mmbiz.qpic.cn/sz_mmbiz_png/Fr4ehPkklc9c1by0WYBkI9LXz0klnK9pnX5e6l8pmPtnrczxnW0GE8MzicZNnpn4FqFXQppFDibbYAq0pkScH6DUHxuXSVQjCrhY377CaCCU8/640?wx_fmt=png&from=appmsg)

把它打开，就可以了。本着能薅多久薅多久，就这样用先。还有就是读图画图的能力取决于大模型的种类。像这几个都是推理模型，是不能画图的，只有多态模型才能画图，并不是说opencode不智能。

opencode是一个开源的AI代理，开源的意思是他的代码是公开的，大家都可以复制或者魔改自己用，它不是一个闭源的商业代理，闭源的商业代理比如notion的agent  国内的workbuddy啥 这类，闭源通常都是收费的，还有一个问题就是闭源通常都是放在云服务器上的，也就是说你的资料都在它那里，功能之类的由供应商说了算，比如你现在买了90元一个月的会员，有一些功能可以用，但是它是闭源的，它就可以随时改你的功能，并且你的资料都要传上去做训练用的。

但是开源的模型首先功能你可以自己做主，你可以自己下载插件扩展它，你可以直接魔改它，都没关系，只要你声明MIT协议之类都不存在魔改侵权。然后开源的模型如果接的你本地模型，你的数据不会上传出去（理论上是这样），除非你薅羊毛用它的免费模型，那就上到云端了。

GitHub上你能搜到的所有的各种skill、插件只要你能直接看到的，基本上都是开源，这样你就可以依照自己的喜好任意的像搭积木一样搭建自己的AI AGENT.他还有个好处，就是比如notion这样的收费的AGNET，我们可以通过MCP接口免费的实现和它内部收费一样的AGENT效果。然后也可以接通GITEE利用opencode实现原本要收费的傻瓜式同步效果等等，四舍五入差不多一个月省两三百是没有问题的。
