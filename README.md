# DashBoard
## About
网络在线电影购票轻量级系统

主要功能：
- 在线购票
- 在线退票
- 电影简介、院线信息
- 个人中心

## 迭代
### 第一次迭代
目标：熟悉开发所需软件工具，完成在线购票这一基本任务
#### week1
* 需求分析：给出此次迭代基本
* 详细设计：无
* 编码实践：确定前端框架与后端接口
#### week2
* 需求分析：确定购票需求
* 详细设计：确认建立数据库，实现个人中心
* 编码实践：学习前端框架与后端接口

## Team Profile
##### 团队名称 ：Aurora Borealis（北极光）
##### 团队目标 ：完成轻量级在线电影购票系统开发
##### 团队成员 ：廖泽林 廖泽祥 刘洋旗 阿布都乃比江 岑灼良 陈炫佐
---

### 成员任务分配

**刘洋旗**
- 产品经理：负责产品的需求分析与功能设计，把控总体进度，协调后端与前端对接

**廖泽林**
- 后端工程师：负责后端服务层和数据层框架的开发工作，协作测试工作与调试工作

**廖泽祥**
- 后端工程师：负责后端框架总体实现，数据库技术开发和后期性能优化工作

**阿布都乃比江**
- 前端工程师：负责前端框架总体实现，辅助前端性能优化与测试

**岑灼良**
- 前端工程师：负责前端框架细节部分，后期前端性能优化与初期调试

**陈炫佐**
- 前端工程师：负责前端框架细节部分，协调前端与后端对接，相关客户端界面开发工作与测试工作

## investigation
### 背景
现在中国大部分的家庭都喜欢在家里置办属于自己风格的家庭影院。但是，仍然有很人喜欢到电影院去看电影。因为家里的气氛毕竟不如影院好。所以，现代家庭影院的出现并不会让电影院没有生路。

为了提高劳动的效率、节约成本、提高服务质量，我们小组开发本项目。用以方便电影票售票和客户的购买。通过这个软件，可以很快实现一些常用的服务，并保证无错、高效。每个社会服务系统都有自己的一套管理机制。当然，电影院也不除外。其实电影院的管理系统应该来说比其他的社会服务系统的管理要简单一点。电影院不外乎是引进电影，制定播放影片的时间表，买票，检票进场观看，还有就是一些数据管理方面的事。如工作人员管理，票务管理等等。为了工作机制简单有序，必然要引进一套管理系统。

### 现有主流软件

#### 淘票票
##### 优势：
- 简洁美观，专注电影购票
- 依附淘宝超大流量，最大限度提升站内流量
- 取票方便，无需排队
##### 劣势：
- 强行插入广告，用户体验较差
- 价格相对较高
##### 产品特色：
主栏目仅有三个，且全部与电影购票相关，十分简约，红白配色，清晰明了。内嵌听歌功能，颇显累赘。

#### 百度糯米
##### 优势：
- 团队购票，价格便宜
- 取票方便，无需排队
- 依附百度超大流量，最大限度提升站内流量
##### 劣势：
- 产品推出较晚
- 附带功能过多，操作复杂
- 特色不鲜明，模仿程度较重
##### 产品特色：
主栏目高达十个，且附带了大量额外功能，界面繁琐，但同样决定了该款软件的定位不止于电影购票。

### 产品定位
我们预计制作完成一款轻量级的电影购票软件，不附加过多的功能，导致使用复杂、上手困难，拥有简单、美观、方便、易上手、需要内存小、运行快速的特点

## Vision
### 目标
- 通过互联网实现在线电影购票
- 建立后端数据库，存储用户信息，搭建个人中心
- 保证软件的轻量级与易上手性

### 关键问题
- 前端开发与后端开发的实践问题
- 前端与后端的对接问题
- 数据库搭建与算法问题
- 团队合作与任务合理分配问题

### 竞争产品
- 百度糯米
- 淘票票
- 美团等

## Product Backlog

### 怎样编写Backlog
产品backlog是Scrum的核心，也是一切的起源。从根本上说，它就是一个需求或故事或特征等组成的列表，按照重要性的级别进行了排序。它里面包含的是客户想要的东西，并用客户的术语加以描述。

我们叫它故事，有时候也叫做backlog条目。我们的故事包括以下字段：

ID统一标识符，就是个自增长的数字而已。以防重命名故事以后找不到它们。

