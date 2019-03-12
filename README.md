# M6：[数据网关](https://github.com/OS-Q/M6) 

[![sites](OS-Q/OS-Q.png)](http：//www.OS-Q.com)

#### 归属通信体系：[Q2](https://github.com/OS-Q/Q2)

#### 关于系统架构：[OS-Q](https://github.com/OS-Q/OS-Q)

## [节点描述](https://github.com/OS-Q/M6/wiki) 

M6数据网关节点，用于引导相应数据流到指定位置，保证边缘侧数据传送

### [共用资源](https://github.com/OS-Q/M6/wiki/)  


---

- 边缘设备命名规则：体系 Q:[1,4] -> 节点 M:[1,12] -> 平台 W:[1,52] -> 设备 D:[1,365]

- naming patterns：system Q[1,4] -> node M[1,12] -> platform W[1,52] -> device D[1,365]

## [包含平台](https//github.com/OS-Q/M6/wiki) 

#### W23：[实时连接](https://github.com/OS-Q/W23)

用于守候下层低频数据，对上维护通信设备状态

#### W24：[数据缓存](https://github.com/OS-Q/W24)

上下层间数据缓存节点，完成边缘侧的数据分发

#### W25：[安全强化](https://github.com/OS-Q/W25)

逐级强化数据安全机制，保证数据安全最高能效

#### W26：[应急保障](https://github.com/OS-Q/W26)

用于提供在特殊或紧急状态下的通信需求和保障

## [同级节点](https://github.com/OS-Q/Q2/wiki/)

#### M4：[桥接管道](https://github.com/OS-Q/M4)

作为上下层级设备控制的通信管道

#### M5：[无线终端](https://github.com/OS-Q/M5)

集成无线通信和边缘控制终端设备

#### -> M6：[数据网关](https://github.com/OS-Q/M6)

数据中转节点，数据的汇集和处理

---

####  © qitas@qitas.cn
###  [OS-Q redefined Operation System](http://www.OS-Q.com)
####  @ 2019-3-12