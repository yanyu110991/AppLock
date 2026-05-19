# 停一下

一款面向个人自控和习惯管理的 iPhone App。

第一版目标是通过 iOS Screen Time 相关能力限制指定 App 的使用时长，例如微信：

- 使用到 10 分钟时提醒。
- 使用到 12 分钟时系统级拦截。
- 支持硬核模式，避免当下冲动时轻易关闭规则。
- 拦截后引导打开微信读书，把刷视频替换成阅读。

当前仓库先沉淀产品原型和技术架构，后续会逐步创建 SwiftUI 工程。

## 文档

- [MVP 交互原型文档](docs/mvp-interaction-prototype.md)
- [技术架构文档](docs/technical-architecture.md)

## 技术方向

- Swift
- SwiftUI
- 组件化架构
- 组件内部 MVI
- FamilyControls
- DeviceActivity
- ManagedSettings
- ManagedSettingsUI
- App Groups

