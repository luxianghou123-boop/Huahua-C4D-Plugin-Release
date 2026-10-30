# 花花智能建模-C4D端 v1.2.24

## 更新内容

- 新增可编辑的多段程序化楼梯，支持平台、左右转向和折返；新增楼段继承上一段参数。
- 楼梯支持精细扶手、踏面饰板、可选灯带、左右边带及独立材质。
- 每段楼梯和平台可独立设置墙面、窗户及底部造型。
- 新增智能门窗，提供 13 种预设及对应预览图，可按选中对象尺寸生成。
- 支持双扇/四扇推拉窗、带上亮窗、普通木门、消防门及单扇/双扇玻璃门。
- 普通木门支持可调整尺寸、位置的玻璃小窗。
- 优化门窗框体、玻璃和五金连接细节。
- 保持模型库、AI JSON 导入、授权、machineId、检查更新和 CDK 兑换逻辑不变。

## Windows 安装

关闭 Cinema 4D，运行 `HuahuaC4DPlugin-v1.2.24.exe`，在原有 Inno Setup 安装向导中选择检测到的 Cinema 4D 版本。
安装目标为所选 Cinema 4D 目录下的 `plugins\HuahuaC4DPlugin`。安装完成后重启 C4D。

安装包包含 `plugin_main.pyp`、`CHANGELOG.md` 和 `res/opening_previews/` 下的 13 张预览图。
不包含本地配置、授权 token、machine_id.json 或用户模型与贴图。
本附件为 Windows 安装程序，不是 macOS 安装包。

## 校验

文件大小：2,289,827 字节。

SHA256：`2b8de4ba9ed43cfc72d4f32b0bc23b7217a24e974f452716e79b65d0915e4be4`
