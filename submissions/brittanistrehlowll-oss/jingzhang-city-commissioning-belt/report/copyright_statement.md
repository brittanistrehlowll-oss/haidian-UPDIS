# 版权与使用说明

本投稿由AI agent在用户指令和人工审查下形成。核心文字、结构化JSON、GeoJSON、HTML与PDF为本次投稿生成或整理；公共事实和任务要求来自主办方公开仓库与政府公开来源。

为保证离线评审环境中的中文可读性，四个 HTML 页面统一引用 `visual/assets/fonts/jingzhang-cjk-subset.css`。该 CSS 内嵌一个根据四个最终 HTML 实际用字生成的 WOFF2 子集：投稿字体族名为 **JingZhang CJK Subset**，原字体族为 **Noto Sans SC**，源字体元数据版本为 `Version 2.04;241114210130;non-release`，变量轴为 `wght 100–900`。原字体版权元数据包含 `© 2014–2021 Adobe` 及 Reserved Font Name `Source`；本投稿使用独立字体族名，不使用该保留名称。字体来源及 SIL Open Font License 1.1 见 `https://github.com/notofonts/noto-cjk/blob/main/Sans/LICENSE`；完整许可文本随 CSS 人类可读头注保留。字体仅用于页面排版，不构成方案事实或设计证据。

最终核心图件包含AI辅助视觉生成，并经过数值白名单、术语、英文命名、`provisional_rough` 边界警示和版面QA清洗。视觉图中的技术文字、指标和边界以 `proposal.md`、`metrics.json`、GeoJSON和机器矩阵为正式证据，不以生成图像自行补全的文字或数字作为事实依据。

本次新增的四个媒体资产 `assets/media/cover.webp`、`assets/media/architecture-overview.webp`、`assets/media/architecture-technical-board.webp` 和 `assets/media/architecture-spatial-sequence.webp`，源自投稿人提供的四张 AI 辅助概念建筑可视化 PNG；其中第一张作为 Gallery 封面，后三张作为建筑设计与空间体验补充方案。处理中仅进行 RGB 转换、WebP 转码和等比例适配；3:2 技术展板保留完整画面，未引入外部图片、地图或实景底图。这四张图仅用于表达建筑母体、公共脊、空间序列、材料和场景氛围，不代表官方实景、官方边界、居民意见、测绘成果、施工图或指标证据。投稿人已确认这四项资产具有本次 PR、Gallery、Proposal Page 和 A3/A0 PDF 所需的公开提交权；原始生成工具/模型及第三方许可凭证未随附件提供的部分仍按“未随包记录”保留。

本轮新增的四个区域协同媒体资产 `assets/media/regional-coordination-01-location.png`、`assets/media/regional-coordination-02-interface.png`、`assets/media/regional-coordination-03-scenarios.png` 和 `assets/media/regional-coordination-04-loop.png`，源自投稿人提供的区域协同概念图，作为 `media_poster` 补充登记，与既有封面和三张建筑方案图并列使用，原有资产路径与内容保持不变。四张图分别表达区域区位关系、北京尺度空间承接、六类典型场景来源与四类本地承接界面、协同价值闭环；图内照片样式插图统一属于 **典型场景示意 / Representative Scenario Imagery**，用于表达场景类型、活动氛围与空间接口。图中方位关系、距离、边界、点位、箭头和输出关系属于规划示意，具体事实以正式公开资料、现场调研和专项校核为准；图件本身不作为已建立合作、资金安排、数据交换协议或政府实施机制的证明。投稿人已确认这四项资产具有本次 PR、Gallery、Proposal Page 和 A3/A0 PDF 所需的公开提交权；原始生成工具/模型与第三方素材的具体凭证未随包提供的部分仍按“未随包记录”保留。

用户提供的既有规划、市政、AIDC、控规与城市更新材料只用于抽象通用方法，不向公共仓库复制内部客户底图、非公开指标、受限图片、个人信息或其他不能确认再分发权利的内容。