Name(名称)简短的，描述性的故事名。比如“查看你自己的交易明细“.它必须要含义明确，这样开发人员和产品负责人才能大致明白我们说的是什么东西，跟其他故事区分开。它一般由2到10个字组成。

Importance(重要性)产品负责人评出一个数值，指示这个故事有多重要。例如10或150.分数越高约重要。

Initialestimate(初始估算)团队的初步估算，表示与其他故事相比，完成该故事所需的工作量。最小的单位是故事点(storypoint)，一般大致相当于一个man-day(人天数)，例如把3个人关在一起，大约需要4天时间，那么初始估算的结果就是12个故事点。

How to demo(如何做演示) 它打猎描述了这个故事应该如何在sprint演示上进行示范，本质就是一个简单的测试规范。“先这样做，然后那样做，就应该得到。。。的结果。“ 如果你在使用TDD(测试驱动开发)，那么这段描述就可以作为验收测试的伪码表示。

Notes(注解) 相关信息，解释说明和对其他资料的引用等等。一般都非常简短。

### 本产品的Backlog

![image](https://github.com/ABTicket/Initial-design-and-planning/blob/master/image/product%20backlog.png)

### Requirement specification

#### 注：没找到虚线箭头，inculde皆是由左指向右，extend皆是由右指向左

#### 用户用例

![image](https://github.com/ABTicket/Initial-design-and-planning/blob/master/image/User%20use%20case.png)

#### 总体用例
![image](https://github.com/ABTicket/Initial-design-and-planning/blob/master/image/use%20case.png)

## 生产规范与指南

### 前端规范
#### 文件/资源命名

在 web 项目中，所有的文件名应该都遵循同一命名约定。以可读性而言，减号（-）是用来分隔文件名的不二之选。同时它也是常见的 URL 分隔符，所以理所当然的，减号应该也是用来分隔资源名称的好选择。

请确保文件命名总是以字母开头而不是数字。而以特殊字符开头命名的文件，一般都有特殊的含义与用处（比如 compass[1] 中的下划线就是用来标记跳过直接编译的文件用的）。

资源的字母名称必须全为小写，这是因为在某些对大小写字母敏感的操作系统中，当文件通过工具压缩混淆后，或者人为修改过后，大小写不同而导致引用文件不同的错误，很难被发现。

还有一些情况下，需要对文件增加前后缀或特定的扩展名（比如 .min.js, .min.css），抑或一串前缀（比如 3fa89b.main.min.css）。这种情况下，建议使用点分隔符来区分这些在文件名中带有清晰意义的元数据。

#### 协议

不要指定引入资源所带的具体协议。

当引入图片或其他媒体文件，还有样式和脚本时，URLs 所指向的具体路径，不要指定协议部分（http:, https:），除非这两者协议都不可用。

不指定协议使得 URL 从绝对的获取路径转变为相对的，在请求资源协议无法确定时非常好用，而且还能为文件大小节省几个字节。

#### 文本缩进
一次缩进两个空格。

#### 注释
注释是你自己与你的小伙伴们了解代码写法和目的的唯一途径。特别是在写一些看似琐碎的无关紧要的代码时，由于记忆点不深刻，注释就变得尤为重要了。

编写自解释代码只是一个传说，没有任何代码是可以完全自解释的。而代码注释，则是永远也不嫌多。

当你写注释时一定要注意：不要写你的代码都干了些什么，而要写你的代码为什么要这么写，背后的考量是什么。当然也可以加入所思考问题或是解决方案的链接地址。

#### 代码检查
对于比较宽松自由的编程语言来说，严格遵循编码规范和格式化风格指南就显得极为重要。遵循规范固然很好，但是有自动化流程来确保其执行情况，岂不更佳。

### 后端规范
#### 命名规范
##### 命名总规则

所有名称的字符范围为：A-Z, a-z, 0-9 和_(下划线)。不建议使用其他字符作为名称。
采用英文单词或英文短语（包括缩写）作为名称，不使用无意义的字符或汉语拼音。
名称应该清晰明了，能够准确表达事物的含义，最好可读，遵循“见名知意”的原则。
提倡英文命名，切忌英文和拼音混用。

##### 类库Namespace命名

类库分成三个层次，分别是.Net框架、公司基础公共类库、项目级类库。公共类库参照已有类库引用，以下主要对项目级Namespace命名提出参考建议：
- YesHJ.Ucenter 用户中心
- YesHJ.Cms 网站内容系统
- YesHJ.Class 网校
- YesHJ.Bulo 社区
- YesHJ.Shop 网店

命名空间建议： YesHJ.{ProductLine}.{Appname}.XXXX =>例如：YesHJ.Bulo.KaoDian.XXXX

##### 变量、方法命名

私有变量及方法参数使用camel命名（第一个词首字母用小写，其它词首字母用大写）
公共变量、方法、类使用Pascal命名（单词的首字母用大写）
公有变量尽量使用Property ，慎用Public Static变量；
变量命名要有意义：拒绝无意义的变量a，a1，b，k等；
典型的增删改查方法命名如下：比如获取GetUserList
用名词或名词短语命名属性；

##### 文件、文件夹命名

目录命名建议和Class命名要求一致，不要出现“_”和“小写”开头，已经用小写的不需要调整，保证命名空间的命名符合标准即可。
特殊或者系统文件夹可保持大写方式，比如App_Code、App_WebReferences等；
文件命名一般采用小写，应用加下划线方式命名。
页面的命名和Class命名要求一致，注意不要小写开头。

### Web服务
#### URL命名：

老的Api方式：app.hujiang().com.hjdns.net => {appName}.hjapi.hujiang.com (内部域名解析) 还有一些是使用 {appName}.yeshj.com

#### 传参：不要暴露参数类型和参数值

#### 类型和应用场景：

Web Service：传统用法，不宜调用太频繁。注意要有异常保护，即使不返回结果，也不要影响页面的其他功能，尽量用异步。
Rest Service：一般参数要保护；同样不宜调用太频繁。尽量用Json做数据格式。
WCF Service：适用于高安全、频繁调用，同时不能直接产生数据库关联的场景。

### 代码风格

#### 代码前置后置

代码前后端分离：(code-behind)
好处，逻辑比较清晰，容易进行重构。
缺点：发布、维护繁琐一些。

今后新项目必须采用代码后置(code-behind)，不要再使用单页面（single-page code ），特别是UserControl等需要复用的，自己在维护代码时，修改单页面程序时，要把它改成code-behind。

建议：

需要简化前台代码的数量和复杂度，必要时需要分离出独立的Service层，前端的C#代码仅仅用来做交互性的操作，不要包含太多复杂逻辑。
新项目尽量采用Web Application Project，不建议使用Web Site Project。

#### 注释

逻辑理解注释，采用//加注释语句
写在注释语句之前一行或者紧跟着注释语句后同一行
public,protect函数或者属性注释采用/// VS自动添加注释模式，
所有共有变量和共有方法都需要注释，类库中的protect和public的类要加类头注释

#### 书写格式

在程序代码间一般不要连续留空两行
如果一个函数的参数很多，要么一行全部输入，要么一行一个参数
不要用空格缩进，统一用制表符缩进
对于一些比较长的块，使用#region 和#endregion 来括起来
单行代码要 < 80个字符
C#代码中的SQL要排版，方便阅读和维护；格式：参照数据库开发规范。
【程序开发安全与性能策略】
参数检查 常见的像字符串参数，一般调用 String.IsNullOrEmpty函数来检查，或按照需要自己编写函数检查。 对于数字、电话号码、身份证号等检查采用公用类库方法进行服务器端检查。 对实体对象的ToString操作，一定要先做非空判断，或者调用Convert.ToString方法；
Sql注入防范 对外部传入参数进行合法性检查，比如传址、表单、cookies数据； 写数据库相关服务时，非特殊情况，必须使用参数化方式传递变量参数； 敏感表用存储过程操作，限制连接sql权限，只赋予Select以及存储过程执行权限更新数据；
对于数据库连接的策略是尽早释放，如SqlDataReader用完之后一般采用Using自动释放连接，或者要主动调用Close方法关闭连接。
对于连续的ID，要防范恶意用户做推测性的攻击行为： 可以使用Framework里面的FakeIDHelper、GuardIDHelper类进行伪装。
日志：

比较大的项目，我们需要选用Log4NET这样的比较成熟的日志组件。小一些的项目也可以使用.NET内置的System.Diagnostics里面的日志方法。
除了要建立ErrorLog日志之外，建议对每个后台服务的执行情况和执行时间做必要的监控： 可以写Log文件、数据库、远程日志服务等，但是要考虑尽量减少对性能的影响，增加可维护性。 特别是首次上线后，要通过监控，密切观察系统的运行情况，了解系统的性能瓶颈、产生原因等，方便对系统进行持续性优化。
