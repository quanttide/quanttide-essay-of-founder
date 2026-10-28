# CHANGELOG

所有显著变更都将记录在此文件中。

格式基于 [Keep a Changelog](https://keepachangelog.com/zh-CN/1.0.0/)。

版本遵循语义化版本规范：0.0.x（探索期）→ 0.x.y（验证期）→ x.y.z（正式期）

---

## [Unreleased]

### 变更

- `meta/human-ai-collaboration.md` 迁到 `agent/`，与智能体主题同处；正文清掉禁用词、拆分长句，补上「法理层」一句

- `agent/agent-harness.md`：补 YAML 前置元数据 `status: pending`（待验证），署名用 `authors` 块并标 `type: agent`，与 `docs` 契约对齐
- `agent/agent-harness.md`：全文重写为论文体——去第二人称与警句式短段，定义先行、论证成段、数据入文；第七节保留，缩写数据与来源写清
- `agent/agent-harness.md`：补第七节「系统开始看自己」——闸门、体检、巡检合起来让系统第一次有了可查的记录；巡检数据说明看见不等于自我纠正；结论顺延为第八节
- `fiction/mutual-secret-crush.md` 与 `write/from-reality-to-fiction.md` 互引：补三条线的心理问法与结构答法对照、情绪与时间的换算、读者账与自己账的区分，后者落定立意引文
- `language/context.md`：「章程的发现」按降级后的条文改写——章程只留第三条「不跨语境借词」，财务与计算机术语的词表移入案例集
- `language/context.md`：三要素改按语域理论称语场、语旨、语式，惯例拆进体裁规约与语域期望；「语境决定什么」改为「语境约束什么」，「日常说法」改为「该语场惯用的说法」，与规格的约束口径一致

### 新增

- `design/design-os.md`：设计操作系统——模型在强约束的中间层（设计 DSL）里做意图与取舍，确定性代码用信息预算、栅格间距、字号阶梯、视觉重量、可访问性、布局预演六条硬规则做校验；自 `data/context/default/insight/design.md` 迁入并整理成初稿
- `life/pressure.md`：从觉察到整合的压力应对方法——结构性孤独与双重角色耗能，以及观察、记录、对话、整合四步循环；自 `data/context/life/essay/` 迁入，正文未改
- `agent/agent-harness.md`：智能体架子——参考与约束不是程度差别；生成端只能给参考，验收端才能给约束，所以闸门装在写入那一刻；规则要离开对话，得自带结构、语义界线与正反例；架子自身要能被删，否则约束只进不出
- `language/context.md`：语境——词为什么站错位置，从对象、读者、惯例定义语境，区分语境与上下文，列错配的三种表现、根源与章程的语境边界
- `meta/human-ai-collaboration.md`：人机协作——从初稿必冗余、问法决定精简深度，到工作量从生产转向治理、约束 AI 的副产品成为基础设施，并以「下一轮能少写多少」重定协作的衡量标准

- `work/task-blueprint-vs-workflow.md`：任务蓝图与工作流——从完备性、身份与变更、判据位置、读者与语言四组对照，提出以任务蓝图为真源、工作流降为可选投影的阶段判断，并列运行快照、跨任务复用与治理后置三项代价
- `work/artifact-contract.md`：产物契约——把合格线从步骤里独立出来，定义三条禁令、约束四项、四种机判句式与人判边界，并以产物定义的四问划清分工
- `write/from-reality-to-fiction.md`：从现实到虚构——整合手册 `write/` 三篇（动机、方法、卡点）为一篇，按「现实派下任务、素材进虚构、卡点在门口、故事回现实」重排
- 初始化论文仓库：`README.md`、`index.md`（入口，待补充）、`myst.yml`
- `fiction/mutual-secret-crush.md`：双向暗恋文的叙事方法（常见套路、反思、我们的尝试及优缺点），结论泛化，不依赖具体样本