所有空间、政策、运营和经济建议均为概念参考，不构成政府审定、工程可研、投资承诺、产权处置或实施时序结论。

## 逐图视觉资产来源登记（v0.12）

### 状态摘要

本表是投稿人侧的 provenance ledger，用于让评审逐项识别文件、用途、生产关系、输入/底图记录、处理过程、人物或个人数据边界、公开使用范围和权利状态。投稿人已明确确认：封面、05图、中英文核心图、3张建筑方案图和4张区域协同图均由投稿人控制或已获得公开提交权，可用于本次 PR、Gallery、Proposal Page 和 A3/A0 PDF；因此本表机器状态统一为 **`confirmed_by_participant`**。原始附件没有同时提供每张图的准确生成工具/模型、日期、提示词、底图凭证和第三方授权文件，这些具体 provenance 细节仍如实标注为未随包记录，不被本次权利确认扩展为额外的事实声明。

### 逐图清单

|Asset ID|文件|用途与性质|生成/输入/底图记录|处理与事实边界|人物/个人数据|公开提交权利状态|
|---|---|---|---|---|---|---|
|VIS-001|`assets/media/cover.webp`|Gallery 封面；AI/数字生成概念示意|投稿人提供的概念图；具体工具、模型、日期和提示词未随包提供；底图记录待确认|RGB/WebP 转码与封面适配；不作为结构化证据|未提供真实身份数据来源说明，待确认|`confirmed_by_participant`|
|VIS-002|`assets/figures/site-overview.png`|核心图01中文；总体城市设计概念图|任务材料、提交 `provisional_rough` 几何与方案提示；详细生成日志和底图凭证待确认|PNG 输出；空间和数字事实以 proposal、GeoJSON、metrics 为准|未提供真实身份数据来源说明，待确认|`confirmed_by_participant`|
|VIS-003|`assets/figures/site-overview.en.png`|核心图01英文；双语对应图|与 VIS-002 同源，英文标注；详细生成日志和底图凭证待确认|PNG 双语输出；空间和数字事实以 proposal、GeoJSON、metrics 为准|未提供真实身份数据来源说明，待确认|`confirmed_by_participant`|
|VIS-004|`assets/figures/land-use-structure.png`|核心图02中文；用地结构概念图|用地结构、提交几何与方案提示；详细生成日志和底图凭证待确认|PNG 输出；用地关系以 `land_use.geojson` 与 proposal 为准|未提供真实身份数据来源说明，待确认|`confirmed_by_participant`|
|VIS-005|`assets/figures/land-use-structure.en.png`|核心图02英文；双语对应图|与 VIS-004 同源，英文标注；详细生成日志和底图凭证待确认|PNG 双语输出；用地关系以 `land_use.geojson` 与 proposal 为准|未提供真实身份数据来源说明，待确认|`confirmed_by_participant`|
|VIS-006|`assets/figures/key-areas.png`|核心图03中文；三重点区概念图|重点区角色、提交几何与方案提示；详细生成日志和底图凭证待确认|PNG 输出；重点区几何与面积以 `key_areas.geojson` 为准|未提供真实身份数据来源说明，待确认|`confirmed_by_participant`|
|VIS-007|`assets/figures/key-areas.en.png`|核心图03英文；双语对应图|与 VIS-006 同源，英文标注；详细生成日志和底图凭证待确认|PNG 双语输出；重点区几何与面积以 `key_areas.geojson` 为准|未提供真实身份数据来源说明，待确认|`confirmed_by_participant`|
|VIS-008|`assets/figures/mobility-bluegreen.png`|核心图04中文；交通、蓝绿与市政接口概念图|慢行、蓝绿和市政接口方案材料；详细生成日志和底图凭证待确认|PNG 输出；路线与空间层以 roads/green_space GeoJSON 与 proposal 为准|未提供真实身份数据来源说明，待确认|`confirmed_by_participant`|
|VIS-009|`assets/figures/mobility-bluegreen.en.png`|核心图04英文；双语对应图|与 VIS-008 同源，英文标注；详细生成日志和底图凭证待确认|PNG 双语输出；路线与空间层以 GeoJSON 与 proposal 为准|未提供真实身份数据来源说明，待确认|`confirmed_by_participant`|
|VIS-010|`assets/figures/metrics-evidence.png`|核心图05中文；指标与证据图|`metrics.json`、方案证据清单和六类 Civic AI Overlay 规划控制；详细生成日志待确认|新版 PNG 已统一为六类规划控制；图中文字不替代结构化数字证据|未提供真实身份数据来源说明，待确认|`confirmed_by_participant`|
|VIS-011|`assets/figures/metrics-evidence.en.png`|核心图05英文；指标与证据图|与 VIS-010 同源，英文标注；详细生成日志待确认|新版 PNG 已统一为 six planning-control categories；图中文字不替代结构化数字证据|未提供真实身份数据来源说明，待确认|`confirmed_by_participant`|
|VIS-012|`assets/media/architecture-overview.webp`|建筑方案一；AI/数字生成概念示意|投稿人提供 PNG 与建筑空间提示；具体工具、模型、日期、底图和提示词待确认|RGB/WebP 转码与等比例适配；表达建筑界面和公共脊意向|未提供真实身份数据来源说明，待确认|`confirmed_by_participant`|
|VIS-013|`assets/media/architecture-technical-board.webp`|建筑方案二；AI/数字生成概念示意|投稿人提供 PNG 与建筑空间提示；具体工具、模型、日期、底图和提示词待确认|RGB/WebP 转码与等比例适配；表达建筑—公共空间一体化意向|未提供真实身份数据来源说明，待确认|`confirmed_by_participant`|
|VIS-014|`assets/media/architecture-spatial-sequence.webp`|建筑方案三；AI/数字生成概念示意|投稿人提供 PNG 与建筑空间提示；具体工具、模型、日期、底图和提示词待确认|RGB/WebP 转码与等比例适配；表达公共空间序列意向|未提供真实身份数据来源说明，待确认|`confirmed_by_participant`|
|VIS-015|`assets/media/regional-coordination-01-location.png`|区域协同图01；区位关系概念板|投稿人提供区域协同概念图；具体工具、模型、日期、底图和提示词待确认|PNG 输出；插图按“典型场景示意”使用，不作为现状实景证据|未提供真实身份数据来源说明，待确认|`confirmed_by_participant`|
|VIS-016|`assets/media/regional-coordination-02-interface.png`|区域协同图02；北京尺度空间承接概念板|投稿人提供区域协同概念图；具体工具、模型、日期、底图和提示词待确认|PNG 输出；插图按“典型场景示意”使用，不作为现状实景证据|未提供真实身份数据来源说明，待确认|`confirmed_by_participant`|
|VIS-017|`assets/media/regional-coordination-03-scenarios.png`|区域协同图03；场景接口概念板|投稿人提供区域协同概念图；具体工具、模型、日期、底图和提示词待确认|PNG 输出；插图按“典型场景示意”使用，不作为现状实景证据|未提供真实身份数据来源说明，待确认|`confirmed_by_participant`|
|VIS-018|`assets/media/regional-coordination-04-loop.png`|区域协同图04；价值闭环概念板|投稿人提供区域协同概念图；具体工具、模型、日期、底图和提示词待确认|PNG 输出；插图按“典型场景示意”使用，不作为现状实景证据|未提供真实身份数据来源说明，待确认|`confirmed_by_participant`|

机器可读对应记录见 `sources.json` 的 `visual_asset_provenance.assets`。封面、建筑方案和区域协同图在页面图注中就地标注为概念示意或典型场景示意；核心图的数值、边界、用地和交通事实由结构化文件、proposal 和指标体系共同约束。图片本身不证明已建立合作、资金安排、数据交换协议、政府实施机制或法定规划结论。
