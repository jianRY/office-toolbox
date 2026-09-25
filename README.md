# 办公工具箱

四个独立工具合到一个窗口，左侧图标栏切换。

## 模块

| 图标 | 工具 | 原项目 |
|------|------|--------|
| ⚖ | 法院文书下载器 | jianRY/court-doc-downloader |
| ▣ | 发票二维码识别下载工具 | jianRY/invoice-qr-tool |
| 📄 | 发票识别汇总工具 | jianRY/invoice-ocr-tool |
| 📊 | 图片表格转 Excel 助手 | jianRY/img2excel |

## 下载

请到 [Releases](https://github.com/jianRY/office-toolbox/releases) 页下载：
- **单文件版**：一个 exe 即可，体积 142MB，启动慢一点（首次约 25 秒解压）
- **目录版**：zip 解压后用里面 OfficeToolbox.exe，启动快（3~5 秒），适合常用
- **安装版**：双击安装到 `C:\Program Files\办公工具箱`，自动创建开始菜单快捷方式和注册表卸载项

## 自动更新

启动器顶栏「检查更新」按钮走 GitHub API 检测最新版。
仓库根目录的 `update.json` 是回退通道。

## 签名

所有 exe 已用 `jianRY` 自签名证书签名（CN=jianRY,O=jianRY）。首次运行如遇 SmartScreen
提示「未知发布者」，右键 exe → 属性 → 勾选「解除锁定」或「仍要运行」即可。