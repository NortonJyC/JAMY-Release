# JAMY Releases

此目录存放公开发布所需的产品资料，不存放 JAMY 的应用源码。

## 发布方式

每次正式发布时，请在本仓库的 **Releases** 页面创建版本，并将安装包作为 Release 附件上传，而不是提交到 Git 历史中。

建议每个版本包含：

- Windows 安装程序
- 版本号与发布日期
- 用户可读的更新说明
- 已知问题（如有）
- 安装包 SHA-256 校验值（建议）

## 用户使用说明

- 根目录 `README.md`：产品展示、功能一览、完整格式清单与主要使用上限。
- [`LIMITS.md`](LIMITS.md)：3.1.13 的容量建议、模型/图片/音视频与 AI 边界、导入批次与备份限制。
- [`3.1.13.md`](3.1.13.md)：本次免费测试发布的版本说明、安装提示与校验信息。
- [`manual/3.1.13/`](manual/3.1.13/README.md)：29 章完整文字手册、章节索引及离线 HTML 阅读版。
- 2026-10-30 更新包已内嵌离线手册；同一发行页还提供第三方源码/构建配方/许可 ZIP，普通用户无需安装该附件。
- 容量建议与程序保护上限分别标注；图片分析、搜索准备和普通媒体预览分别说明。

## Included Assets

- `assets/jamy-mark-black.png`、`assets/jamy-mark-red.png`：软件界面品牌标识，分别适配浅色与深色背景。
- `assets/jamy-studio-library.png`：3.1.13 亮色主题下的实际素材库与 GLB 详情。
- `assets/jamy-studio-model.png`、`assets/jamy-studio-ai.png`：3.1.13 模型材质与 AI 任务确认界面实拍。
- `assets/jamy-download.svg`、`assets/jamy-website.svg`：README 导航按钮。
- `assets/jamy-local-workflow.svg`：本地素材工作流示意。
- `assets/CREDITS.md`：截图说明、样例素材作者与许可。
- `CHANGELOG.md`：公开版本更新记录。
