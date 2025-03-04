---
title: 我的硕士前半生 | Forever Young
shortTitle: 我的硕士前半生 | Forever Young
description: 本篇文章属于随笔类，它可能无法对你起到直接帮助，它只是我这个普通学生一年半以来的一些足迹与思考。它可能更适合大二，研0研一的同学查看。本文首发于我的个人博客 Forever Young我的本科像硕士，有实验室有工位，桌子超级大，有老师带有学长可以问。我的硕士像本科，没有实验室，工位真的是公共座位，导
tags:
  - 优质文章
category:
  - 其他网站
head:
  - - meta
    - name: keywords
      content: 年终总结
---

> [二哥的编程星球](https://mp.weixin.qq.com/s/hXXBTPPkFj2VMg_GXqn4EA)已经有 **1500 多名** 球友加入了，如果你也需要一个良好的学习氛围，[戳链接](https://mp.weixin.qq.com/s/CljCSezUgoBXb-T9wbIGww)加入我们吧！这是一个编程学习指南+ Java 项目实战+ LeetCode 刷题的私密圈子，你可以阅读星球专栏、向二哥提问、帮你制定学习计划、和球友一起打卡成长，冲冲冲。

大家好，我是二哥呀。

在朋友圈看到一位读者写的这篇“我的硕士前半生”，感觉应该会对大家有较大的启发，于是分享出来，希望对大家有一些帮助🤔。

PS：这位读者拿到了美团、百度、网易、滴滴、B站等大厂的日常实习offer，他是如何做到的呢？

## 21年9月 迷茫

研一刚入学还是有些迷茫的，这种迷茫不是那种无头苍蝇式的迷茫，大体方向是准备实习找工作，落实到具体细节却并没有做好

先是没有吸取大学的经验，都准备去找互联网工作了，竟然还准备去参加班干部选举（幸亏没选上😂，要不然就被学校绑死了

然后发现了学校政策其实不是那么完善，奖学金和国奖有漏洞，花时间和钱就一定能拿，但这样拿了又有什么意义

和本科实验室的阿里学长聊了下该学什么，简单规划路线后就开始学了

## 21年11月 GSoC

### 缘起

准备过程说起来也很简单，就是正常的学，刷题、八股。

忘记了是因为什么想起了GSoC，算是为了圆梦吧，第一次认识它也是在知乎，来自那篇广为流传的文章：Google 编程之夏(GSoC)：海量优质项目，丰厚报酬，你竟然还不知道？

![](http://cdn.tobebetterjavaer.com/tobebetterjavaer/images/nice-article/other-wodssqbsforeveryoung-7795b016-e2dd-4dda-bd96-0b33a583a916.png)

>二哥：我之前给球友们有推荐过，不同于一般的比赛，非常的酷。

### 查找资料

确定参加后就开始查找资料，国内国外中文英文资料都在搜。

因为官网的搜索并不是很好用，我的主要技术栈是 Java，于是想从一些Java社区入手，在官网上搜索 Java，结果会连 Javascript 的社区也一并搜索出来，我觉得这很不方便，于是将官网2021年的项目信息爬下来，存到数据库里。

![](http://cdn.tobebetterjavaer.com/tobebetterjavaer/images/nice-article/other-wodssqbsforeveryoung-b3bed841-fa05-4c2b-b0dc-ff44dfff274c.png)

然后用 SpringBoot 读取出来做些简单数据处理输出到MD文件中，也就产生了早期的 gsoc-analyse 项目，本意是为了更好的查找符合自己技术栈的项目。

![](http://cdn.tobebetterjavaer.com/tobebetterjavaer/images/nice-article/other-wodssqbsforeveryoung-198ec1e2-ed1f-4e94-99d5-3b90f4d39990.png)


### Casbin 奇遇

gsoc-cn有一个gitter群（一个聊天室，可以查看很久之前的信息），我查找资料的时候，翻看了近2年的所有聊天记录，发现了 Casbin 的罗老师有在收人, 我去加了群，也给罗老师发了简历。

因为我当时比现在更菜，简历上也没什么能看的，硕士还写了个电子信息，让罗老师误以为是 EE （*Electronic Engineering* ） 而不是 CS （*Computer Science* ），这也给我提了个醒，看简历的人不一定和写简历的人有相同的知识背景，只是大致相等，对于部分可能出现误会的地方应该标识/解释清楚。

![](http://cdn.tobebetterjavaer.com/tobebetterjavaer/images/nice-article/other-wodssqbsforeveryoung-cbaf3e81-8e46-4448-9665-9894f23584f8.png)

然后我又和罗老师围绕着我简历交流了一些其他问题（后来才知道罗老师是两届GSoC学生，北大博士，跪了

最后罗老师还是友善的给了建议，其实一直知道自己菜，但没能完全找到自己的弱点。如果是想一直靠技术吃饭，但活到老学到老是必然的。即时是想先进个好点的厂打工，知识的深度也是要远比广度重要的。


### 21年11月 申请维护GSoC QQ群

我感觉gitter上交流没有群聊方便，gsoc-cn之前的QQ群也没人维护了，我建立了新的QQ群，并发到Gitter上，又在GitHup上的GSoC-CN仓库上提交了issue，申请把QQ群加入到他们的readme中，让更多的人加入到群里。

仓库的reviewer也同意了我的请求，让我提交pr，然后快速的学习了下pr之类的操作提交了第一个pr。

![](http://cdn.tobebetterjavaer.com/tobebetterjavaer/images/nice-article/other-wodssqbsforeveryoung-e21c3f8a-cb84-4eab-8f1f-c74929c076fb.png)

算是迈出了个人开源的一小步

### 22年4月 前期准备及提交申请

大致就是我先选了一个社区，社区不是很活跃（一个博士课题组的社区，他们都很忙，一个pr得审好久好久），我没有收到正反馈以及不知道能做些什么，也就放弃了这个社区。

也是运气使然，我后来的mentor 在群里发布了社区的项目，我一开始不知道他是mentor，先加了他微信，看了社区的项目，发现有一个是自己还敢尝试一下的，然后在github上发现了项目导师的联系方式

巧的是，我已经加了他的微信（在不了解项目时加了联系方式，后面选的项目刚好是他当导师😂

因为之前看了很多经验贴，建议不要在没了解过项目的前提下和导师交流

后面也就开始了贡献，在社区里解决了第一个 good first issue 后初步了解了项目，

后面开始解决其他问题时，也遇到了愿意帮忙解决问题的贡献者（Jooks 、Y哥、福哥 .....

（算是另一种意义上的组>部门>公司了）

中间也是提交了一部分pr

然后花了一周每天2-3点睡，学习了项目中用到的另一个东西

晚上疯狂用GitHub 的 action 做实验，最后做出了一个demo

![](http://cdn.tobebetterjavaer.com/tobebetterjavaer/images/nice-article/other-wodssqbsforeveryoung-93f80a9f-8fc5-4411-9bd8-41660b11da81.png)

期间也和项目mentor一直在讨论项目细节，mentor也给了很多建议

![](http://cdn.tobebetterjavaer.com/tobebetterjavaer/images/nice-article/other-wodssqbsforeveryoung-d6156f48-72d4-4b95-aa85-e4c219df78ca.png)

或许是之前写保研申请书的时候经验起了作用，再加上看了很多前辈的申请书，proposal 中加了一些花里胡哨的图、apache要求的内容，mentor reveiw之后还夸了我的 proposal （开心～

![](http://cdn.tobebetterjavaer.com/tobebetterjavaer/images/nice-article/other-wodssqbsforeveryoung-8c489b1a-7bf4-4fb8-8c49-df5082bfb815.png)

gsoc是支持一个人申请三个项目，我一直在这个项目上探索，最后也就申请了这一个项目

![](http://cdn.tobebetterjavaer.com/tobebetterjavaer/images/nice-article/other-wodssqbsforeveryoung-5a635f72-db85-495d-bd4b-1bf7f1c21531.png)

### 22年5月 GSoC-CN社群分享会

建立QQ群之后，因为有gsoc-cn的引流，也吸引了很多小伙伴

比如后来我们一起举办分享会的 cheverjohn, 彼时他还在 Apache Apisix 实习，也认识很多开源大佬，和他交流后也了解到了很多关于Apache 基金会的东西，然后我们就在群里举办了 GSoC-CN的第一个分享会，是由 Skywalking 的 Committer 江前辈 （Apache SkyWalking Committer ｜ Google Summer of Code 2021 Student ｜ pingcap intern ）主讲的 关于OSPP 的 分享会。


### 侥幸中选

分享会之后不久，就是 GSoC 开奖了，规则限制导师不能提前透露相关信息，我也没有去问，公布名单的时间是国内时间的晚上两点，我还记得那天晚上我开了个腾讯会议，群里很多人一起在那等待，2点过了一会等到了第一封邮件。

![](http://cdn.tobebetterjavaer.com/tobebetterjavaer/images/nice-article/other-wodssqbsforeveryoung-266d9854-71f2-4650-9c4c-b0bc40e454a1.png)

## 22年6月 开题与GLCC

这里首先要感谢我的导师，没有他的“支持”，我也不能这么自由。

我导师应该是个反卷达人了，也不加班，平时自己接点项目自己做，学生想做可以做，不想做也没事，工程领域里的他全都会，前后端嵌入式人工智能都会

在开题这件事上，他允许我自己去探索，即使他自己也不懂我当时想做的云原生领域。

我一开始不懂为什么不能直接放手学生去做自己想做的，后来和罗老师交流才明白导师能让我做是多么不容易。

对于研究生来收，一个组通常都是做同一个细分方向的，如果有个学生要做其他领域的东西，对于导师来说，这个东西他也不懂，也就很难给出指导，所以一般不会允许自己的学生去做其他方向。

后来和导师商量着先自己去探索，如果探索出了些东西，很好。如果没有，那就需要在他指导下做点东西。（毕业还是要毕业的，兴趣不能当饭吃

### 学习分布式相关知识

因为对分布式比较感兴趣，之前看谷歌的三驾马车也是囫囵吞枣的阅读完了，没有真正的学懂它们。

然后从谷歌、知乎、GitHub、各种社区搜寻分布式的资料

得益于谷歌的搜索及排名算法，我找到了很多不错的资料和博客

然后就是自己看论文，看项目代码

花了几周，学了一些基础知识，自己太菜了，没人带没能深入到具体的某个方向

后续因为在GLCC上看到了感觉合适的项目，和校内导师商量之后觉得可以作为毕设，就去申请，因为自己没申请上，用一个自己感兴趣的东西作为毕设的想法也就泡汤了 😭

### GLCC-开始-结束

彼时，计算机学会的 GLCC 刚开放申请，我也申请了一个项目，分布式相关的，也和导师做了一些交流，可惜，太菜了，没能获得社区导师的认可。

![](http://cdn.tobebetterjavaer.com/tobebetterjavaer/images/nice-article/other-wodssqbsforeveryoung-ba67879f-fa53-43d8-a37c-d3e9a1419665.png)

路漫漫其修远兮，吾将上下而求索

## 22年8月 日常实习求职实录

### 投递&面试

花了一个月面试

小厂、中厂、大厂，除了字节约面拒了以外，其他约面的都面完了

因为之前花时间入门了一下分布式的东西，再加上当时已经写了 这篇博客，所以将一些分布式的东西也写在简历上，我觉得是运气加持，遇到了一些比较match的面试官，他们有的懂分布式，就会问一些问题，这些问题，我有的会，有的以前没思考，借用他们的提问，我完善了我的八股串，后期熟练之后可以不间断输出自己的理解

有的不懂，那我会从其他方面聊一些入门知识，聊着聊着就耗完了面试时间，做道算法题，这场比试就结束了。

可能是我唬住了面试官，除了一开始投的某八股厂，剩下的面试都过了（以及一堆面完之后没发感谢信也没发后续流程的公司）

### Offer 选择--人生处处CAP

靠着8分运气，也拿到了一些offer，大厂、中厂、技术厂、小厂外包、传统公司都有，

选择起来说简单也简单，自己学历不够好，选个大厂学学项目规范，让简历看起来好看一些。

然后就剩下了几家了，但都是卧龙凤雏，base、部门、公司 每个offer都欠一样，或许人生处处CAP吧

## 23年1月 认识了更多大佬

找日常实习时，认识了也在准备日常实习的 ConquerJ (现在是titok的实习生)，后来又认识了更多有实习/准备找实习的同学。

### 给巨佬们跪了


目前有：

获得 N个 SSP 算法岗 offer 23届佬哥 ｜ N个 SPP offer 佬哥们 ｜23届 阿里P6 佬哥 ｜top +米哈游 佬哥

top+顶会+大厂实习佬哥 ｜ 985+NUS 佬哥 ｜ UCLA + 华尔街量化佬哥

Apache 某社区 Committer 佬哥 | CNCF 某社区 Reviewer 佬哥

本科发顶会论文佬哥 ｜国内顶尖实验室佬哥 .......

**“我经常被他们嘲笑，因为我有一个offer是sp”**

**来看看部分佬哥们的自我介绍：**

**23届 11 个算法 SSP Offer**

![](http://cdn.tobebetterjavaer.com/tobebetterjavaer/images/nice-article/other-wodssqbsforeveryoung-8b9e5a74-5493-4fe7-9bf7-02ff33dbdbcd.jpg)

![](http://cdn.tobebetterjavaer.com/tobebetterjavaer/images/nice-article/other-wodssqbsforeveryoung-bd583842-e881-486b-a710-1bef835804b2.png)

 
![](http://cdn.tobebetterjavaer.com/tobebetterjavaer/images/nice-article/other-wodssqbsforeveryoung-067d79e6-46bf-495b-a411-b678a3358988.png)

## 最后

### 回首才发现走出去了很远

如同乔帮主在斯坦福演讲中所讲的

> 当然，当时的我没有办法把这些点点滴滴连接起来，但当我从这回头看时，一切都变的清清楚楚。
> 
> 的确如此，没有人可以未卜先知，把自己所学到的东西连接在一起，我们只能在回首的时候，发现这些是如何改变现在的自己的。
> 
> 所以，你必须要有这样一种信念，那就是你现在的所有点滴，都会在未来的某一天连接起来，改变你的人生。
> 
> 你必须要有一种信念，相信胆识，命运，生活，轮回，无论什么都好。
> 
> 因为通过这些信念，会带给你遵从内心的勇气。
> 
> 即使你内心的声音让你走一条人迹罕至的路，这些信念也会给你勇气，然后改变一切。

当时因为感兴趣而去准备GSoC，去维护QQ群，去举办活动，才能在后面认识了很多前辈，进入了另一个圈子。

GSoC的活动，或许并没有让我的编程水平有突飞猛进式的提升，但通过参与它，我有了勇气去尝试新的未知的东西，这是最大的收获。也因为参与GSoC，我认识了社区里的前辈，后期投递实习时拿到了很多内推机会。

当时因为兴趣去学的分布式基础知识，没能在毕业设计中直接用到，但在后面面试中用到了很多，也获得一些面试机会，获得一些offer。

当时因为喜欢交流，加入了[二哥的编程星球](https://mp.weixin.qq.com/s/CljCSezUgoBXb-T9wbIGww)，才能在后来认识了八股战神&放弃直博复旦的冰冰同学，认识了三个月上岸的titok的凡哥.......

没有人可以未卜先知，我们只能基于当前时间之前的经验做出选择

直到回首望去，所有的脚步都会被串联起来，指向你现在的位置

### Follow your heart

不一定大公司就适合每一个人，可能它要求实习生日报，正式员工okr，双月okr，可能每天要开站会，可能要早上8点上班，也可能支持永久远程。

公司有很多很多，但我们很难知道自己想要什么。

### 读书好 多读书 读好书

大学时人傻，没有好好利用好时间

读研后，因为睡眠一直不好，控制变量做了些实验后觉得是睡前没有平复心情

然后开始看书，小说、传记、技术书都看

学校的图书馆很好，一次可以借很多本，借完放床头，睡前开始看，看个1h再睡，睡眠改善了很多。

> 在这个信息纷杂的年代，读书可以帮助我们更好的思考，

很多经典技术书也是非常值得一看的，还记得面试某游戏厂时遇到的一个问题，最近有看什么书吗？

当时在看DDIA，刚读完吴军博士的软能力，对着面试官就是一顿输出😂

多读一些经典书、好书，总会派上用场的


>参考链接：[https://erdengk.top/archives/wo-de-shuo-shi-qian-ban-sheng](https://erdengk.top/archives/wo-de-shuo-shi-qian-ban-sheng)，整理：沉默王二
