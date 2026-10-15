---
name: fde-playbook
description: |
  当用户在做 To B / AI 交付相关工作、需要 FDE（Forward Deployed Engineer，前向部署工程师）业务落地方法论时调用。
  覆盖：判断真假 FDE、进场前判断（立项四问+客户四问）、五天摸真问题、选场景（翻译问题+北极星三条件+用例优先级表）、干系人地图与信任、汇报金字塔、demo 驱动开发（MVP+MVA+每周 demo）、施工纪律（gap 四象限+代码三区）、集成迁移、私有化版本纪律、四层知识库、安全护栏五件套、评估驱动开发（三类评估集+棘轮）、上生产（六项检查+HITL）、沉淀（平台提交+自治阶梯）、私有知识四步、定价（OLA+RaaS）、服务陷阱、五步复盘、失败识别与止损、行业落地（金融/制造/零售客服）、能力模型与面试、职业发展。
  不适用于: 具体代码实现与具体技术选型、具体投资标的、需要专业资质的医疗/法律/财务审计事项。
  Triggers: FDE/前向部署/业务落地/交付方法论/客户现场/真问题/北极星/demo/评估集/服务陷阱/forward deployed/field engineer
metadata:
  cangjie.generated-by: cangjie-tools v2.5.0
  cangjie.variant: single
  cangjie.bundle-id: bundle.fde-playbook
  cangjie.capability-count: 27
  cangjie.entrypoint-count: 1
---
# 《FDE 业务落地实战课》 — 全书能力入口

## 触发与不触发

**适用**：与本书能力域相关的咨询与任务（见下方路由表的意图列）。
**不适用**：
- 具体代码实现与具体技术选型（本课是交付方法论，不是编程手册）
- 具体投资标的、财务审计等需要专业资质的事项
- 医疗/法律/人身安全的专业决策

## 核心原则（常驻速览，概览类问题读到这里即可回答）

1. AI 负责「做出来」，人负责「判断是否做得好」——写代码不再稀缺，把 AI 交付成业务结果 + 现场认知沉淀回产品才是稀缺能力。
2. 判断真假 FDE 只看两条硬线：现场认知是否回流产品、第二个客户是否做得更容易。
3. 进场最大陷阱是把「嘴上需求」当「真问题」；选场景是把「想要什么」翻译成「什么变化 + 哪个数字」。
4. demo 是让客户说「不对」的工具，不是让客户说「哇塞」的道具；MVP 验价值、MVA 验可行性。
5. 施工纪律：代码写在哪（负债/隔离/资产）决定它是资产还是负债；数据安全护栏第一天焊死。
6. 先定义「好」再写第一行 prompt，评估集是开发迭代的方向盘，不是上线前的验收工序。
7. 内环让客户满意、外环让公司值钱；只做内环就是套着软件外壳的咨询公司。

## 能力路由（先读本表，按意图加载 1 张能力卡）

