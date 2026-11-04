# AI 产品作品集 · liuyumeng821

> 我关注真实使用场景中的 AI 产品：先定义用户要完成的任务，再设计可理解的交互、证据与反馈路径，并用原型和代码验证关键环节。

[GitHub 主页](https://github.com/liuyumeng821) · 联系邮箱：yumengliu398@gmail.com · [项目简历文本](PROJECT_RESUME.md)

## 项目总览

按产品定位梳理。下方封面、演示和材料链接可进入各项目查看。

| 项目 | 产品介绍（用户 · 场景 · 解决方式 · 差异化优势） | 查看 |
|---|---|---|
| **01 向星而行 Starbound** | 面向想用身体参与游戏的玩家，在居家体感冒险中用摄像头识别动作、驱动关卡反馈并保存进度，解决传统按键交互代入感弱、动作反馈不连续的问题；优势是把动作确认、游戏状态和断线恢复串成可追踪的体验链路。 | [演示视频](https://github.com/liuyumeng821/star-journey/releases/download/demo-video-v1/default.mp4) · [项目详情](https://github.com/liuyumeng821/star-journey) |
| **02 Beauty Twin** | 面向美妆新手，在选妆和实际化妆时用本人实时试妆、已有产品匹配与分步跟练，解决“看上去适合却不会画”的断层；优势是从预览到动手操作形成连续路径。 | [在线体验](https://babelbeast.com/beauty-twin) · [演示视频](https://github.com/liuyumeng821/beauty-twin/blob/main/docs/Beauty-Twin-产品体验视频.mp4) · [项目详情](https://github.com/liuyumeng821/beauty-twin) |
| **03 ChemFlow AI** | 面向化工工程学习者与方案设计者，在多阶段工艺设计中用工作流串起设计基准、流程模拟、经济和安全评估，解决跨工具整理与结论难追溯的问题；优势是显式标注数据来源、求解状态和人工确认边界。 | [项目详情](https://github.com/liuyumeng821/chemflow-ai) |
| **04 暗语森林 WhisperWood** | 面向喜欢互动叙事的玩家，在浏览器游戏中用摄像头识别手势与运动轨迹来施法，解决点击操作与故事世界脱节的问题；优势是把静态手势、动态轨迹和即时战斗反馈结合成可学习的规则。 | [项目详情](https://github.com/liuyumeng821/whisperwood) |
| **05 研伴** | 面向理工科研究生、博士后与青年科研人员，在持续检索、阅读和写作的科研场景中，用项目上下文与 Paper Memory 串起灵感启思、文献检索、深度阅读、记忆索引、论文写作和评审修改，解决资料分散与证据难追溯的问题；优势是六模块共享上下文，并区分原文、分析、假设与用户判断。 | [项目详情](https://github.com/liuyumeng821/yanban) · [PRD](https://github.com/liuyumeng821/yanban/blob/main/docs/PRD.md) |
| **06 它的一天 OneDay** | 面向宠物主人和拍摄者，在记录宠物日常时用拍摄任务组织候选事件与人工复核，解决回看长视频找素材费时的问题；优势是把拍摄意图、候选证据和最终选择分开管理。 | [项目详情](https://github.com/liuyumeng821/oneday) |
| **07 干饭盲盒 Lunch Picker** | 面向午餐选择困难的个人和小团队，在日常选餐时用候选店管理、筛选、抽签和历史记录减少反复讨论；优势是把即时随机决策与可复用的选择记录结合起来。 | [项目详情](https://github.com/liuyumeng821/lunch-picker) |
| **08 同频** | 面向想记录人宠互动的人群，在计划拍摄时用任务条件和视觉复核方案明确拍什么、如何筛素材，解决拍摄目标模糊与后期筛选负担；优势是将拍摄任务和复核标准一起设计。**目前为产品方案。** | [方案说明](concepts/tongpin/README.md) |

### 01 · 向星而行 Starbound

<a href="https://github.com/liuyumeng821/star-journey"><img src="https://raw.githubusercontent.com/liuyumeng821/star-journey/main/docs/starbound-poster.png" alt="向星而行海报" width="440"></a>

**一句话定位：** 面向希望用身体参与游戏的玩家，把摄像头动作识别、即时反馈和关卡存档连接为体感冒险体验。

**产品设计重点：** 用“动作输入→识别确认→游戏反馈→进度保存”串起完整体验；对识别误触、断线和重复事件设计状态处理。 [项目详情](https://github.com/liuyumeng821/star-journey) · [演示视频](https://github.com/liuyumeng821/star-journey/releases/download/demo-video-v1/default.mp4) · [产品 PPT](https://github.com/liuyumeng821/star-journey/blob/main/docs/starbound-presentation.pptx) · [角色与场景概念图](https://github.com/liuyumeng821/star-journey#视觉与概念图)

### 02 · Beauty Twin

<a href="https://github.com/liuyumeng821/beauty-twin"><img src="https://raw.githubusercontent.com/liuyumeng821/beauty-twin/main/docs/Beauty-Twin-作品封面-1920x1080.jpg" alt="Beauty Twin 封面" width="620"></a>

**一句话定位：** 面向不知道妆容是否适合自己的美妆新手，用本人实时试妆、已有产品匹配和分步跟练连接“选妆”与“动手画”。

**产品设计重点：** 将选择、预览、保存和操作指导放进一条低门槛路径，并处理相机不可用及设备未连接时的体验。 [在线体验](https://babelbeast.com/beauty-twin) · [演示视频](https://github.com/liuyumeng821/beauty-twin/blob/main/docs/Beauty-Twin-产品体验视频.mp4) · [项目详情](https://github.com/liuyumeng821/beauty-twin)

### 03 · ChemFlow AI 化工流程模拟与评估平台

<a href="https://github.com/liuyumeng821/chemflow-ai"><img src="https://raw.githubusercontent.com/liuyumeng821/chemflow-ai/main/docs/chemflow-cover.png" alt="ChemFlow 项目封面" width="620"></a>

**一句话定位：** 面向化工工程学习者和方案设计者，把工艺任务、流程模拟、经济与安全评估组织到可追溯的工作台，减少跨工具整理和复核成本。

**产品设计重点：** 将复杂工程问题拆成有输入、产出、来源和人工确认的步骤，让用户看清“已计算”“待验证”和“需要判断”的边界。本人担任项目负责人；答辩材料标注 NJUChem 团队。 [项目详情](https://github.com/liuyumeng821/chemflow-ai) · [答辩 PPT](https://github.com/liuyumeng821/chemflow-ai/blob/main/docs/chemflow-presentation.pptx)

### 04 · 暗语森林 WhisperWood

<a href="https://github.com/liuyumeng821/whisperwood"><img src="https://raw.githubusercontent.com/liuyumeng821/whisperwood/main/docs/cover.svg" alt="暗语森林展示封面" width="620"></a>

**一句话定位：** 面向喜欢互动叙事的玩家，把摄像头中的手势与轨迹转成法术，在浏览器里完成暗黑童话式对战。

**产品设计重点：** 把识别动作设计成可学习、可反馈的游戏规则，并考虑光线、识别稳定性和权限等试玩门槛。 [项目详情与本地试玩](https://github.com/liuyumeng821/whisperwood) · [路演材料](https://github.com/liuyumeng821/whisperwood/blob/main/docs/roadshow.pptx)

### 05 · 研伴

<a href="https://github.com/liuyumeng821/yanban"><img src="https://raw.githubusercontent.com/liuyumeng821/yanban/main/public/og.png" alt="研伴科研工作流封面" width="620"></a>

**一句话定位：** 面向理工科研究生、博士后与青年科研人员，以对话为入口、研究项目为上下文，将问题、文献、证据、判断和论文组织成可追溯的科研工作流。

**产品设计重点：** 我根据自己的科研日常独立设计开发，以项目与 Paper Memory 串起六个可独立进入的模块，并明确区分论文原文、外部事实、Agent 分析、研究假设与用户批注。 [项目详情与本地运行](https://github.com/liuyumeng821/yanban) · [完整 PRD](https://github.com/liuyumeng821/yanban/blob/main/docs/PRD.md)


## 我希望展示的产品能力

- **问题与场景定义：** 从体感游戏、美妆决策、工程任务和科研流程出发，明确用户、任务及关键阻力。
- **复杂流程拆解：** 将多步骤任务拆成可理解的状态、反馈和人工确认节点。
- **原型与技术协作：** 自己实现多个项目的前后端与交互原型；在 ChemFlow 中担任负责人。源码、演示、方案及验证记录均可从项目页进入。
- **边界意识：** 区分真实在线体验、参赛演示、教学模型、规划功能和未验收的设备/模型链路，不虚构用户数据或效果指标。

本作品集既可用于产品经理实习投递，也可用于展示 AI 产品实践。项目的完成度以各仓库 README 和验证记录为准。
