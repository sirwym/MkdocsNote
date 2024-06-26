## 赛事简介

**信息学奥林匹克竞赛**（英语：Olympiad in Informatics，简称：OI）是一门在中学生中广泛开展的学科竞赛，和物理、数学等竞赛性质相同。OI 考察的内容是参赛者运用算法、数据结构和数学知识，通过编写计算机程序解决实际问题的能力。

OI 竞赛种类繁多，仅中国就包括：

-   全国青少年信息学奥林匹克联赛（NOIP）
-   全国青少年信息学奥林匹克竞赛（NOI）
-   全国青少年信息学奥林匹克竞赛冬令营（WC）
-   国际信息学奥林匹克竞赛中国队选拔赛（CTSC）

国际性的 OI 竞赛包括：

-   国际信息学奥林匹克（IOI）
-   美国计算机奥林匹克竞赛（USACO）
-   日本信息学奥林匹克（JOI）
-   亚太地区信息学奥林匹克（APIO）

    ……

对于大部分选手而言，每年的新赛季从 9 月的 CSP-J/S 第一轮开始。

在中国，OI 竞赛允许使用的语言只有 C++（曾经也开放过 C 和 Pascal 语言，但都已停止支持）。其中，不同的竞赛对 C++ 的版本有不同的规定。考试题目一般为算法或者数据结构相关的内容，题目形式包括传统题（最常见的规定输入和输出到文件的题目）和非传统题（提交答案题、交互题、补全代码题……等等）。

## 赛制介绍

### OI 赛制

选手仅有一次提交机会。比赛时无法看到评测结果，评分会在赛后公布。每道题都有多个测试点，根据每道题通过的测试点的数量获得相应的分数；每个测试点还可能会有部分分，即使只有部分数据通过也能拿到分数。

CSP-J/S 第二轮、NOIP、省选、NOI 都是 OI 赛制。

### IOI 赛制

选手在比赛时有多次提交机会。比赛实时评测并返回结果，如果提交的结果是错误的，不会有任何惩罚。每道题都有多个测试点，根据每道题通过的测试点的数量获得相应的分数。

APIO、IOI 都是 IOI 赛制。目前国内比赛也在逐渐向 IOI 赛制靠拢。

### ICPC 赛制

又称 ACM 赛制，ACM-ICPC 赛制。每题提交后都有反馈，每道题必须通过了所有的测试点才算通过。每道题不限制提交次数，未通过会有罚时。得分以最后一次提交为准。赛时可以看到实时排名，按通过题数排名，通过题数相同的情况下按照答题时间+罚时来排名。
ICPC，CCPC，AtCoder ABC/ARC/AGC，LeetCode 周赛，牛客小白赛，传智杯都是 ICPC 赛制。

### Codeforces (CF) 赛制

