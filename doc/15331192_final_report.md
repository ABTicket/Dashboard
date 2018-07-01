## 课程学习自我总结
我主要负责后台的开发、部署：

+ **学习了一门新的语言**。在此之前没学过golang语言。正好这次系分课程需要做个项目，因此我利用这个机会学习了golang，使用golang搭建起了后台的服务。
+ **没有使用http框架**。我认为这个后台服务功能没有复杂到需要使用框架的程度，因此只是使用了一个第三方路由库mux以及golang中的http模块，加上一个使用mongodb的库mgo，自己手动搭建起了后端的结构。
+ **实现了自动部署**。利用github + travis即可实现自动构建源码，但这里离目标自动部署还有距离。因此我通过在.travis.yml文件中配置：通过源码构建之后免密连接至服务器并运行服务器上的脚本，来完成自动部署。
+ **学习、完成shell脚本的编写**。服务器上的部署脚本，需要完成从github更新代码、更新代码到容器、进行容器上服务的重启等功能。
+ **REST风格api的设计、实现**。我们的前后端利用docker实现了分离，通过REST api进行通信，因此设计、实现REST api十分重要。
+ **数据模型的组织**。电影信息、场次、座位、订单、用户等信息，都需要进行有效的组织，这部分着实花费了不少时间。
+ **使用docker支持前后端分离**。前后端各自开发互不影响，有效地提高了开发效率。
+ 感谢 @liaozx3 ，与我讨论了后端的实现细节，搭建起了后端的架构、完成了使用docker在云服务器上的部署工作。感谢 @lqAsuna ,共同讨论了数据模型的组织、存储等问题。感谢 @chenhtso，讨论了前后端对接的问题，完成REST api的设计。

## PSP 2.1 统计表
|PSP 2.1|Time Spent(h)|
|-------|-------|
|**Planning**||
| - Estimate | 1 |
|**Development**||
| - analysis| 10 |
| - Design Spec| 20 |
| - Design Review| 5 |
| - Coding Standard| 5 |
| - Design| 15 |
| - Coding| 30 |
| - Code review| 5 |
| - Test| 10 |
|**Reporting**||
| - Test Report| 2 |
| - Size Measurement| 1 |
| - Postmortem & Process Improvement Plan| 1 |

## 个人分支的 GIT 统计报告
没有使用个人分支进行开发。直接看master上的统计数据：
![贡献度](https://github.com/ABTicket/Dashboard/blob/master/image/lzl_git_contribution.png)
中间一段有波峰，是由于在测试利用travis实现持续集成，因此commit次数出现波峰。


## 最得意/或有价值/或有苦劳的工作清单

+ 后台总体架构的实现。 不使用http框架、只使用第三方路由库即实现了一个REST api的服务器。
+ 实现CI。push代码到github上即可同时将代码同步并且部署到云服务器上，极大提高了工作效率。

## 技术类、项目管理类博客清单
