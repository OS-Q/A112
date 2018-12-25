# M6：[数据网关](https://github.com/OS-Q/M6) 

[![sites](OS-Q/OS-Q.png)](http：//www.OS-Q.com)

#### 归属通信体系：[Q2](https://github.com/OS-Q/Q2)

#### 关于系统架构：[OS-Q](https://github.com/OS-Q/OS-Q)

## [节点描述](https://github.com/OS-Q/M6/wiki) 

M6数据网关节点，用于引导相应数据流到指定位置，保证边缘侧数据传送

### [共用资源](https://github.com/OS-Q/M6/wiki/)  

#### [管理接口](M7/)

M6节点和M7节点协议

#### [计算接口](M8/)

M6节点和M8节点协议

---

- 边缘设备命名规则：体系 Q:[1,4] -> 节点 M:[1,12] -> 平台 W:[1,52] -> 设备 D:[1,365]

- naming patterns：system Q[1,4] -> node M[1,12] -> platform W[1,52] -> device D[1,365]

## [包含平台](https//github.com/OS-Q/M6/wiki) 

#### W23：[实时网关](https://github.com/OS-Q/W23)

用于守候低频数据上报，维护低频设备通信管道

#### W24：[扩展网关](https://github.com/OS-Q/W24)

具有可临时定义的网关，可以根据需要切换身份

#### W25：[安全网关](https://github.com/OS-Q/W25)

用于实现对数据的加密，保证数据向上的私密性

#### W26：[分发网关](https://github.com/OS-Q/W26)

用于完成数据资源储备，保证通用数据及时下发

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
####  @ 2018-12-25