[Codeforces](https://codeforces.com) 是一个在线评测系统，会定期举办比赛。

它的比赛特点是在比赛过程中只测试一部分数据（Pretests），而在比赛结束后返回完整的所有测试点的测试结果（System Tests）。比赛时可以多次提交，允许 Hack 别人的代码（此处 Hack 的意思是提交一个测试数据，使得别人的代码无法给出正确答案）。如果想要 Hack，选手必须要锁定自己的代码（换言之，比赛时无法重新提交该题）。Hack 时不允许将选手程序拷贝到本地进行测试，源代码会被转换成图片。

Codeforces 同时提供另外一种赛制，称作扩展 ICPC（Extended ICPC 或 ICPC+）。在这一赛制中，在比赛过程中会测试全部数据，但比赛结束以后会有 12 小时的全网 Hack 时间。Hack 时允许将选手程序拷贝到本地进行测试。

### exICPC 赛制

Codeforces 创造的赛制，别名很多，ex 是拓展、扩展的意思。因此，其他规则与 ICPC 赛制一样，但是解决问题所得的分数是由该题当前的分数减去不成功的提交次数乘 50。此外，比赛结束后还会有 12 小时的全网 hack 时间。
Educational Codeforces Round 是 exICPC 赛制。



### 乐多赛制

洛谷创造的赛制。比赛时可以看到结果。对于一道题的得分，计算为 $s * 0.95^{t-1}$，其中 $s$ 为分数，$t$ 为提交次数，最低得分为原来的 70%，之后再提交不会因为提交次数扣分。



## 主要比赛

### CSP-J/S

**CSP-J/S**（英文：Certified Software Professional Junior/Senior）是 NOIP 在 2019 年被取消之后，CCF 开设的非专业级软件能力认证测试，面向全年龄段。

CSP-J/S 分为入门级（Junior，简写为 CSP-J）与提高级（Senior，简写为 CSP-S）两组，赛程分为第一轮（一般在每年 9 月）和第二轮（一般在每年 10 月）两场。第一轮为笔试，考察计算机理论和操作常识和基本的算法与数学知识；第二轮为上机考试，入门组与提高组都为 4 题，其中入门组考试时间 3.5 个小时，提高组 4 个小时（CSP-S 2019 除外，该场比赛使用旧 NOIP 提高组赛制，赛程分为两天，一天 3 题 3.5 小时）。第一轮面向社会全体学生报名，经过一定的排名筛选后成绩优秀者有机会参加第二轮。

报名参加第一/二轮、第二轮后进行题目申诉等都需要向 CCF 缴费。

两轮测试都会以省为单位按照排名对选手成绩进行评级认证，分为一、二、三等。

### NOIP

**NOIP**（英语：National Olympiad in Informatics in Provinces，中文：全国青少年信息学奥林匹克联赛）是中华人民共和国组织的、面向中国（含港澳）中学生的信息学竞赛。

2018 年及以前的旧赛制：NOIP 按参赛对象分为普及组和提高组，2018 年于上海试点入门组；按阶段分为初赛和复赛两个阶段。初赛会考察一些计算机基础知识和算法基础，复赛为上机考试。时间上一般是 11 月的第二个周末，周六上午提高组一试 8:30-12:00（3.5 小时，共 3 题），下午 14:30-18:00 普及组（3.5 小时，共 4 题），周日上午提高组二试 8:30-12:00（3.5 小时，共 3 题）。全国使用同一套试卷，但是评奖规则按照省内情况由 CCF（中国计算机学会）统一指定，并于赛后在 [NOI 官方网站](http://www.noi.cn) 上公布。各省的一等奖分数线略有不同。

NOIP 于 2019 年 8 月 16 日 [被 CCF 暂停](http://www.noi.cn/xw/2019-08-16/715365.shtml)，于 2020 年 1 月 21 日 [被宣布恢复](http://www.noi.cn/xw/2020-01-21/715520.shtml)。2020 年起的 NOIP 赛制与以往有所不同，具体如下：

-   取消初赛，由 CSP-J/S 第一轮替代；
-   取消普及组，由 CSP-J 替代，此后 NOIP 仅有一个组别，面向提高组水平选手；
-   赛程由以往的两天共 6 题、每天 3.5 个小时，缩减为一天 4 题、共 4.5 个小时。
-   选手需要在 CSP-S 第二轮中取得一定名次才能获得 NOIP 参赛资格，具体名额各省有所差异。NOIP 省级参赛资格由该省在去年赛季中的参赛人数和成绩等有关。

报名参加 NOIP 和进行题目申诉不需要额外缴费。

NOIP 以省为单位排名评奖。截至 2019 年，大部分高校的选手获得提高组省一等奖可以得到自主招生资格。

> 2020 年 1 月，中华人民共和国教育部发布 [关于在部分高校开展基础学科招生改革试点工作的意见](http://www.moe.gov.cn/srcsite/A15/moe_776/s3258/202001/t20200115_415589.html)。意见指出，2020 年起，不再组织开展高校自主招生工作，并在部分一流大学建设高校开展基础学科招生改革试点（强基计划）。

### 省队选拔赛

**省队选拔赛**（简称：省选）用于选拔各省参加全国赛的代表队，一般举行于每年的 1\~4 月。赛程上一般分为两天，每天 3 题 4.5 小时。

省选题目由各个省自行决定，目前的趋势是很多省份选择联合命题。

各个省队的名额有复杂的计算公式，一般和之前的成绩和参赛人数有关。通常来讲，NOIP 分数需要在省选的指标中占一定比例。根据规则，初中选手只能被选拔为 E 类选手，不能参加 A、B 类选拔。A 类选手有 5 人（4 男 1 女），其他选手根据给定名额和所得分数依次进入 B 队。一个学校参加 NOI 的名额不超过本省 A、B 名额总数的三分之一（四舍五入），得分最高且入选 A 队的女选手不占该比例（简称 1/3 限制或 1/3 淘汰）。

自 2020 年起，NOI 省队选拔由 CCF 统一命题和评测，有能力命题的省可自行命题，但选拔方式需得到 CCF 的批准。自 2024 年起，NOI 省队选拔恢复各省自主命题，有需求的省份可组织联考或使用他省试题，但具体方案需要得到 CCF 的批准。

### NOI

**NOI**（英文：National Olympiad in Informatics，中文：全国信息学奥林匹克竞赛）是国内包括港澳在内的省级代表队最高水平的大赛。

NOI 一般在七月份举行，选手分为正式选手与夏令营选手两类。正式选手又分为三类，其中 A、B 类为省队正式选手，C 类选手为邀请赛选手。A、B 类对应省队的 A、B 类选手（其中 A 类在计算成绩时会有 5 分加分）；C 类名义上是学校对 CCF 做出突出贡献后的奖励名额。夏令营选手分为 D、E 类，分别对应以非正式选手身份参赛的高中组与初中组选手。夏令营选手如果成绩超过分数线的话，只有成绩证明而没有奖牌（同等分数含金量要低一些）。排名前 60 的正式选手组成国家集训队，获得保送资格。

在国际平台上，为了与其他同样称作 NOI 的比赛区分，有时会被称作 CNOI。

### WC

**WC**（英文：Winter Camp，中文：全国青少年信息学奥林匹克竞赛冬令营）是每年冬天在当年 NOI 举办地进行的一项活动。

WC 的内容包括若干天的培训和一天的考试。这项考试主要用于从国家集训队（50 人）选拔国家候选队（15 人），但是前一年 NOIP 与 CSP-S 第二轮取得较好成绩的选手也可以参加（不参与选拔）。

### APIO

**APIO**（英文：Asia-Pacific Informatics Olympiad，中文：亚太地区信息学奥林匹克竞赛）是一个面向亚太地区在校中学生的信息学学科竞赛。CCF 每年会在五月初举办中国赛区镜像赛。在比赛日前后会有培训活动。

### CTS

**CTS**（旧称：CTSC, 英文：China Team Selection Competition，中文：国际信息学奥林匹克竞赛中国队选拔赛）用来从国家候选队（15 人）中选拔国家队（6 人）准备参加当年夏天的 IOI 比赛，其中正式选手 4 人，替补选手 2 人。与 WC 一样，前一年 NOIP 取得较好成绩的选手也可以参加（不参与选拔）。

APIO 和 CTS 都以省为单位报名，一般按照 NOIP 的成绩排序来确定参加 APIO 和 CTS 的人员（二者一般时间上非常接近）。

### IOI

**IOI**（英文：International Olympiad in Informatics，中文：国际信息学奥林匹克竞赛）是一年一度的面向全球中学生的信息学科竞赛。每个国家有四人参赛，比赛一般会有直播。IOI 赛制中每个题目会有 Subtask（子任务），每个子任务对应一定的分数。

### 学科营

#### 北京大学（PKU）

-   北京大学信息学冬季体验营（PKUWC）：在冬令营前后举行。
-   北京大学信息学体验营（PKUSC）：一般在六月份在校内举行。由于在学校机房比赛，机房环境是 Windows，比赛系统是 OpenJudge。
-   北京大学中学生暑期课堂（信息学）：在暑假举行，面向高二年级理科学生。

#### 清华大学（THU）

-   计算机系 "大中衔接" 冬季研讨与教学活动：相当于信息学冬令营，有时也会用英文简写为 THUWC。一般共两天，上午为竞赛（第一天是标准 OI 竞赛，第二天为清华独创的 "工程题" 竞赛），下午为课程培训。

## 其他国家和地区的 OI 竞赛

### 美国：USACO

官网地址：<http://www.usaco.org/>

USACO 或许是国内选手最熟悉的外国 OI 竞赛（可能也是中文题解最多的外国 OI 竞赛）。

每年冬季到初春，USACO 会每月举办一场网络赛。一场比赛持续 3\~5 个小时。

根据官网的介绍，USACO 的比赛分成这 4 档难度（2015\~2016 学年之前为 3 档）：

-   铜牌组，适合编程初学者，尤其是只学了最最基础的算法（如：排序，二分查找）的学生；
-   银牌组，适合开始学习基本的算法技巧（如：递归，搜索，贪心算法）和基础数据结构的学生；
-   金牌组，学生会遇到更复杂的算法（如：最短路径，DP）和更高级的数据结构；
-   铂金组，适合有着扎实的算法设计能力的选手，铂金组可以帮助他们以复杂且更开放的问题来挑战自我。

在国内，目前 USACO 题目最齐全的 OJ 平台是洛谷。
