# Project: 国际政治形势分析与预测

**ID**: intl-politics-20260324-150731
**Status**: planning
**Room**: !oNyE5upFmVXLA5U9jT:matrix-local.hiclaw.io:18080
**Created**: 2026-03-24T15:07:31+08:00
**Confirmed**: pending

## Team

- @manager:matrix-local.hiclaw.io:18080 — Project Manager
- @info-collector:matrix-local.hiclaw.io:18080 — 信息收集专员
- @geo-analyst:matrix-local.hiclaw.io:18080 — 地缘战略分析师
- @econ-analyst:matrix-local.hiclaw.io:18080 — 经济与制裁分析师
- @military-analyst:matrix-local.hiclaw.io:18080 — 军事安全分析师
- @predictor:matrix-local.hiclaw.io:18080 — 预测建模师
- @report-writer:matrix-local.hiclaw.io:18080 — 报告撰写专员
- @coordinator:matrix-local.hiclaw.io:18080 — 协调者

## Task Plan

### Phase 1: 信息采集阶段

- [x] task-20260324-150800 — 信息采集与筛选 (assigned: @info-collector:matrix-local.hiclaw.io:18080)
  - 覆盖主要国家/地区（中美俄欧印等）
  - 信息分类：政治/经济/军事/外交
  - 每条信息标注：来源、时间、可信度、相关度
  - 验收条件：信息来源 ≥ 5 类，覆盖近 30 天重大事件，每条信息可追溯
  - Spec: /root/hiclaw-fs/shared/tasks/task-20260324-150800/spec.md
  - Result: /root/hiclaw-fs/shared/tasks/task-20260324-150800/result.md

### Phase 2: 分析阶段（并行执行）

- [x] task-20260324-174400 — 地缘战略分析 (assigned: @geo-analyst:matrix-local.hiclaw.io:18080, depends on: task-20260324-150800)
  - 关键行为体及其利益分析
  - 双边/多边关系图谱
  - 潜在冲突热点识别
  - 战略博弈态势评估
  - 验收条件：覆盖主要大国关系，识别至少 3 个风险点，提供历史对比分析
  - Spec: /root/hiclaw-fs/shared/tasks/task-20260324-150900/spec.md
  - Result: /root/hiclaw-fs/shared/tasks/task-20260324-150900/result.md

- [x] task-20260324-174401 — 经济影响分析 (assigned: @econ-analyst:matrix-local.hiclaw.io:18080, depends on: task-20260324-150800)
  - 关键经济关联度分析
  - 制裁/反制措施影响评估
  - 能源、贸易、金融风险分析
  - 经济传导路径图
  - 验收条件：包含量化数据支撑，识别主要经济风险，评估经济工具的政治效用
  - Spec: /root/hiclaw-fs/shared/tasks/task-20260324-150901/spec.md
  - Result: /root/hiclaw-fs/shared/tasks/task-20260324-150901/result.md

- [x] task-20260324-174402 — 军事安全评估 (assigned: @military-analyst:matrix-local.hiclaw.io:18080, depends on: task-20260324-150800)
  - 关键军事动态监测
  - 冲突风险评估（低/中/高）
  - 同盟军事协作分析
  - 核威慑态势评估
  - 验收条件：风险等级有依据，覆盖主要热点地区，标注预警指标
  - Spec: /root/hiclaw-fs/shared/tasks/task-20260324-150902/spec.md
  - Result: /root/hiclaw-fs/shared/tasks/task-20260324-150902/result.md

### Phase 3: 预测阶段

- [x] task-20260324-151000 — 综合预测建模 (assigned: @predictor:matrix-local.hiclaw.io:18080, depends on: task-20260324-150900,task-20260324-150901,task-20260324-150902)
  - 三情景预测（乐观/中性/悲观）
  - 关键变量识别
  - 转折点预警指标
  - 6-12 个月趋势判断
  - 验收条件：每个情景有逻辑支撑，标注概率范围，设定可验证指标
  - Spec: /root/hiclaw-fs/shared/tasks/task-20260324-151000/spec.md
  - Result: /root/hiclaw-fs/shared/tasks/task-20260324-151000/result.md

### Phase 4: 报告阶段

- [~] task-20260324-151100 — 最终报告撰写 (assigned: @report-writer:matrix-local.hiclaw.io:18080, depends on: task-20260324-151000)
  - 执行摘要（1-2 页）
  - 完整分析报告
  - 可视化图表（关系图、风险矩阵、时间线）
  - 附录（数据来源、方法论）
  - 验收条件：结构清晰、逻辑连贯，关键发现突出，适合决策者阅读
  - Spec: /root/hiclaw-fs/shared/tasks/task-20260324-151100/spec.md
  - Result: /root/hiclaw-fs/shared/tasks/task-20260324-151100/result.md
  - **On REVISION_NEEDED**: return to task-20260324-151000 | reassign to @predictor:matrix-local.hiclaw.io:18080

### Phase 5: 发布阶段

- [ ] task-20260324-151200 — 质量审核与发布 (assigned: @coordinator:matrix-local.hiclaw.io:18080, depends on: task-20260324-151100)
  - 质量审核
  - 格式规范检查
  - 发布版报告输出
  - 验收条件：所有验收条件满足，格式符合发布标准
  - Spec: /root/hiclaw-fs/shared/tasks/task-20260324-151200/spec.md
  - Result: /root/hiclaw-fs/shared/tasks/task-20260324-151200/result.md
  - **On REVISION_NEEDED**: return to task-20260324-151100 | reassign to @report-writer:matrix-local.hiclaw.io:18080

## Deliverables

| 交付物 | 格式 | 负责任务 |
|--------|------|----------|
| 原始信息库 | 数据库/文件 | task-20260324-150800 |
| 地缘分析报告 | Markdown | task-20260324-150900 |
| 经济影响评估报告 | Markdown | task-20260324-150901 |
| 安全风险评估报告 | Markdown | task-20260324-150902 |
| 多情景预测报告 | Markdown | task-20260324-151000 |
| 完整分析报告 | Markdown/PDF | task-20260324-151100 |
| 发布版报告 | PDF | task-20260324-151200 |

## Change Log

- 2026-03-24T15:07:31+08:00: Project initiated- 2026-03-24T15:12:00+08:00: Plan confirmed by human
- 2026-03-24T15:12:00+08:00: Task task-20260324-150800 assigned to info-collector
