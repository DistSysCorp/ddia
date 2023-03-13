# 《DDIA 逐章精读》小册

在理解英文原文的基础上，结合我的一些工作经验，进行一些相应扩展，并参考 [github 上 Vonng 的中文翻译版](https://github.com/Vonng/ddia)，对每一章用中文重新组织，作为每次分享的文字稿，在此集结为一本开源小册，并附上每章分享的**录屏视频**（[b 站](https://space.bilibili.com/30933812/channel/collectiondetail?sid=240551), [Youtube](https://www.youtube.com/playlist?list=PLSISRu2b2N54LGT3Pyef70ae8m0tAAo6g)），希望可以对有需要的同学有所帮助，水平所限，难免疏漏，如发现有任何有误之处，欢迎[提 issue](https://github.com/DistSysCorp/ddia/issues/new) 和 [PR](https://github.com/DistSysCorp/ddia/compare)。

这个小册的电子版在[这里](https://mbd.pub/o/bread/ZJaXlZdt)，之后更新完后，电子书也会随之更新。

## 目录

### [序](preface.md)

### 第一部分：数据系统基础

- [第一章：可靠、可扩展、可维护](ch01.md) [[b 站](https://www.bilibili.com/video/BV1bY411L7HA) [Youtube](https://www.youtube.com/watch?v=geVsm3YGF4A&list=PLSISRu2b2N54LGT3Pyef70ae8m0tAAo6g&index=1)]
  - [本书为什么以数据系统为主题](ch01.md#本书为什么以数据系统为主题)
  - [可靠性](ch01.md#可靠性)
  - [可伸缩性](ch01.md#可伸缩性)
  - [可维护性](ch01.md#可维护性)
- [第二章：数据模型和查询语言](ch02.md) [b 站 ([上](https://www.bilibili.com/video/BV19a411C7UN) [下](https://www.bilibili.com/video/BV1BZ4y1r79M)) Youtube ([上](https://www.youtube.com/watch?v=1TVdmZ_sJCM&list=PLSISRu2b2N54LGT3Pyef70ae8m0tAAo6g&index=2) [下](https://www.youtube.com/watch?v=GdihZOSMuuI&list=PLSISRu2b2N54LGT3Pyef70ae8m0tAAo6g&index=3))]
  - [概要](ch02.md#概要)
  - [关系模型 vs 文档模型](ch02.md#关系模型与文档模型)
  - [数据查询语言](ch02.md#数据查询语言)
  - [图模型](ch02.md#图模型)
- [第三章：存储与查询](ch03.md) [b 站 ([上](https://www.bilibili.com/video/BV1mL411P72H/) [下](https://www.bilibili.com/video/BV1bL411A7ga)) Youtube([上](https://www.youtube.com/watch?v=tI1BmIZpK-c&list=PLSISRu2b2N54LGT3Pyef70ae8m0tAAo6g&index=4) [下](https://www.youtube.com/watch?v=8wiJSECzADc&list=PLSISRu2b2N54LGT3Pyef70ae8m0tAAo6g&index=5))]
  - [底层数据结构](ch03.md#驱动数据库的底层数据结构)
  - [事务型还是分析型](ch03.md#事务型还是分析型)
  - [列式存储](ch03.md#列存)
- [第四章：编码和演进](ch04.md) [[b 站](https://www.bilibili.com/video/BV1Aa411q7u9) [Youtube](https://www.youtube.com/watch?v=DqddHDVTkps&list=PLSISRu2b2N54LGT3Pyef70ae8m0tAAo6g&index=6)]
  - [数据编码的格式](ch04.md#数据编码的格式)
  - [几种数据流模型](ch04.md#几种数据流模型)

### 第二部分：分布式数据

- [第五章：冗余](ch05.md) [ b 站 ([上](https://www.bilibili.com/video/BV1VR4y1K7eK) [下](https://www.bilibili.com/video/BV1ou4116779)) Youtube([上](https://www.youtube.com/watch?v=pbURsaoKiYc&list=PLSISRu2b2N54LGT3Pyef70ae8m0tAAo6g&index=7) [下](https://www.youtube.com/watch?v=y23oqgIG7Vw&list=PLSISRu2b2N54LGT3Pyef70ae8m0tAAo6g&index=8))]
  - [领导者与跟随者](ch05.md#领导者与跟随者)
  - [复制滞后问题](ch05.md#复制滞后问题)
  - [多主模型](ch05.md#多主模型)
  - [无主模型](ch05.md#无主模型)
- [第六章：分区](ch06.md) [b 站 ([上](https://www.bilibili.com/video/BV1tY4y157Np) [下](https://www.bilibili.com/video/BV1AA4y1f7Hi)) Youtue ([上](https://www.youtube.com/watch?v=7vvycyhJn1s&list=PLSISRu2b2N54LGT3Pyef70ae8m0tAAo6g&index=9) [下](https://www.youtube.com/watch?v=aPeHdQgBmi4&list=PLSISRu2b2N54LGT3Pyef70ae8m0tAAo6g&index=10))]
  - [分片与复制](ch06.md#分片与复制)
  - [键值对集的分片](ch06.md#键值对集的分片)
  - [分片和次级索引](ch06.md#分片和次级索引)
  - [分片均衡](ch06.md#分片均衡)
  - [请求路由](ch06.md#请求路由)
- [第七章：事务](ch07.md) [ b 站 ([上](https://www.bilibili.com/video/BV1d94y117pW) [中](https://www.bilibili.com/video/BV1u3411w765) [下](https://www.bilibili.com/video/BV1Qr4y1M7Zm)) Youtube ([上](https://www.youtube.com/watch?v=gbExnxslpCs&list=PLSISRu2b2N54LGT3Pyef70ae8m0tAAo6g&index=11) [中](https://www.youtube.com/watch?v=sDKKhGFyUmk&list=PLSISRu2b2N54LGT3Pyef70ae8m0tAAo6g&index=12) [下](https://www.youtube.com/watch?v=Lhs6H6IgFvY&list=PLSISRu2b2N54LGT3Pyef70ae8m0tAAo6g&index=13))]
  - [棘手的概念](ch07.md#棘手的概念)
  - [几种弱隔离级别](ch07.md#几种弱隔离级别)
  - [可串行化](ch07.md#可串行化)
- [第八章：分布式系统中的麻烦事](ch08.md) [b 站 ([上](https://www.bilibili.com/video/BV1Ad4y1D7Yy) [中](https://www.bilibili.com/video/BV1114y1L7wU) [下](https://www.bilibili.com/video/BV1uG411A7GK)) Youtube ([上](https://www.youtube.com/watch?v=-q-yY_0aCsg&list=PLSISRu2b2N54LGT3Pyef70ae8m0tAAo6g&index=13) [中](https://www.youtube.com/watch?v=mk-QfuBV_NQ&list=PLSISRu2b2N54LGT3Pyef70ae8m0tAAo6g&index=14) [下](https://www.youtube.com/watch?v=xhk-X-rkLU4&list=PLSISRu2b2N54LGT3Pyef70ae8m0tAAo6g&index=15))]
  - [故障和部分失败](ch08.md#故障和部分失败)
  - [不可靠的网络](ch08.md#不可靠的网络)
  - [不可靠的时钟](ch08.md#不可靠的时钟)
  - [知识、真相和谎言](ch08.md#知识、真相和谎言)
- [第九章：一致性和共识协议](ch09.md) [b 站 ([上](https://www.bilibili.com/video/BV1eK411o73Q) [中](https://www.bilibili.com/video/BV1Y14y1P7xG) [下](https://www.bilibili.com/video/BV1r3411S7J2)) Youtube ([上](https://www.youtube.com/watch?v=Hq2gWib5n_I&list=PLSISRu2b2N54LGT3Pyef70ae8m0tAAo6g&index=17) [中](https://www.youtube.com/watch?v=Nds2xpnyS8A&list=PLSISRu2b2N54LGT3Pyef70ae8m0tAAo6g&index=18) [下](https://youtu.be/5ZCXSDMcerg))]
  - [一致性保证](ch09.md#一致性保证)
  - [线性一致性](ch09.md#线性一致性)
  - [顺序保证](ch09.md#顺序保证)
  - [分布式事务和共识协议](ch09.md#分布式事务和共识协议)

# DDIA 读书会

DDIA 读书分享会，会逐章进行分享，结合我在工业界分布式存储和数据库的一些经验，补充一些细节。每两周左右分享一次，欢迎加入，Schedule 在[这里](https://docs.qq.com/sheet/DWHFzdk5lUWx4UWJq)。我们有个对应的分布式&数据库讨论群，每次分享前会在群里通知。如想加入，可以加我的微信号：qtmuniao，简单自我介绍下，并注明：分布式系统群。另外，我的公众号：“木鸟杂记”，有更多的分布式系统、存储和数据库相关的文章，欢迎关注。

读书会安排和往期录屏：[https://docs.qq.com/sheet/DWHFzdk5lUWx4UWJq](https://docs.qq.com/sheet/DWHFzdk5lUWx4UWJq)

# 关于我

我是青藤木鸟，一个喜欢摄影的分布系统程序员，现主要做数据库方向。可以通过[领英](https://www.linkedin.com/in/qtmuniao/)，[b 站](https://space.bilibili.com/30933812)，[知乎](https://www.zhihu.com/people/qtmuniao) , 微信号 (qtmuniao) 找到我。更多分布式系统文章欢迎关注我的公众号——[木鸟杂记](https://mp.weixin.qq.com/mp/appmsgalbum?__biz=Mzg5NTcxNzY2OQ==&action=getalbum&album_id=2164896217070206977&scene=126&devicetype=iOS15.4&version=18001d33&lang=zh_CN&nettype=WIFI&ascene=59&session_us=gh_80636260f9f9&fontScale=106&wx_header=3)。同名博客：木鸟杂记 [https://www.qtmuniao.com](https://www.qtmuniao.com)

对于 Martin Kleppmann 博士的[DDIA](https://dataintensive.net/)，每章大概我自己要读两遍英文版，然后自己翻译一遍，再理顺一遍词句，再找相关资料补充一些背景，最后再讲一遍，因此每章最少都得花十几个小时甚至几十个小时（比如事务那一章）。创作不易，如果感觉感觉对你有帮助的话，不妨分享给更多的人~ 这将对我是莫大的鼓励和支持。当然，也可以订阅我的技术专栏[系统日知录](https://xiaobot.net/p/system-thinking) ，顺便留个言。

最后，如果你想对某些章节讨论的话，欢迎来我搭的一个专门的分布式系统论坛：https://distsys.cn/ 。感谢阅读，感谢关注。
