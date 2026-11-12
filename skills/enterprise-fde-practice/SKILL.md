---
name: enterprise-fde-practice
description: "基于FDEInterviews《Building an Enterprise FDE Practice》的企业FDE团队经营学习技能。用于章程、准入、授权、容量、试点、生产移交、指标与投资复盘；逐章读取并将合成案例、观察、推断、建议和授权分开。"
---

# FDEInterviews《Building an Enterprise FDE Practice》

本技能依据用户提供的本地 OCR 版本；共 34 章。修订于 2026-11-12。

## 使用方式

1. 用户可说“从第 N 章教我”“解释术语”“给我自测”或提供企业 AI 项目要求诊断。先用下方主题索引定位，再**读取对应章节文件**；综合问题读最相关的 2–3 章。
2. 教学按“一个关键判断→源内例子或重新构造的短例→一道检查题→用户回答后的纠偏”推进。项目诊断给出**当前证据、缺口、有权决策人、最小下一步、停止/升级条件**。
3. 数字、原句、案例细节先用 `scripts/read_source.py` 按 OCR 行号回查。该工具在有同版合法来源时运行；公共安装版无 OCR，若未提供源文件，明确说无法核验精确原文。严禁大段复述原书。
4. 说清“来源观察/作者判断/教学案例/我的应用推演”，不得把案例估算当现实业绩；时效性事实须查询当前原始来源。若与用户真实组织政策或授权冲突，以有权人的实际决定为准。
5. 跨三本 FDE 书时分别调用各技能，保留作者定义差异。来源限制见 [核验说明](references/source-quality.md)。

**决策路线**：从团队章程到交付义务的闭环：准入→授权→发现→试点→生产→采用→接收方演练→复用→投资复盘。

## 用本书作决策

1. **四类陈述先分开（前言）**：观察要有记录和窗口；推断须写假设与替代解释；建议须说明何时反转；授权只能由有权负责人作出。一次评估通过不等于获准使用数据、发布生产或接受风险。
2. **先经营实践，再配置人手（第1–9章）**：用可拒绝项目的章程定义问题类别、资金、容量、权限和退出。准入先检查有界问题、数据许可、下一决策者与实践适配；再比较机会。计划同时检查总小时、稀缺技能、辅导、旧项目支持与储备。
3. **交付证据闸口（第10–18章）**：观察实际工作与基线；协议分开技术验收、业务验收和发布授权。试点独立检验有用结果、技术、运行、采纳；生产审查版本、环境、用户、失败恢复和接收方。移交要由接收者亲手完成适当环境的恢复演练。
4. **AI 的动作契约（第14–15章）**：定义任务、评价、成本、允许动作、失败回退和版本。在服务端以当前身份核对确切动作；审批绑定确切载荷。外部写入结果未知时先对账，不能把超时当未执行。
5. **指标与经济性（第17、21–23、33章）**：固定合格任务分母、起止时钟和开放队列。释放工时是容量；只有实际支出或增量收入改变，才能主张现金效益。NRR、扩张与避免流失勿双计，内部转账勿当企业收入。
6. **资产与扩张（第19–26章）**：代码合并不是产品化；兼容、支持、迁移和退役都需所有者。扩张依据合格需求、可兑现容量和资金。30/90/180 天只是审查窗口，不是成熟度证书。

## 章节导航

