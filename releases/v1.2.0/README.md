# 花花广告设计 C4D 插件 v1.2.0

本版本新增公共 machineId，用于适配后台单账号单电脑授权规则。

- AI 面板和 C4D 插件可共用同一个 machineId
- register-device / check-license / heartbeat 上报 machineId
- 新增 machine_replaced 处理
- session_replaced / machine_replaced 不进入离线宽限
- 保留 C4D 插件自身 deviceId
- 授权弹窗显示电脑标识前 8 位
- 设备数量文案调整为设备记录

当前发布包为手动安装 zip，解压后将 `HuahuaC4DPlugin` 文件夹放入 Cinema 4D plugins 目录。
