# Task: 投资配置建议整合

**Task ID**: task-005
**Project**: china-stock-advisor-001 (A股港股投资顾问)
**Assigned to**: strategist
**Status**: pending (depends on: task-002, task-003, task-004)
**Depends on**: task-002, task-003, task-004

## 背景

整合宏观分析、行业分析、港股分析和地缘风险评估，形成最终的投资配置建议。

## 目标

综合四维度分析成果，制定A股+港股配置建议，提供可执行的投资配置方案。

## 输入资源

- `task-001/result.md` - 宏观形势与政策分析
- `task-002/result.md` - A股行业景气度分析
- `task-003/result.md` - 港股市场机会分析
- `task-004/result.md` - 地缘风险评估

## 交付物

1. **配置建议报告** (`A股港股投资配置建议.md`) - 包含：
   - 执行摘要
   - 四维度分析综合
   - A股/港股配置比例建议
   - 行业配置权重建议
   - 风险提示

2. **配置执行表** (`配置建议执行表.csv`) - 包含：
   - 具体配置比例
   - 行业权重
   - 调仓建议
   - 风险偏好方案

3. **风险偏好方案** - 包含：
   - 保守型投资者方案
   - 稳健型投资者方案
   - 进取型投资者方案

## 验收条件

- [ ] 整合四维度分析
- [ ] 提供明确的A股/港股比例
- [ ] 提供行业配置权重
- [ ] 包含三种风险偏好方案

## Constraints

- 不承诺收益
- 必须包含风险提示
- 考虑个人投资者限制
- 方案需可执行

## ⚠️ Multi-Phase Collaboration Protocol

This is a multi-phase collaborative project. You MUST wait for task-002, task-003, and task-004 to complete before starting your integration.

When you complete your task:
1. Report completion with **@manager:matrix-local.hiclaw.io:18080 PROJECT_COMPLETE**
2. Include a brief summary of the final deliverables
3. The project will be marked as complete

## Task Directory Convention

- 创建 `plan.md` 记录你的执行计划
- 所有产出文件放在此目录
- 完成后写入 `result.md`
- 推送时排除 spec.md: `mc mirror ... --exclude "spec.md"`