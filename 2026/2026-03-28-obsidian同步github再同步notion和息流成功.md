---
title: "obsidian同步github再同步notion和息流成功"
date: 2026-03-28 15:21
author: 月半宵夜趣
url: https://mp.weixin.qq.com/s/pwHoeM3Y33Q0pADorpObVA
---
优点：不花钱，不用TOKEN

缺点：步骤挺多，得先安装好OBSIDIAN什么的，巨麻烦

![](https://mmbiz.qpic.cn/mmbiz_png/Fr4ehPkklcibYcyicTAP37ZDFo0kpUTuicYxlGRwDc7Mfia5iaSOOd6D59qgFuzjZOhm8UxiaT9TArTGxUc2TiakLCFsPLV0EOIN4Mdway7bMt26t4/640?wx_fmt=png&from=appmsg)

直接看效果，这是OB界面

![](https://mmbiz.qpic.cn/sz_mmbiz_png/Fr4ehPkklc8mXHouov5lvA3ER3Y2IsUpBeaqoT3QvO7uE17dIM3IyPYy52aZy61IMfhXd83QkscP6nqRkjwvrn2lkbsQUONHprFa3yA3OYE/640?wx_fmt=png&from=appmsg)

这是同步notion以后的显示，真的超级爽，0TOKEN,永远不要钱

![](https://mmbiz.qpic.cn/sz_mmbiz_png/Fr4ehPkklcibusSO3jiaGXZU81089Q0OYxMkH4YJl52jTQZl784D3xP9XQO7KO5C2y85XnhxfZof4U4GglOPyG3UOUMPCzibEuWTXMianbLajN4/640?wx_fmt=png&from=appmsg)

这是GITHUB界面，太爽了，完全不花钱的快乐

![](https://mmbiz.qpic.cn/mmbiz_png/Fr4ehPkklc8YW8mRMuXCdqcgw38mpE6Jo6GibA27wdljw4t4vsWq7YQ4SxoLdthYuhXKO5yfr3bcbg7CR5NJcicnibmy7eiaI56OmH5EDG3mF5A/640?wx_fmt=png&from=appmsg)

这是打开的样子，一想到永不要钱简直就觉得捡到一个亿，第一个这样用的人简直是天才

![](https://mmbiz.qpic.cn/sz_mmbiz_png/Fr4ehPkklc8DwGTbwS1Lh6R9JSxF1Us5AqRPjZb4ZAGl8iaic6UwQhkt3CuwWXnfWenfI83aEY5voCwjicoZcX7LMFEoknWSmXKzKNwfL4F8kI/640?wx_fmt=png&from=appmsg)

和息流的也跑通了，撒花

检查日志，一切正常，至此我的两台电脑、github、obsidian、息流、notion已经全部互通，直接用git自带的action和平台自己的API实现无感化自动同步中。

并且我还顺手升级了一下公众后的同步：

![](https://mmbiz.qpic.cn/sz_mmbiz_png/Fr4ehPkklc8xjCzr8cmiaj0lg4xK0icxKJvLr7NHQ7I4NTGCW3icryRJrTKYdky6rKesaC3tianJM3IgiagM3ZUlghUkynzUabgcjJQGHhav19oA/640?wx_fmt=png&from=appmsg)

一秒自动排版，工工整整，大家以后看到这类工整的文就不要觉得惊奇啦。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/Fr4ehPkklcibhXbz9bkaEFCG7iaDu2ibgd3wrhaM6beSWpy29SFcq2X4MetSILXICwWIU5zGIAEYc0ib2AH17qHyEdDSYkkXFjsfDgrcaY3BHWk/640?wx_fmt=png&from=appmsg)

当然这个过程是人工也参与了判断的，比如有的时候是我直接给AI报错，因为AI有时会忽略错误

![](https://mmbiz.qpic.cn/sz_mmbiz_png/Fr4ehPkklcibCVKrxbSrKN0GCe62yhprpmVIB93AwPNJibftGywccn4oFfcPIfq1bxUCt3O61G1JkZhJ3ZibCu3VRcGBmO4d3gtib0udqxSVu3k/640?wx_fmt=png&from=appmsg)

![](https://mmbiz.qpic.cn/sz_mmbiz_png/Fr4ehPkklcibBq5s23Z8SBOCCF6QUzawZe9frSpOaAQ90HUTDYibJCyY6l3ibzm634ZnBEJFAelVE5ZzUkibLHfatC23Idfta2pjzlVrWuGbKq4/640?wx_fmt=png&from=appmsg)

还有就是豆包和deepseek都搞不定息流的同步代码，最后是龙虾的Claude搞定的

豆包把我气笑了，还当场认了爹

![](https://mmbiz.qpic.cn/mmbiz_png/Fr4ehPkklc81Y78lF52XgUicAYcEoueZI9QRP3HqHsy6LwmrmUAiaAwt1dw5HgKTCfjbr4PibOqlpyobraPXYFAYiatfJoSLg0tBOIWzjcWOjR4/640?wx_fmt=png&from=appmsg)

![](https://mmbiz.qpic.cn/mmbiz_png/Fr4ehPkklcicuWmlOIqiaBjg4KsKVsRib5v1jUNCe1BPCGIwnIicib0LrQQkibZ58gJ9rYoTC7CLjO2AcUUpLCU40okYia3j1dib7QLd20nwCC8eayc/640?wx_fmt=png&from=appmsg)

后面人机交互了几次，终于好了

![](https://mmbiz.qpic.cn/mmbiz_png/Fr4ehPkklcictsqq1asPI7mkkiaqVnoXZBddonljaTEy1lhRVcsUSSjs7qL2BUQL8mccYib2T3m2oUdOErtVJ227hlEjU5QfWvaUGibl5Kj9rME/640?wx_fmt=png&from=appmsg)

讲道理啊，还真就靠KOLLAB CLAUDE真神，写的代码一次就能跑通

![](https://mmbiz.qpic.cn/sz_mmbiz_png/Fr4ehPkklcicO4MTIibygp59icOb3hLAA8cg6Hyq0Uycq4369bFC936afVuL7XibcFfDJ9JV9qaKlJr3UQfDSwmLLUbnmUUaSMMCsHHwibLLT5MY/640?wx_fmt=png&from=appmsg)

这个逻辑链条由于长且复杂的丧心病狂，不推荐毫无计算机基础的小白自己手搓，会疯。

![](https://mmbiz.qpic.cn/mmbiz_png/Fr4ehPkklcicKL9O02k05QXeZjJ5yNqBsmQB6lAYQpG0Z1rTqD6LMjviaxS6KnCH9AGSzW2H1urayHictF9bHYdpde5FWiaPNwbRWG9fnBToxyU/640?wx_fmt=png&from=appmsg)

notion同步的结果

为什么要搞这么难的东西呢？不是要学习么，学习那肯定要搞一个牛比一点的外挂啊，不然后面东西多了就很难整理了。我相信到了中学阶段大部分的ORC和几何渲染问题都会得到解决，那我们最后需要的东西说到底还是数据库的记录和整理。

这样做有个好处，息流和notion还有公众号实际都是云端，那就可以在哪里都能看，都能用，只要保证办公室的电脑和家里的电脑都能同步就行了。

![](https://mmbiz.qpic.cn/mmbiz_png/Fr4ehPkklcibgNaH4bV6hM6icMEr15iaLiaUDm2yycmDQsymHJiaQ6oud7rn0g5tZsK4mlcO6Euz9b04pKicb9YJckdTcf5ueJYPNYDcs5BC4UCE8/640?wx_fmt=png&from=appmsg)

![](https://mmbiz.qpic.cn/sz_mmbiz_png/Fr4ehPkklc9CSVG9Y5FvpCrianJO8yDCO5KFe8mkReqbUQTYqszdLniccKUyp9dRrs41ibFTzBYWOTGZ6axJV2fO1BoPlMdCZUhjXqnqxrEmcA/640?wx_fmt=png&from=appmsg)

以后就是天崩地裂我的数据都没事
