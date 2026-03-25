# Task: 港股市场机会分析

**Task ID**: task-003
**Project**: china-stock-advisor-001 (A股港股投资顾问)
**Assigned to**: hk-market
**Status**: pending (depends on: task-001)
**Depends on**: task-001

## 背景

基于宏观分析框架，分析港股市场投资机会，包括估值、AH溢价、资金流向等维度，为跨市场配置提供支撑。

## 目标

评估港股市场当前配置价值，识别投资机会与风险。

## 交付物

1. **港股市场报告** - 包含：
   - 恒生指数估值分位
   - AH溢价指数分析
   - 港股通资金流向
   - 市场情绪指标

2. **投资机会清单** - 包含：
   - 优质港股标的筛选逻辑
   - 行业分布建议
   - 风险收益比评估

3. **配置价值评估** - 包含：
   - 当前时点配置建议
   - 与A股配置比例建议
   - 流动性风险提示

## 验收条件

- [ ] 包含恒指估值分位
- [ ] 包含AH溢价分析
- [ ] 包含港股通资金流向
- [ ] 评估当前配置价值

## Constraints

- 必须标注流动性风险
- 考虑港股通投资限制
- 不涉及个股推荐
- 数据来源需标注

## ⚠️ Multi-Phase Collaboration Protocol

This is a multi-phase collaborative project. You MUST wait for task-001 to complete before starting your analysis.

When you complete your task:
1. Report completion with **@manager:matrix-local.hiclaw.io:18080 TASK_DONE**
2. Include a brief summary of what was done
3. Wait for Manager to coordinate next steps

## Task Directory Convention

- 创建 `plan.md` 记录你的执行计划
- 所有产出文件放在此目录
- 完成后写入 `result.md`
- 推送时排除 spec.md: `mc mirror ... --exclude "spec.md"`