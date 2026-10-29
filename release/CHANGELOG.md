# JAMY Changelog

## 3.1.13 — 2026-10-30 更新构建

- 版本号保持 3.1.13，替换 2026-10-29 r3 下载包。
- 首次页与启动页明确免费测试定位，自有说明精简为“免费测试说明”，保留真实隐私数据流和必要第三方许可。
- 内嵌 29 章离线使用手册，支持目录、正文搜索、章节定位与前后章。
- 同一发行页补充第三方源码、构建配方与许可 ZIP，普通用户无需安装该附件。

## 3.1.13 — 2026-10-29

- 手动备份独立保留，补充保存位置、清理规则和删除入口。
- 修复 AI 搜索相关度排序，增加 Beta 标识和清晰的任务操作引导。
- 优化 3D 预览切换和详情栏定位，重复上传材质贴图时复用已有资产。
- 改善瀑布流排列，文件夹封面支持更多已生成缩略图的资产。
- 快捷窗口贴边后支持上下移动，完善 Zen 浏览器图片拖入兼容。
- Retain manual backups independently, with clearer storage, cleanup and deletion controls.
- Fix AI relevance ordering and add Beta labels with clearer task guidance.
- Improve 3D preview transitions and detail-panel positioning, and reuse existing assets for repeated texture uploads.
- Improve waterfall layout and allow more generated asset thumbnails as folder covers.
- Move the docked Quick strip vertically and improve image drag compatibility with Zen.

## 3.1.12 — 2026-10-27

- 首次启动可离线阅读并确认使用许可与隐私说明，拒绝后正常退出；本测试包正文仍明确标为发布前候选。
- 在“关于软件”中查看、切换和复制说明正文及第三方许可材料。
- 自定义 AI 服务与网页导入分别说明数据用途并保存明确授权；未应用的 API 草稿不再阻碍本地组件准备。
- 反馈入口显示固定邮箱，复制或导出诊断仍只保存到本机；启动署名统一为 NortonJY。
- Read and acknowledge the offline license and privacy information before first use, or decline and exit. This test package clearly labels the documents as pre-release candidates.
- View, switch and copy documents and third-party notices from About.
- Keep explicit consent for custom AI services and web imports separate; unapplied API drafts no longer block local component preparation.
- Show the fixed support email and keep copied or exported diagnostics local. Use NortonJY consistently in the startup credit.

## 3.1.11 — 2026-10-26

- 缩略图因可用内存不足而暂缓时，明确显示原因及恢复说明，保留原有安全检查与重试入口。
- 任务入口区分“等待”和“进行中”，可直接看到等待内存或预览进程恢复的原因。
- 已停止的预览任务明确提示可重试，不再误报为等待自动恢复。
- Explain when thumbnails are waiting for available memory, preserving existing safety checks and retry controls.
- Distinguish waiting tasks from active processing and show the memory or preview recovery reason.
- Show stopped previews as retryable instead of promising automatic recovery.

## 3.1.10 — 2026-10-26

- 修复部分 FBX 动作因冗余采样无法预览的问题，保留原动作；准备超时会提示稍后重试。
- 按 FBX 声明的坐标方向显示模型，并更新旧方向的缩略图。
- 新增“简化骨骼”及问号说明，可隐藏已识别的辅助连线，随时恢复完整显示，不改变原动画。
- Fix preview failures caused by redundant FBX animation samples while preserving motion; preparation timeouts now suggest retrying later.
- Respect declared FBX coordinates and regenerate thumbnails that used the previous orientation.
- Add “Simplify skeleton” with a help button to hide recognized helper lines and restore the full display without changing the animation.

## 3.1.9 — 2026-10-26

- 优化模型预览布局，调整亮度与光照时可同时查看模型，兼顾小窗口操作。
- 为本地 AI 与自定义 API 整理内部步骤，清楚区分测试通过、失败、等待与尚未开始。
- 优化手机连接、模型预览和文件夹导入的说明层级，突出当前状态与可用操作。

## 3.1.8 — 2026-10-25

- 补充本地 AI 准备、分析速度与自定义服务的使用说明，任务等待原因更加清楚。
- 区分 AI 搜索、缩略图、高清图片和模型预览的处理限制，并提供对应操作建议。
- 补充文件夹导入和手机传输的范围说明，完善中英文失败提示。
- 优化预览提示在小窗口中的滚动，保留原有处理上限和操作流程。

## 3.1.7 — 2026-10-25

- 复制导入 GLTF 时一并保存其引用的模型数据和贴图，保留相对目录，避免主文件已收录却无法完整预览。
- GLTF 重复检查覆盖整组文件；模型相同但贴图或数据不同的资产可以分别收录。
- 重新导入缺失的普通图片时，可选择补回原资产，保留原有标签、评分和项目关联。
- 加强模型链接的依赖路径检查，以及导入失败、取消和重启后的恢复处理。
- 没有收录来源记录的资产会明确显示暂无记录。

## 3.1.6 — 2026-10-23

