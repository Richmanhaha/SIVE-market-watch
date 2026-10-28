# 全球行情通 Android 测试版

这是一个面向个人使用的 Android 原型，采用原生 Android WebView 外壳加载本地界面。

## 当前功能
- 美股、港股、A 股、贵金属、原油、加密货币分类
- 搜索资产
- 本地自选列表
- TradingView 图表入口与常见周期
- 深色简洁界面

## 重要数据说明
本版本没有独立的行情 API，也不伪造价格。行情图通过 TradingView 的嵌入页面加载；具体标的覆盖、地区可用性、实时/延迟状态和商业使用授权以服务提供方为准。不要把本原型用于交易决策。

## 构建 APK
仓库的 GitHub Actions 工作流会在本目录变更后自动构建 debug APK，并将测试包作为 workflow artifact 和预发布 release 上传。Debug APK 适合个人测试，不适合正式公开发行。
