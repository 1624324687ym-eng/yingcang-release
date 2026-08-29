# yingcang-release

影舱（Yunmu AI Theater）的发布专用仓库。

本仓库只承载版本发布资产，不含任何源代码：

- 每个版本的 GitHub Release 附带更新清单 `update.json`，声明最新版本号、夸克网盘下载链接、发布说明、发布时间与安装包 SHA-256。
- 应用通过固定地址读取最新清单：`https://github.com/1624324687ym-eng/yingcang-release/releases/latest/download/update.json`（GitHub 自动重定向到最新 Release 中的同名资产）。
- 安装包通过更新清单中声明的夸克网盘链接分发，本仓库不存放安装包。

应用源码仓库为私有仓库，不在此公开。
