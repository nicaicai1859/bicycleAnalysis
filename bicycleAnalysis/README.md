#### 页面展示

周围几公里单车查询页面：

![附近单车查询](https://cdn.jsdelivr.net/gh/trayfour34/Picture_Bed@master/20201230005214.jpg) 

![附近单车查询](https://cdn.jsdelivr.net/gh/trayfour34/Picture_Bed@master/20201230005306.jpg) 

![附近单车查询](https://cdn.jsdelivr.net/gh/trayfour34/Picture_Bed@master/20201230005321.jpg) 

![附近单车查询](https://cdn.jsdelivr.net/gh/trayfour34/Picture_Bed@master/20201230005334.jpg) 

**功能详解：**

**（1）输入某个地点的经纬度，以及需要查询的半径范围，反馈出周围所有的单车点。**

**（2）对单车点进行可视化，闲置状态为红色圆点，正在骑行状态为绿色圆点。只有点击闲置状态下的单车才有单车信息窗弹出。**

**（3）倘若用户正在骑行一辆单车，则无法骑行其他单车，并显示**

![错误处理](https://cdn.jsdelivr.net/gh/trayfour34/Picture_Bed@master/20201230005422.jpg) 



人员单车流动页面（显示某个时段某地度变化）：

![人员流动](https://cdn.jsdelivr.net/gh/trayfour34/Picture_Bed@master/20201230005456.jpg) 

![人员流动](https://cdn.jsdelivr.net/gh/trayfour34/Picture_Bed@master/20201230005505.jpg) 

**功能详解：输入需要查询区域的东北角经纬度和西南角经纬度，和需要查询的时间段，得到在特定时间段内，自行车出入区域的动画。**



密度变化（查询不同商业圈的密度变化对比）：

![密度变化](https://cdn.jsdelivr.net/gh/trayfour34/Picture_Bed@master/20201230005530.jpg) 

![密度变化](https://cdn.jsdelivr.net/gh/trayfour34/Picture_Bed@master/20201230005608.jpg)                                                                        ![密度变化](https://cdn.jsdelivr.net/gh/trayfour34/Picture_Bed@master/20201230005710.png)

**功能详解：输入特定的时间段，返回数据库内所有的单车数据，前端进行聚类和可视化，通过放大缩小地图，和地图数据可视化来实时观察某个地区单车数量的大小和变化。**



一天中每个时间段订单数汇总和图标统计：

![每天订单汇总](https://cdn.jsdelivr.net/gh/trayfour34/Picture_Bed@master/20201230010109.jpg) 

![每天订单汇总](https://cdn.jsdelivr.net/gh/trayfour34/Picture_Bed@master/20201230010123.jpg) 

**功能详解：**

**（1）** **输入相应区域的东北角经纬度和西南角经纬度，得出一天中24小时每个时段的订单数据。**

**（2）** **拖动下方的滚动条，可以更加细致的查询具体时段（如8:00-16:00的订单变化量）**

 

 

 **一天中每个时间段订单数汇总和图标统计**：

![时间段订单汇总](https://cdn.jsdelivr.net/gh/trayfour34/Picture_Bed@master/20201230010308.jpg) 

![时间段订单汇总](https://cdn.jsdelivr.net/gh/trayfour34/Picture_Bed@master/20201230010322.jpg) 

**功能详解：**

**（1）输入相应区域的东北角经纬度和西南角经纬度，得出八月31天中每天的订单总量和变化趋势。**

**（2）拖动下方的滚动条，可以更加细致的查询具体时段（如8.1-8.5的订单变化量）**

 

列表管理：

**用户页面（共17765条数据，50条/页）**

![用户管理](https://cdn.jsdelivr.net/gh/trayfour34/Picture_Bed@master/20201230010518.jpg) 

![用户管理](https://cdn.jsdelivr.net/gh/trayfour34/Picture_Bed@master/20201230010539.jpg) 

**添加新用户**

![添加用户](https://cdn.jsdelivr.net/gh/trayfour34/Picture_Bed@master/20201230010730.jpg) 

**编辑修改已有用户信息**

![修改信息](https://cdn.jsdelivr.net/gh/trayfour34/Picture_Bed@master/20201230010717.jpg) 

**修改用户类别（管理员or普通用户）**

![修改权限](https://cdn.jsdelivr.net/gh/trayfour34/Picture_Bed@master/20201230010703.jpg) 

**模糊搜索（提供对各种特定属性的选择来进行模糊搜索）**

![模糊搜索](https://cdn.jsdelivr.net/gh/trayfour34/Picture_Bed@master/20201230010653.jpg) 

**功能详解：**

**（1）列表有 用户ID，用户名，注册时间，电话，邮箱，余额 共六个属性。**

**（2）可进行用户列表增，删，改，查，导出的操作。**