- 重新整理详情界面：名称与格式置顶，紧凑色板保留完整导出，标签、评分、AI 解读和来源分区展示；保留原有预览与操作。
- 修复后台色板更新时自定义标签可能无法保存的问题，连续添加与删除保持操作顺序。
- 首次打开先选择资源库位置，取消选择不会自动创建；已有资源库继续沿用保存的位置。
- 修复尚未打开任何资源库时，路径身份不可用导致退出被阻止的问题；已开始的保存与备份仍须确认完成。
- 导入文件夹时切换页面不会中断任务，完成后保留正在浏览的位置。
- 3D 动画默认支持空格播放与暂停，可在设置中改键或关闭；低内存等待原因更清楚。
- 新增原生自定义安装界面，分步显示准备、授权和安装结果。升级支持请求采用新退出协议的目标程序正常退出；旧版本需手动关闭，无法确认退出时停止安装。

## 3.1.5 — 2026-10-22

- 统一设置内恢复备份、清除诊断日志的危险描边，明确区分禁用状态并保留原确认流程。
- 本地 AI 准备状态改为短标签与独立说明；当前文件进度的百分比和字节分层展示，保留下载后校验提示。

## 3.1.4 — 2026-10-22

- 统一七页设置的导航、卡片、按钮与字体，优化五种主题和窄窗口显示。
- 本地 AI 状态与当前文件进度更清楚，保留原有准备、检查、任务与高级配置操作。
- 资源库路径更易阅读；备份、恢复与诊断分组展示，保留完整范围提示和确认流程。

## 3.1.3 — 2026-10-22

- 自定义 API 图片分析默认同时处理 2 张，可调至 4 张；遇到服务限流自动降速。
- 暂停、继续和停止统一进入资产任务，诊断可查看图片处理、请求和保存各阶段耗时。
- 优化后台整理效率，避免尚未打开的 AI 标签筛选影响颜色信息保存。

## 3.1.2 — 2026-10-22

- 自定义 API 图片分析默认同时处理 2 张，可设置 1–4 张；自动导入与批量任务共用上限，本地 AI 仍串行并保留内存门槛。
- 暂停、停止后不再发送新请求，在途结果正常保存；调并发只影响后续调度，重启不重复调用结果未知的任务。
- 服务返回限流时自动降速、等待并逐级恢复；长时间或持续拒绝时明确暂停，需检查服务后重新应用设置。
- 诊断记录调度准备、图片处理、网络响应和保存耗时；不记录图片、密钥或素材路径。

## 3.1.1 — 2026-10-22

### 中文
- AI 分析、加入项目及其他长窗口改为正文滚动，标题与关闭按钮保持可见。
- AI 批量分析完成后保留当前素材列表、选择和详情，减少整页闪动。
- 优化已支持千问图片模型的请求设置与连接复用；补充脱敏请求耗时，便于定位网络或服务等待。
- 大型本地组件下载支持最多两路分段，保留暂停续传及完整文件校验；临时下载链接过期可有限重取。
- 下载仍使用受信任的官方源，实际速度与 AI 响应时间取决于网络和服务；未加入未经验证的镜像。

### English
- Long analysis, project assignment and other dialogs now scroll their content while keeping close controls visible.
- Batch analysis preserves the visible asset cards, selection and details instead of clearing the page.
- Improved supported Qwen vision request settings and connection reuse, with content-free request timings for diagnosis.
- Large local components use up to two bounded download ranges, retaining pause/resume and whole-file verification, with bounded refresh of expired download links.
- Downloads still use trusted official sources. Actual speed and AI latency depend on the network and provider; no unverified mirrors were added.

## 3.1.0 — 2026-10-22

### 中文
- 正式整合本地 AI 与自定义 API：批量图片分析、暂停续跑，以及可直接搜索和筛选的 AI 标签。
- 同一电脑、同一用户更换版本自动复用已有本地组件；修复透明白色 PNG 分析前的背景处理。
- AI 搜索支持相近结果提示；分析、搜索准备与导入等进度统一到资产任务入口，完成后短暂提示。
- 改善详情面板标签布局、保存后的状态保持，以及打开详情时所选资产的定位。
- 合入模型、骨骼和音频预览修复；大文件保护仍然保留。
- 旧资源库首次打开前自动创建升级备份。升级后的库不能直接用旧版打开；降级请使用升级前备份。
- 云端内置服务尚未开放；自定义 API 按服务商计费。AI 识别与搜索结果仍可能不准确。

### English
- Local AI and custom APIs are now integrated: batch image analysis, pause/resume, and searchable, filterable AI tags.
- Existing local components are reused for the same computer and user. Transparent white PNGs now receive a contrasting analysis background.
- AI search can show nearby matches. Analysis, search preparation and imports share the asset task center with brief completion notices.
- Improved detail tags, state after saving, and selected-asset positioning when details open.
- Includes model, skeleton and audio preview fixes while preserving large-file safeguards.
- Existing libraries receive a backup before their first schema upgrade. Older versions cannot open upgraded libraries directly; use a pre-upgrade backup to downgrade.
- The built-in cloud service is not available yet. Custom API usage is billed by its provider; AI recognition and search can still be inaccurate.

