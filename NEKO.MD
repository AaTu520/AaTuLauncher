# 开发状态与验证边界

更新日期：2026-11-07。

- AaTu 的 Microsoft 应用尚未完成 Minecraft 服务接入审核。当前应用 ID 在获取 Minecraft 登录令牌时返回 `Invalid app registration`（HTTP 403）；完整正版登录和授权续期仍待接入审核后的真实账号验证。
- 登录截图使用 `DEMO-CODE` 演示界面，不代表 Minecraft 授权已通过。
- 当前交付已完成 Windows x64 构建、152 项自动测试及隔离原生界面检查。实际游戏兼容性、不同系统和大型实例的完整验收仍待补充。
- macOS、Linux 与 Windows ARM64 尚未完成原生构建及运行验证。
- CurseForge 独占且未被 Modrinth 识别的模组尚不支持更新检查。
