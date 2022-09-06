
![OpenRUM Logo](resources/images/logo/open_rum_vertical_logo.png)

- [OpenRUM概述](#openrum概述)
  - [Session](overview/session.md)
  - [Events](overview/events.md)
- [Protocol](https://github.com/RealUserMonitoring/OpenRUM-proto)
- [Specification](https://github.com/RealUserMonitoring/OpenRUM-specification)

# OpenRUM概述

## 介绍

现在互联网时代，追求极致的用户体验变得尤为重要，极致的用户体验可以为其迎来更好的口碑、用户和交易，可创造更大的商业价值。

<br>

*嵌入式真实用户监控产品弊端：*

**1.客户的配合繁琐；**

在当前应用的混开模式或外包模式，集成SDK获取会给用户带来很多非必要麻烦，尤其在一些金融类行业，无法让客户充分配合或者造成和客户的应用代码耦合；

<br>

**2.对于RUM侧数据的清洗和计算的专业度不足；**

针对RUM侧 ，想达到用户体验数据合理性，就要针对很多指标做相关算法，在清洗计算上如果不标准造成数据的误判，产品上适得其反；

<br>

**3.对于RUM侧数据的可视化专业度不足；**

OpenRUM为真实用户监控提供了一种标准的、中立的指标协议框架。基于此，对于开发者使用的形形色色的监控系统，无需进行额外的协议设计与RUM侧指标算法的了解，只需对照协议进行数据的发送，便可针对真实用户的体验做出可洞察性观测。
