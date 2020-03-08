# javaparser-note

事因给安全白盒系统强化功能，由于现阶段只能通过字符串模式匹配，只能简单的匹配出污点分析的sink, 但对于数据的来源并不能确认，所以需要从代码中提取相应的调用链路，来确定source是否为外部数据。对于不需要验证调用链的特征代码，通过正则去匹配也容易出现坑，所以学习一些用javaparser把源代码转换成AST(Abstract Syntax Tree)去处理。还有就是先挖个坑，自己来填，免的两分钟的热情。还有就是谁看到了可以一起交流一下，要不也太寂寞了。然后还有就没有然后了，想起来再说。

## 目录
[day_1 : 把代码抽象成AST](./day_1.md)
