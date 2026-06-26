# 花花 C4D 插件 v1.2.6

## 发布内容

- 修复真实导入中文贴图仍提示缺失的问题
- 增加中文文件名 Unicode NFC / NFD 规范化匹配
- 增加 URL 编码贴图路径兼容
- 显式 texturePath 找不到时不再静默退回旧规则，避免错贴
- 增强缺失贴图日志，列出真实查找路径和候选文件
- 支持 fill / stroke 子结构中的贴图路径读取
- 保持授权、machineId、检查更新、CDK 兑换等逻辑不变

## Windows 安装包

下载并运行 `HuahuaC4DPluginSetup-v1.2.6.exe`。

SHA256 见 `checksums.txt`。