| 章 | 主题 | 应解决的决定 |
|---|---|---|
| [01](chapters/ch01.md) | Choose the practice you are building | 先定义实践的服务问题、资金与退出义务，再决定招多少人。 |
| [02](chapters/ch02.md) | Admit work that deserves the capacity | 准入先查问题、权限、决策人与职责，合格后再排序。 |
| [03](chapters/ch03.md) | Make authority visible | 把权力写到具体决定上，组织汇报线不能代替客户许可。 |
| [04](chapters/ch04.md) | Fund a bounded experiment | 首笔预算购买有限学习周期，包含客户以外的真实工作。 |
| [05](chapters/ch05.md) | Hire for the work you can name | 招聘画像必须来自即将执行的任务与团队单点。 |
| [06](chapters/ch06.md) | Test judgment with shared evidence | 面试评价可观察判断，候选人应看到一致的情境与评分锚点。 |
| [07](chapters/ch07.md) | Ramp through permissioned responsibility | 入职权限应随经审查的能力证据逐级扩大。 |
| [08](chapters/ch08.md) | Reward durable contribution | 绩效要看可控制的贡献和留下的持续能力。 |
| [09](chapters/ch09.md) | Plan capacity in the units that constrain you | 容量要同时对齐总工时、稀缺技能和客户依赖。 |
| [10](chapters/ch10.md) | Observe the work before designing the system | 先观察操作员的真实任务与异常，再设计解决方案。 |
| [11](chapters/ch11.md) | Write an agreement that survives a change | 项目协议要让范围改变时仍能重做决定。 |
| [12](chapters/ch12.md) | Make the pilot answer a question | 试点必须回答一个会改变下一步投资或发布决定的问题。 |
| [13](chapters/ch13.md) | Release a system someone can operate | 生产准备度是对确定版本、环境、人群和运营责任的证据声明。 |
| [14](chapters/ch14.md) | Work inside the customer's authority | 客户授权按主体、资源、动作、目的和时限逐项约束。 |
| [15](chapters/ch15.md) | Put AI behavior inside an engineering contract | 给 AI 任务写工程契约，推理能力不等于行动许可。 |
| [16](chapters/ch16.md) | Escalate the decision that is blocked | 交付阻塞与活跃事故使用不同升级时钟。 |
| [17](chapters/ch17.md) | Change the workflow people actually use | 采纳要看合格业务实例最终得到被接受的结果。 |
| [18](chapters/ch18.md) | End the engagement with a capable owner | FDE 离场前接收方要在适当环境亲自完成运行和恢复。 |
| [19](chapters/ch19.md) | Turn field work into supported capability | 现场产物进入产品要有人承接支持、兼容和生命周期。 |
| [20](chapters/ch20.md) | Build a platform the practice will use | 内部平台从重复且昂贵的交付摩擦开始。 |
| [21](chapters/ch21.md) | Measure the practice without rewarding concealment | 指标必须为具体管理决定服务，保留分母与开放队列。 |
| [22](chapters/ch22.md) | Price the obligation you are accepting | 收费方式必须与实际承诺的交付和支持义务一致。 |
| [23](chapters/ch23.md) | Make a defensible investment case | 投资结论区分参与结果、结果变化和因果增量。 |
| [24](chapters/ch24.md) | Run reviews that produce decisions | 复盘会必须产生有权人作出的选择。 |
| [25](chapters/ch25.md) | Scale only the parts that work | 扩张依据持续合格需求和可运行能力，而不是队列长度。 |
| [26](chapters/ch26.md) | Launch in evidence gates | 用证据闸口启动实践，日期只提醒评审。 |
| [27](chapters/ch27.md) | A startup with more promises than capacity | 创业公司承诺超过容量时，先区分可执行发现与被产品/权限阻塞的请求。 |
| [28](chapters/ch28.md) | A vendor whose shared capacity keeps disappearing | 供应商总工时可用不代表稀缺专家和共享工程可用。 |
| [29](chapters/ch29.md) | An internal enterprise practice must find the benefit owner | 内部团队须找到收益实现的业务负责人。 |
| [30](chapters/ch30.md) | Reset a practice that cannot leave its customers | 无法离开旧客户的团队先盘点支持义务，再谈新增交付。 |
| [31](chapters/ch31.md) | Rehearse the leadership decisions | 通过角色演练检查权责与证据是否在压力下仍成立。 |
| [32](chapters/ch32.md) | Use the operating toolkit | 根据需要作出的决定选择记录，别让二十四张表成为目的。 |
| [33](chapters/ch33.md) | A metric dictionary with explicit boundaries | 指标词典必须规定对象、分母、窗口、排除与用途。 |
| [34](chapters/ch34.md) | A shared working vocabulary | 共享词汇要防止同一个词掩盖不同承诺。 |

## 主题索引

- **章程 / Charter**：01、26
- **项目准入 / Intake**：02
- **决策权 / 权限**：03、14
- **预算 / 实现率**：04、09、22
- **招聘 / 结构化面试**：05–06
- **入职爬坡 / 绩效**：07–08
- **稀缺技能容量**：09、28
- **发现 / 基线**：10
- **项目协议 / 范围变更**：11
- **试点四项测试**：12
- **生产准备 / 恢复**：13
- **数据许可 / 风险例外**：14
- **AI 行动授权 / 未知写入**：15
- **升级与事故**：16
- **采纳分母 / 流程变更**：17、33
- **交接毕业测试**：18
- **组件吸收 / 平台**：19–20
- **指标 / 开放队列**：21、33
- **收费 / 完整成本**：22
- **ROI / 反事实**：23
- **评审 / 扩张**：24–26
- **四个虚构教学案例**：27–30
- **T01–T24 工具说明**：32
- **术语边界**：34

## 辅助文件

- [决策方法库](patterns.md)：在项目中执行的步骤与退出条件。
- [决策速查](cheatsheet.md)：情境对应的下一步和证据。
- [术语](glossary.md)：本书语境的工作性定义。
- [后记与附录导读](references/backmatter.md)：补充证据口径与出版边界。
- [来源质量](references/source-quality.md)、[章节行号和 SHA](references/source-manifest.json)：精确核查边界。