| 用户意图 | 先读 | 补读/备注 |
|---|---|---|
| 判断一个岗位/团队是不是真 FDE；分辨 FDE 与外包/售前/实施换皮 | references/capabilities/genuine-check.md | references/capabilities/service-trap.md、references/capabilities/capability-interview.md |
| 判断一个项目该不该接；判断客户组织能否接住 FDE | references/capabilities/intake-gate.md | references/capabilities/five-day-discovery.md、references/capabilities/genuine-check.md |
| 摸清客户真正的痛点；区分真问题与客户的合理选择 | references/capabilities/five-day-discovery.md | references/capabilities/intake-gate.md、references/capabilities/translation-northstar.md |
| 把客户模糊目标翻译成可衡量结果；选定北极星指标 | references/capabilities/translation-northstar.md | references/capabilities/five-day-discovery.md、references/capabilities/use-case-prioritization.md、references/capabilities/pricing-ola-raas.md |
| 给候选场景排序；有理有据地拒绝某个场景 | references/capabilities/use-case-prioritization.md | references/capabilities/translation-northstar.md、references/capabilities/demo-driven.md |
| 画干系人地图、找关键人；转化怀疑者、防止赞助人崩塌 | references/capabilities/stakeholder-map.md | references/capabilities/pyramid-reporting.md、references/capabilities/intake-gate.md、references/capabilities/failure-identification.md |
| 组织向高管/客户的汇报；把技术语言翻译成业务语言 | references/capabilities/pyramid-reporting.md | references/capabilities/stakeholder-map.md |
| 做第一个 demo；把模糊反馈转成具体工单 | references/capabilities/demo-driven.md | references/capabilities/use-case-prioritization.md、references/capabilities/eval-driven.md、references/capabilities/go-live.md |
| 判断客户需求写在哪；避免代码越来越臃肿 | references/capabilities/code-placement.md | references/capabilities/versioning-discipline.md、references/capabilities/sediment-pipeline.md |
| 对接外部系统；数据迁移对账 | references/capabilities/integration-migration.md | references/capabilities/code-placement.md、references/capabilities/go-live.md |
| 管理私有化版本节奏 | references/capabilities/versioning-discipline.md | references/capabilities/code-placement.md |
| 组织知识给 Agent 用；定位客户环境准确率下降原因 | references/capabilities/knowledge-layering.md | references/capabilities/private-knowledge.md、references/capabilities/safety-guardrails.md |
| 配置 Agent 安全护栏；防止 Agent 越权 | references/capabilities/safety-guardrails.md | references/capabilities/knowledge-layering.md、references/capabilities/go-live.md |
| 定义 AI 系统的「好」；构建评估集 | references/capabilities/eval-driven.md | references/capabilities/demo-driven.md、references/capabilities/go-live.md |
| 做上生产前检查；设计治理方案与人工检查点 | references/capabilities/go-live.md | references/capabilities/eval-driven.md、references/capabilities/safety-guardrails.md、references/capabilities/demo-driven.md |
| 把客户成果沉淀成产品；建立平台提交机制 | references/capabilities/sediment-pipeline.md | references/capabilities/autonomy-ladder.md、references/capabilities/private-knowledge.md、references/capabilities/code-placement.md |
| 把项目交接给客户团队；避免客户离不开你 | references/capabilities/autonomy-ladder.md | references/capabilities/sediment-pipeline.md |
| 把经验沉淀成知识资产；判断知识能不能跨客户共享 | references/capabilities/private-knowledge.md | references/capabilities/knowledge-layering.md、references/capabilities/sediment-pipeline.md |
| 给 FDE 项目定价；写结果级协议 | references/capabilities/pricing-ola-raas.md | references/capabilities/translation-northstar.md、references/capabilities/service-trap.md |
| 判断重服务值不值得做；避免滑向服务陷阱 | references/capabilities/service-trap.md | references/capabilities/pricing-ola-raas.md、references/capabilities/sediment-pipeline.md、references/capabilities/failure-identification.md |
| 复盘一个 FDE 项目 | references/capabilities/retrospective.md | references/capabilities/sediment-pipeline.md、references/capabilities/failure-identification.md |
| 给团队做失败模式体检；判断项目该不该止损 | references/capabilities/failure-identification.md | references/capabilities/service-trap.md、references/capabilities/retrospective.md、references/capabilities/stakeholder-map.md |
| 判断强监管行业值不值得做重；把治理能力做成可复用产品 | references/capabilities/regulated-industry.md | references/capabilities/industrial-rule-model.md、references/capabilities/customer-service-authorization.md |
| 判断用规则还是用模型；检查数据地基 | references/capabilities/industrial-rule-model.md | references/capabilities/regulated-industry.md、references/capabilities/go-live.md |
| 设计客服 Agent 授权边界；定义拦截率与降级机制 | references/capabilities/customer-service-authorization.md | references/capabilities/industrial-rule-model.md、references/capabilities/go-live.md |
| 自评/评估 FDE 能力；准备 FDE 面试与入职 | references/capabilities/capability-interview.md | references/capabilities/genuine-check.md、references/capabilities/career-development.md |
| 判断 FDE 职业去留；设计晋升通道 | references/capabilities/career-development.md | references/capabilities/capability-interview.md、references/capabilities/failure-identification.md |

**非能力类查询**：
- 书名/作者/章节/整书概览 → references/overview.md
- 术语解释 → references/glossary.md
- 决策规则速查（不需要原文依据时） → references/cheatsheet.md
- 完整意图与关键词索引（本表未覆盖的意图先查这里） → references/capability-index.md

## 加载规则

- 每次任务先读本文件，再按路由表加载 **1** 张能力卡；任务明确跨域时最多加载 2 张。
- 概览/书名类问题不加载能力卡，用「核心原则」与 overview.md 回答。
- 路由表与 capability-index.md 都无法命中的意图，明确告知超出本书范围，不要硬套。

## 边界与判停

- 意图在 27 个能力卡的 intents 与路由表均无法命中 → 明确告知超出本书范围，不硬套框架。
- 涉及医疗/法律/人身安全 → 停止套用方法论，建议专业求助。
- 纯事实查询（书名/作者/章节）→ 用 overview 回答后即停，不展开方法论建议。
