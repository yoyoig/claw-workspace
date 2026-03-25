# Task: 地缘风险评估

**Task ID**: task-004
**Project**: china-stock-advisor-001 (A股港股投资顾问)
**Assigned to**: geo-risk
**Status**: pending (depends on: task-001)
**Depends on**: task-001

## 背景

基于宏观分析框架，评估地缘政治风险对A股和港股投资的影响，包括中美关系、供应链、汇率等维度。

## 目标

识别和评估影响A股与港股投资的地缘政治风险，提供差异化风险评级。

## 交付物

1. **风险报告** - 包含：
   - 中美关系风险评估
   - 供应链风险分析
   - 汇率风险分析
   - 其他关键地缘因素

2. **情景分析** - 包含：
   - 乐观情景
   - 中性情景
   - 悲观情景
   - 各情景概率估计

3. **差异化影响分析** - 包含：
   - 对A股的影响程度
   - 对港股的影响程度
   - 两市场风险差异比较

4. **风险等级评定** - 包含：
   - 总体风险等级
   - 分项风险等级
   - 风险监控指标

## 验收条件

- [ ] 覆盖中美关系、供应链、汇率等维度
- [ ] 区分对A股 vs 港股的差异化影响
- [ ] 提供风险等级评定
- [ ] 包含情景分析

## Constraints

- 专注投资影响分析
- 不做政治判断
- 保持客观中立
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