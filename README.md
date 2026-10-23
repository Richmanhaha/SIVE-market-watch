# SIVE 行情终端

适用于安卓手机浏览器的轻量 PWA 行情看板，使用第三方图表与行情入口。

## 数据说明
- 本应用不会生成或猜测股票价格。
- TradingView 图表标识尝试使用 `OMXSTO:SIVE`；备用报价入口使用 Yahoo Finance 的 `SIVE.ST`。
- 是否实时或延迟，以数据提供方实际标注为准。免费行情可能延迟、限流或调整。
- 本应用未接入可验证的实时行情 API，因此不把第三方图表刷新频率等同于交易所实时行情。

## 安卓安装
部署完成后，用 Android Chrome 打开 GitHub Pages 地址，点菜单 ⋮，选择“添加到主屏幕”或“安装应用”。

## GitHub Pages
仓库包含 GitHub Actions 工作流，推送到 `main` 后自动构建并部署静态网站。首次运行后请在仓库 Settings → Pages 确认 Build and deployment 来源为 GitHub Actions。
