# THUAI3.0 选手接口
THUAI3.0 原电子系第21届队式程序设计大赛

## 设计思路（参考）
目标框架：C++11及以上

多线程设计：
- 通信线程：监听代理Agent推送的信息更新与发送信息
- AI线程：死循环

重点：
- Protobuf的使用
- 资源的互斥访问（避免选手使用数据的同时通信线程修改它）

难点（饼）：
- 设计良好的debug接口

## 开发组成员
（自己加）