## 3.0.13 — 2026-10-22

- 音频缩略图和预览改为整段波形，支持进度定位。
- 修复骨骼动画预览，新增模型与骨骼显示切换。
- 优化动画跟随、小窗旋转与大窗观察，开放常用预览默认设置。

## 3.0.12 — 2026-10-21

- 修复后台整理期间无法保存图片评分的问题。
- 右键菜单新增“移入文件夹”，支持单个和批量整理。
- 音频预览新增实时波形，修复时长显示与进度跳转。
- 更新版本说明，未开放的提示词解析选项置灰。

## 3.0.11 — 2026-10-21

- 后台任务统一到页脚，减少进度面板对浏览的干扰。
- 优化宽幅图片排列和拖入资产的分类位置。
- 修复音频再次播放无响应的问题。

## 3.0.10 — 2026-10-21

- 支持 16 位灰度与 RGB PSD 预览。
- 修复删除目录后的同步提示及重新导入问题。
- 改善收件箱范围切换、导入定位和浅色主题可读性。

## 3.0.9 — 2026-10-21

- 恢复 PSD 预览和网页图片拖入，改善旧库模型预览。
- 优化启动主题、透明图片背景与瀑布流布局。
- 改善目录同步、文件夹封面和预览详情操作。

## 3.0.8 — 2026-10-21

- 优化缩略图恢复处理，减少等待和界面停顿。
- 改善后台处理期间的操作响应。

## 3.0.7 — 2026-10-20

- 改善任务恢复及详情面板状态保持。
- 修复历史流程中的稳定性问题。

## 3.0.6 — 2026-10-20

- 优化文件夹选择、封面显示和菜单布局。
- 完善透明材质预览与卸载数据保留选项。
- 精简设置入口，改善英文界面排版。

## 3.0.5 — 2026-10-20

- 提升大库目录同步的响应速度。
- 修复“全部资产”的文件夹范围切换。

## 3.0.4 — 2026-10-20

- 完善目录自动与手动同步，保留标签和评分。
- 支持跟踪文件新增、修改、改名、移动与删除。

## 3.0.3 — 2026-10-20

- 恢复已有目录建库时的文件与子目录收录。
- 新增库内文件手动扫描，支持中断后继续。

## 3.0.2 — 2026-10-20

- 新用户默认使用白色主题，新增柔和绿与暖咖啡。
- 改善浅色主题和小窗口的显示效果。

## 3.0.1 — 2026-10-19

- 优化批量导入与手机传输。
- 大图预览支持相邻预加载、评分和标签整理。
- 自动收录 Imported 目录中的新增文件。

## 3.0.0 — 2026-10-15

- 支持 HDR/EXR 预览及模型材质、灯光设置保存。
- 整理资源库、备份和版本信息入口。

## [v2.5.1] - 2026-08-19

### 🚀 底层架构升级 (Core Architecture)
- **数据与程序物理分离**：全局解耦 `userData` 路径，支持通过 `--user-data-dir` CLI参数、`JAMY_DATA_DIR` 环境变量及 `jamy-data` 便携目录自定义数据落盘位置。
- **无损降级与灾难恢复**：`config.json` 与 `workspaces.json` 引入 Schema 版本控制，实现向后兼容的平滑升维与 `.bak` 断电热备机制，杜绝配置损坏死机。
- **系统环境快照记录**：全局日志（`jamy_sys.log`）自动跟随重定向至数据目录，并在首次记录时注入 OS内核、应用版本及 Electron/Node 环境标头。

### 🛠️ 性能与维稳修复 (Performance & Fixes)
- **修复 P0-B (大资源库严重卡顿/卡死)**：
  - [防抖] 阻断了 `AssetItemImage` 组件加载失败时释放状态锁引发的无限重试请求风暴。
  - [I/O] 消除了 `pathAuthority` 在并发拦截 `jamy://` 协议时对 `workspaces.json` 的密集同步读取与 `realpathSync` 抢占阻塞。
  - [并发] 引入 `useAssetLibrary` 尺寸提取批处理合并（Batching）与并发限流机制，平息海量资产导入时的 React 状态级联震荡。
  - [DOM] 重构瀑布流及子文件夹视图渲染引擎，新增基于可见边界的渐进式分块挂载（Chunking），彻底熔断初次载入时的万级 DOM 节点内存爆炸。
- **修复 P0-A (资产 403 阻断)**：修复 Windows 环境下底层自定义协议路径解析丢失盘符冒号引发的非法越权拦截。

## [2.5.0] - 2026-08-14
### Added
- [底层机制] 引入规范化的语义化版本号 (Semantic Versioning)
- [底层机制] 建立标准的更新日志 (Changelog) 本地与 UI 渲染链路
- [重构] 彻底移除 UI 层硬编码版本号，全面对接主进程 IPC 动态读取
