## 6.Requirement specification

### 用例：用户购票

**范围**：用户购票

**级别**：用户目标

**主要参与者**：用户

**涉及及关注点**

- 用户：快捷且简单方便的查看座位信息、电影信息、电影院信息；商家提供多种多样的付费手段；自动检索功能、自动推荐功能；无弹窗广告；最优惠的购票方式推荐，默认选取。
- 电影院：热映电影置前；电影院置前；电影院默认选择和优先推荐；保存一定的用户信息；即时获取购票信息。

**前置条件**：顾客必须下载该APP，顾客必须注册登陆。

**后置条件**：即时记录并传达购票信息，确认付款通道安全有保障，随时更新电影长此信息

**基本流程**
1. 用户下载使用APP，若未注册，则在注册后登陆
2. 用户通过检索或推荐，选择电影院和电影
3. 用户确认电影信息后，用户选择座位，并提供必要信息
4. 用户确认购票，进入购票详情界面
5. 用户核实无误后，进行支付操作
6. 电影院更新该场次座位信息

**扩展**

1. 用户进入购票详情界面后，强制退出。

    - 处理方法：清空数据库，默认不进行购票

2. 用户支付过程中，APP闪退

    - 处理方法：强制中止支付，退还所有金额，将所有状态reset为初始状态
    
#### 扫描购票简介用例

 1. Use case：购票
    - Actors：客户
    - Type：Primary
    -  Description：用户登录进入APP，选择电影信息后，进行一系列的 订单操作。
 2. Use case：查看信息
    - Actors：客户
    -  Type：Primary
    - Description：用户查看已支付/待支付的购票信息
 3. Use case：管理订单
    - Actors：电影院
    - Type：Primary
    - Description：电影院接到购票信息后，更新该场次电影座位信息，并存储用户提供的基本信息

#### 用户用例

![image](https://github.com/ABTicket/Initial-design-and-planning/blob/master/image/User%20use%20case.png)

#### 总体用例
![image](https://github.com/ABTicket/Initial-design-and-planning/blob/master/image/use%20case.png)
 
#### Domain model
 
![image](https://github.com/ABTicket/Initial-design-and-planning/blob/master/image/domain%20model.png) 

#### state model

![image](https://github.com/ABTicket/Initial-design-and-planning/blob/master/image/state%20model.png)

#### system sequence diagram
**15331219 lyq:**
![image](https://github.com/ABTicket/Dashboard/blob/master/image/sequence_model_15331219.png)
 
