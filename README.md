# fingov-release

fin-datagov 桌面端（Windows）公开发布/下载仓。

- 源码仓：`wisfern/fingov`（私有），本仓 Releases 由 CI 自动发布
- 每个版本提供两种产物：
  - `fin-datagov_<版本>_x64-setup.exe`：NSIS 安装包，下载后直接安装
  - `fin-datagov_<版本>_x64-portable.zip`：绿色免安装版，解压即用（需系统已有 WebView2 运行时）
- 免认证直下：`https://github.com/wisfern/fingov-release/releases/download/v<版本>/<文件名>`

> 说明：GitHub 会为每个 tag 自动生成 Source code (zip/tar.gz) 压缩包，该包仅含本仓
> README，不含应用源码；应用源码在私有仓，不会通过本仓泄露。
