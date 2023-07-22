# 蓄电池
![无限能量！](block:createaddition:modular_accumulator)

串口模块可以与蓄电池交互，回报里面存储的能量值。此协议不支持写入操作。

读取操作会返回蓄电池内存储的能量值，**单位为kFE**。读取超过32768kFE的能量值时，其行为由供应方指定的特定实现决定。