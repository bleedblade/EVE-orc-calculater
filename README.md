# EVE-ores-calculater
基于Django的静态lpsolve使用，能够通过矿物计算出所需的矿石并结合jita buy市场给出花费最低的方案。

使用Redis缓存获取到的价格数据。

需要：Python3(.7),lpsolve,Django,Redis,django-redis

目前支持全部15种标准矿石。
默认生产环境为00。（高安低安的话建筑插加成和00不一致）

有一定小误差。

输入参与计算的矿石，拥有的矿石数，所需矿物和所需旗舰组件数量，以及精炼率、建筑加成、建筑插加成、组件图纸材料效率。
输出所需高密度矿石价格、数量，化矿得到的矿物和跟所需矿物相比的差。


都玩EVE了要什么CSS样式（滑稽）
