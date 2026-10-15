# 能力索引（完整版）

| capability_id | 标题 | 重要度 | 意图 | 关键词 | 能力卡 |
|---|---|---|---|---|---|
| cap.fde.genuine-check | 真假 FDE 判断 | critical | 判断一个岗位/团队是不是真 FDE；分辨 FDE 与外包/售前/实施换皮 | 真假FDE、FDE判断、外包换皮、驻场开发、forward deployed | capabilities/genuine-check.md |
| cap.fde.intake-gate | 进场前判断（立项四问 + 客户四问） | critical | 判断一个项目该不该接；判断客户组织能否接住 FDE | 立项四问、客户四问、退出条件、进场判断、customer fit | capabilities/intake-gate.md |
| cap.fde.five-day-discovery | 五天摸真问题 | critical | 摸清客户真正的痛点；区分真问题与客户的合理选择 | 五天摸真问题、进场第一周、真问题、奇怪的星期二、discovery | capabilities/five-day-discovery.md |
| cap.fde.translation-northstar | 翻译问题 + 北极星三条件 | critical | 把客户模糊目标翻译成可衡量结果；选定北极星指标 | 翻译问题、北极星指标、归因、衡量成功、north star | capabilities/translation-northstar.md |
| cap.fde.use-case-prioritization | 用例优先级表 | critical | 给候选场景排序；有理有据地拒绝某个场景 | 用例优先级、价值链、打分排序、做延后放弃、prioritization | capabilities/use-case-prioritization.md |
| cap.fde.stakeholder-map | 干系人地图 + 怀疑者/赞助人管理 | critical | 画干系人地图、找关键人；转化怀疑者、防止赞助人崩塌 | 干系人地图、怀疑者、赞助人、谁说了算、stakeholder | capabilities/stakeholder-map.md |
| cap.fde.pyramid-reporting | 汇报金字塔 + MECE | medium | 组织向高管/客户的汇报；把技术语言翻译成业务语言 | 金字塔原理、MECE、结论先行、汇报、executive summary | capabilities/pyramid-reporting.md |
| cap.fde.demo-driven | demo 驱动开发（MVP + MVA + 每周 demo） | critical | 做第一个 demo；把模糊反馈转成具体工单 | MVP、MVA、每周demo、端到端、demo driven | capabilities/demo-driven.md |
| cap.fde.code-placement | 施工纪律（gap 四象限 + 代码三区） | critical | 判断客户需求写在哪；避免代码越来越臃肿 | gap四象限、代码三区、负债区、资产区、feature flag | capabilities/code-placement.md |
| cap.fde.integration-migration | 集成与迁移三动作 | high | 对接外部系统；数据迁移对账 | 集成清单、数据迁移、对账标准、联调、integration | capabilities/integration-migration.md |
| cap.fde.versioning-discipline | 私有化版本纪律 | medium | 管理私有化版本节奏 | 私有化版本、版本纪律、大版本中版本小版本、versioning | capabilities/versioning-discipline.md |
| cap.fde.knowledge-layering | 四层知识库 | critical | 组织知识给 Agent 用；定位客户环境准确率下降原因 | 四层知识库、知识分层、指标口径、knowledge base | capabilities/knowledge-layering.md |
| cap.fde.safety-guardrails | 安全护栏五件套 | critical | 配置 Agent 安全护栏；防止 Agent 越权 | 护栏、字段级权限、脱敏、审计、guardrail | capabilities/safety-guardrails.md |
| cap.fde.eval-driven | 评估驱动开发 | critical | 定义 AI 系统的「好」；构建评估集 | 评估集、黄金集、棘轮原则、harness、eval driven | capabilities/eval-driven.md |
| cap.fde.go-live | 上生产（六项检查 + 治理 + 留痕 + HITL） | critical | 做上生产前检查；设计治理方案与人工检查点 | 上线检查、六项检查、HITL、全链路留痕、go live | capabilities/go-live.md |
| cap.fde.sediment-pipeline | 沉淀管道（内环外环 + 平台提交 + 前后方握手） | critical | 把客户成果沉淀成产品；建立平台提交机制 | 内环外环、平台提交、前后方握手、沉淀、productization | capabilities/sediment-pipeline.md |
| cap.fde.autonomy-ladder | 自治阶梯（交接） | medium | 把项目交接给客户团队；避免客户离不开你 | 自治阶梯、交接、永久拐杖、handover | capabilities/autonomy-ladder.md |
| cap.fde.private-knowledge | 私有知识四步转化 | high | 把经验沉淀成知识资产；判断知识能不能跨客户共享 | 私有知识、脱敏、边界三问、知识资产、tacit knowledge | capabilities/private-knowledge.md |
| cap.fde.pricing-ola-raas | 定价（OLA + RaaS + 客单价匹配） | high | 给 FDE 项目定价；写结果级协议 | OLA、RaaS、效果分成、定价、outcome | capabilities/pricing-ola-raas.md |
| cap.fde.service-trap | 服务陷阱（a16z 四条件 + 毛利换护城河） | high | 判断重服务值不值得做；避免滑向服务陷阱 | 服务陷阱、毛利、护城河、a16z、gross margin | capabilities/service-trap.md |
| cap.fde.retrospective | 五步复盘 | medium | 复盘一个 FDE 项目 | 五步复盘、项目复盘、可复用资产、retrospective | capabilities/retrospective.md |
| cap.fde.failure-identification | 失败识别与止损 | high | 给团队做失败模式体检；判断项目该不该止损 | 六大失败模式、预警信号、止损、退出评估、failure modes | capabilities/failure-identification.md |
| cap.fde.regulated-industry | 强监管行业三笔商业账 | medium | 判断强监管行业值不值得做重；把治理能力做成可复用产品 | 三笔账、治理即产品、强监管、合规、regulated | capabilities/regulated-industry.md |
| cap.fde.industrial-rule-model | 制造/能源：规则/模型划界 + 数据地基 | medium | 判断用规则还是用模型；检查数据地基 | 规则模型划界、数据地基、安全红线、工业AI、rules vs model | capabilities/industrial-rule-model.md |
| cap.fde.customer-service-authorization | 客服授权三级 + 降级 | medium | 设计客服 Agent 授权边界；定义拦截率与降级机制 | 客服授权、拦截率、敢托付、降级机制、containment | capabilities/customer-service-authorization.md |
| cap.fde.capability-interview | 能力模型与面试 | medium | 自评/评估 FDE 能力；准备 FDE 面试与入职 | 一纵一横一软、四轮面试、30-60-90、能力模型、interview | capabilities/capability-interview.md |
| cap.fde.career-development | 职业发展（晋升双通道 + 是否做 FDE + 个人止损） | medium | 判断 FDE 职业去留；设计晋升通道 | 晋升双通道、职业发展、个人止损、倦怠、career | capabilities/career-development.md |
