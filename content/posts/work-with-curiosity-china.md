---
title: CuriosityChina 招人
date: 2021-08-21
draft: false
tags: ["reality"]
---

目前我在一家小公司（CuriosityChina）工作，能挣钱和可以做的事很多，但我们开发团队目前人比较少，所以需要招前后端开发、SRE 和产品经理。每次跟人介绍团队都会发一堆差不多的东西介绍，这篇博客就是那个差不多的东西

## 在招岗位

我们现在在招的岗位如下：

1. 后端开发，主要写 Go
2. 后端 Leader，做管理，也需要写代码
3. 前端开发，主要是 TypeScript/React，最好是网页和小程序都能写，没写过但是能很快上手也行
4. SRE
5. 产品经理，主要面向企业客户，如果有意愿可以单独联系我（因为看到这个的大多是程序员）

以上岗位都可以在北京办公室（亮马桥）或者上海办公室（静安区）入职，看你方便，特别优秀的 SRE 可能能长期远程，需要你自己证明

### 后端开发

后端 JD：[Golang 开发工程师](https://www.hotjob.cn/wt/FARFETCH/mobweb/v8/position/detail?openid=oGo9u5mgjMwjcnmoOmjxWh1GknHs&recruitType=2&paramStr=121301_2_1_0_0_121959_121959&brandCode=1)，如果链接失效了在微信里搜索“Farfetch 招聘”，从底栏“加入我们”可以找到最新的 JD 链接

主要工作是写业务，各种各样的产品线和各种各样的项目，日常工作里大部分是当 CRUD boy，但是也期待你自己从业务里找到深挖和进步的点推着业务前进

最重要的要求是保持思考、对用到的工具和业务有一定的好奇心，能多想一步多看一步，多问一句：为什么会这样？面试时面试官会从方方面面去寻找你身上关于这一点的答案

后端面试不考手写算法，会考的内容基本都是你在简历上写了的，也不会问得非常刁钻，基本上都是我们在实际业务里遇到过的问题，面试只会确保一件事：你真的能写好业务

### 后端 Leader

后端 Leader 也需要写代码，同时需要管项目进度、管人以及技术调研升级，由于我现在的老板转岗去做 Architecture 相关的工作，所以该岗位目前空缺，锐意招人中，非常欢迎推荐和自荐

### 前端开发

前端 JD：[前端开发工程师](https://www.hotjob.cn/wt/FARFETCH/mobweb/v8/position/detail?openid=oGo9u5mgjMwjcnmoOmjxWh1GknHs&recruitType=2&paramStr=115001_2_1_0_0_121959_121959&brandCode=1)，如果链接失效了在微信里搜索“Farfetch 招聘”，从底栏“加入我们”可以找到最新的 JD 链接

主要工作是写业务，各种各样的产品线和各种各样的项目

要求理解和掌握 HTML/CSS 和 JS，面试时问的问题都不会刁钻和八股，会写点特别短的代码实现一个很简单的小功能，也是确保一件事：你真的能写好业务

### SRE

我司 SRE 可以做的事很多，自由度高，经常需要自己去调研可以做什么然后开始做，能给的钱也比普通开发多，当然要求也高一些，暂时没有找到 JD，有兴趣聊聊的话我可以直接帮你联系我司 SRE

## 团队

CuriosityChina 是个 2013 年创业的 ToB 公司，主要是围绕微信生态为奢侈品品牌做营销，能被普通消费者见到的产品是服务于奢侈品品牌的公众号和小程序，此外还有基于企业微信的产品线和基于品牌自有数据的产品线。2018 年被奢侈品电商 Farfetch 收购成为旗下中国子公司，收购后不久 Farfetch IPO，CuriosityChina 基本保持独立运营，开发团队继续做之前 ToB 相关的业务，直到现在

目前开发团队构成：5 个前端，4 个后端，1 个测试，1 个 SRE，2 个设计师和 1 个哪里缺人往哪搬的 CTO，此外还有 2 个产品经理和若干个项目管理人员。团队人不多，有职级（人事、职级、薪资跟随 Farfetch），管理扁平（所有人都写代码，不努力点可能还没有 CTO 写得多）。团队内部氛围不错，不卷，公司下午 6 点关空调、8 点还不走老板就要赶人，10 点灯都熄了。开发同事之间有信任感，偶尔有互相坑到，但是没有甩锅和推诿，也不会打官腔当油子，总的来说是一帮做实事的人

## 工作

### 技术栈

后端主要语言是 Go，偶尔能看到一些工具是 Python/NodeJS 写的，日常用的工具：

- MongoDB/PostgreSQL：主要的数据库是 MongoDB，有一条新的、跟数据紧密相关的产品线开始使用 PostgreSQL
- ElasticSearch
- [nsq](https://nsq.io/)：业务形态比较轻量，消息队列没有使用 Kafka/RabbitMQ/RocketMQ，但是欢迎你有相关经验
- [echo](https://github.com/labstack/echo)：也有一部分上古项目使用的是 beego，不过很少维护了
- [ngrok](https://ngrok.com/)
- Docker

前端主要语言是 TypeScript，框架用 React，CSS 好像用的是 less，网页端用了很多 antd，小程序端主要是 Taro，此外我就不清楚了，我只会在写 CLI 工具和油猴脚本的时候写 JS，所以更详细的情况不是很清楚，可以在面试的时候问面试官

开发工具上限制很少，不强制要求用某个 IDE 或者编辑器，前端大多数都用 VS Code，4 个后端分别是 Intellij Idea、Goland、VS Code 和 Vim，只要代码能过 CI linter，用记事本都可以

### 开发体验

整体项目风格是微服务的，目前有近 1000 个 GitLab Repository，有开发、测试、生产 3 个环境，所有应用都跑在 Docker 里，有 k8s 和 Mesos 两套编排工具（在逐步往 k8s 上迁移）

一般是在本地连着开发环境开发，开发完之后提交到 GitLab，将代码合并到特定分支就会自动部署到特定环境，除了写代码和合并分支以外的跑测试、部署之类的麻烦事，基本都由 CI/CD 包办了，体验还是很不错的

### 协作工具

此外还有一些日常会使用的工具

- Slack：开发团队内部以及 Farfetch Global 的沟通工具，有个有趣的点是禁止私聊，所有消息都必须发在某个 channel 里，长久来看是对开发人员的保护，想想为什么
- 企业微信：CuriosityChina 和 Farfetch 中国区的聊天工具
- Confluence：文档管理，我经历过的 3 个公司和 4 个团队中，CuriosityChina 是文档维护得最好的了（虽然依然有很多不足）
- Jira：项目进度和 issue 追踪工具，摘录一下同事们的签名：“今天你建 Jira 了吗”、“没有 Jira 不出图，不接受空白 Jira”
- 1Password：密码管理器

## 人事

### 作息

作息可能是这个团队最奇怪和让人最难适应的一个地方，早 10 晚 7，双休，中午 13:00-14:00 之间午休和吃饭，加班超过 21:00 可以打车报销和提供 60 一位的加班餐报销额度

实际上的日常是 10 点出头到公司，晚上 7 点到 8 点之间下班，工期特别紧张和因为线上出问题的时候会有周末加班，周末加班会增加对应的调休天数，调休天数不过期也没有使用条件，申请就可以用。我去年因为工期紧张加了在周末加过 2 天班，因为线上事故周末加了两天班，周末加班就这么多了

偶尔晚上也会有超过晚上 9 点下班的情况，我去年大概有 40 天左右。基本上也是看自己工作情况，有同事常年来得晚走得也比较晚，也有同事按点来按点走，不会因为上下班时间有心理压力，非紧急情况老板也不会在非工作时间夺命连环@，临下班安排非紧急的工作一般也会说“这个你明天做就好”，我目前还没有遇到过“这个我今晚就要、你加班给我做，做完再走”的情况

偶尔会有集体活动和老板请吃饭，也是去不去随意，比如我至今没有去过任何一次除了吃饭以外其他形式的集体活动，虽然那些集体活动也都是吃喝玩乐，但是社恐是被允许的

总的来说，老板自己可能作息不是很规律，但是会尊重你的下班时间和私人空间

此外，在疫情严重的时候会要求和允许远程办公，比如 2020 年我们从 2 月到 6 月都是在家办公，日常身体不适、孩子生病和家里有事也可以无压力正常请假和申请在家办公，这方面给予了员工个人充分的尊重和信任

### 工作压力

坦白来讲工作压力不小，公司氛围虽然自由（在着装、上下班时间、请假、在家办公、异地办公、年龄甚至工作内容方面都相当自由）也鼓励自我驱动，但是对每个人的期待都是“承诺了就要做到”，我感受到最大的压力来自于此。不管是对组内承诺了要提供给同事一个小工具、还是对项目和 CS 承诺了要按时上线，所有人对你的期待都是“既然你承诺能做到，那你就得做到”

虽然这并不是一个硬性要求，偶尔出现 delay 和食言也不会受到明显的惩罚，但是会消磨其他人对你的信任。所以不管是老板还是同事，都会推动和鼓励你兑现承诺，这种推动和鼓励会让你有时候压力很大，需要自己平衡好，以及努力去兑现自己的承诺

### 文化氛围

公司相当包容，有很多 35 岁以上或者快要 35 岁的员工，也有挺多有孩子、时不时需要请假或者在家办公照顾生病的小孩的员工，公司这方面都能在不是特别影响正常工作的情况下予以照顾和倾斜，哪怕我这种奉行不婚不育的人也觉得挺有温度

此外对 LGBT 群体和女装大佬们也很包容，大家可以在不影响他人的情况下自由发散天性，公司也会在 Pride month 举办一些庆祝活动

### 工作氛围

工作氛围相对开放，老板只在需要拍板的时候给结论，日常工作里自由度比较大，积累起足够信任之后老板会主动放权让你去做一些你觉得有意义的事，在试图尝试新东西的时候也有足够的空间

跟其他团队的协作也相当坦诚，有问题直接指出和拿到台面上讨论，能就事论事得处理问题

### 薪资待遇

薪资、职级遵照 Farfetch 政策

工程师工资范围是月薪 20k-50k，具体薪资看面试评级，不会恶意压低工资，不管算时薪还是总包在业内都挺有竞争力，每年保底 13 薪（不满一年的话第 13 薪会按照入职天数按比例折算），此外还会有一个受当年绩效影响的年终奖，浮动范围基本上是一个月的月薪，所以一年总到手大概是 14 薪左右

入职时还会有一个 Farfetch 在纳斯达克的股票包（RSU），总价值换算成人民币大概相当于你12个月工资（这个政策后续变化我不清楚，反正我入职时这么多），RSU 分 4 年得权，每年均匀得到 25%，得权之后的 RSU 可以在遵守公司保密条款的情况下、在公司允许的交易窗口期卖出获益，得权和获益时均需要按照中国税收政策依法光荣纳税，剩余部分归自己。在公司股价波动不大的情况下，差不多是干 4 年送 5 年薪资

公司没有承诺普调，但是实际上我经历过的涨薪和股票增发策略也不错。年终考核时如果绩效不错会有涨薪，入选 Key Contributor 会有股票增发，增发的股票也是按照入职时发的股票策略得权和获益

五险一金正常缴纳，公积金交 12%，逢年过节的小恩小惠不值一提，你自己买也花不了几个钱，但公司的确会偶尔送点东西

以上就是全部内容，如果有其他希望了解的内容的话欢迎通过 [https://shuxiao.wang/](https://shuxiao.wang/) 页面底部的联系方式或者是 [twitter](https://twitter.com/keaising) 联系我
