# Task: A股行业景气度分析

**Task ID**: task-002
**Project**: china-stock-advisor-001 (A股港股投资顾问)
**Assigned to**: a-share
**Status**: pending (depends on: task-001)
**Depends on**: task-001

## 背景

基于宏观分析框架，深入分析A股各行业景气度与投资价值，为配置决策提供行业层面支撑。

## 目标

分析A股主要行业景气度、估值水平、资金流向，识别投资机会与风险。

## 交付物

1. **行业配置建议表** - 包含：
   - 至少8个主要行业的景气度判断
   - 各行业估值分位数据
   - 配置建议（超配/标配/低配）

2. **重点板块分析** - 包含：
   - 2-3个重点板块深度分析
   - 板块内个股选择逻辑
   - 风险提示

3. **北向资金分析** - 包含：
   - 近期北向资金流向
   - 外资偏好变化
   - 对配置的启示

## 验收条件

- [ ] 覆盖至少8个主要行业
- [ ] 包含景气度判断、估值分位数据
- [ ] 包含北向资金流向分析
- [ ] 提供明确配置建议

## Constraints

- 只分析行业层面，不涉及个股推荐
- 需说明估值支撑逻辑
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