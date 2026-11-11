---
title: "AI自动写html格式的widget之纯小白版"
date: 2025-03-20 17:00
author: 月半宵夜趣
url: https://mp.weixin.qq.com/s/2PM5_pMbMfeNC7nepaUy8g
---
Widget就是各种网页小挂件，比如展示天气啦，时钟这样的小玩意。如果用那种少儿编程软件做，会很琐碎，各种逻辑设置之类很绕。所以直接用ai做就很快。

    HTML就是一整个网页，我们可以把这个网页挂在github上部署好，里面放上这个挂件，这样我们就可以在类似息流notion这类网页上用嵌入的方式给他挂上去。

![](https://mmbiz.qpic.cn/mmbiz_jpg/TZaiaIvaGzrcf6liadebyagKhicgAcQyJEW0ER0I4fd5EyIhddM3kybpWAmpUGQnH14SYrMtqJkTdtDUibfvACJoug/640?wx_fmt=jpeg)

一般来说，一个挂件需要三个基本部件：HTML类似于画布，css类似于画笔和各种能看见的积木，核心的动力源就是这个java，负责让css构成的部件动起来，或者也可以获取到api让数据连通到这个挂件里，让它“活”过来。

![](https://mmbiz.qpic.cn/mmbiz_jpg/TZaiaIvaGzrcf6liadebyagKhicgAcQyJEW1mqxxo5oibcfzf09hL9WqBKVJUHibar4TPxOkjNn3o9vNJk9F81icMQEQ/640?wx_fmt=jpeg)

我把指令发给ai以后，ai 写好了整个HTML包括css和配套的java，为了代码简洁，我们可以把java打包好，上传到github，然后用引用的方式调出来就行了，这样做还有一个好处就是，可以给不同的css匹配不同的Java，也可以反过来，给Java匹配不同的css皮肤。

![](https://mmbiz.qpic.cn/mmbiz_jpg/TZaiaIvaGzrcf6liadebyagKhicgAcQyJEWJiaqoz6Xt1KMVGes8qtP6fSia4fkyOY214HjXE25d7L4t8pyAiac6778Q/640?wx_fmt=jpeg)

然后它就可以运行并显示，我们只要把里面的api更换为正常的实时天气就可以得到一个带有动画效果的天气小挂件啦。这里我没有替换api，所以它不准确，但是整个的原理和过程是一样的。所以，无需为少儿编程特别的焦虑，因为编程真的在逐步的成为一件“平易近人”的事情。
