# 花花智能建模-C4D端 v1.2.17

## 更新内容

- 修复“选择隐藏对象”扫描层级时偶发 NoneType.GetNext 报错。
- 优化隐藏对象递归遍历，先保存 next_child / next_root 再继续扫描。
- scan_hidden 增加 None 保护，空文档或复杂层级下不再报错。
- 隐藏对象判断规则保持不变。
- 保持模型库、AI JSON 导入、smart stack、stroke ring 合并、贴图路径、授权、machineId、检查更新、CDK 兑换逻辑不变。

## 安装包

- Windows: HuahuaC4DPluginSetup-v1.2.17.exe
