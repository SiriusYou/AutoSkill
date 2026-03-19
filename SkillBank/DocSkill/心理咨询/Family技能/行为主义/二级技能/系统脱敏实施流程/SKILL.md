---
id: "5b4feb3c-37d5-5f43-b4da-aa1c4978551f"
name: "系统脱敏实施流程"
description: "在行为主义框架下，于单次咨询中执行系统脱敏干预：依据已构建的焦虑等级表，结合放松技术，逐级暴露并消退焦虑反应。"
version: "0.1.0"
tags:
  - "行为主义"
  - "系统脱敏"
  - "暴露疗法"
  - "放松训练"
  - "profile:psychology::行为主义"
  - "axis:疗法"
triggers:
  - "已完成焦虑等级量表构建"
  - "来访者已掌握基础放松技术"
  - "当前咨询阶段为暴露干预期"
examples:
  - input: "来访者SUDS=50，进入等级3（后台候场）想象"
    output: "引导其闭眼想象候场场景，同步指导腹式呼吸（4-7-8法），每30秒询问SUDS；当降至≤25时，确认后进入等级4"
    notes: "需实时监测生理指标（如呼吸频率、手心出汗）作为辅助判断"
---

# 系统脱敏实施流程

在行为主义框架下，于单次咨询中执行系统脱敏干预：依据已构建的焦虑等级表，结合放松技术，逐级暴露并消退焦虑反应。

## Prompt

请按焦虑等级从低到高顺序，引导来访者想象每个等级情境，同步使用已习得的放松技术（如渐进式肌肉放松或腹式呼吸），每级停留至主观焦虑下降50%以上再进入下一级。

## Objective

降低特定情境下的条件性焦虑反应
## Applicable Signals

- 主观焦虑量表（SUDS）评分≥40
- 能自主调用放松技术
- 对暴露无急性解离或惊恐发作

## Contraindications

- 存在未稳定的精神病性症状
- 近期有自伤/自杀意念未完成安全评估
- 无法耐受中度焦虑（SUDS>60）

## Intervention Moves

- 引导想象暴露
- 同步放松引导
- SUDS即时校准
- 等级间暂停与确认

## Workflow Steps

- 1. 确认当前可用焦虑等级表；2. 选择最低未耐受等级启动；3. 引导想象+放松同步进行；4. 每级停留至SUDS下降≥50%；5. 记录耐受等级与残留反应；6. 商定家庭暴露练习

## Constraints

- 必须严格遵循等级顺序
- 单次最多完成3个等级
- 每次暴露后须完成放松归零

## Cautions

- 避免跳级或加速进程
- 若SUDS上升或停滞超2分钟，立即退回上一级并强化放松

## Output Contract

- {'SUDS_change_per_level': '≥50%下降', 'completed_levels_per_session': '1–3', 'safety_check_completed': 'true'}

## Example Therapist Responses

### Example 1

- Client/Input: 来访者SUDS=50，进入等级3（后台候场）想象
- Therapist/Output: 引导其闭眼想象候场场景，同步指导腹式呼吸（4-7-8法），每30秒询问SUDS；当降至≤25时，确认后进入等级4
- Notes: 需实时监测生理指标（如呼吸频率、手心出汗）作为辅助判断

## Objective

降低特定情境下的条件性焦虑反应
## Applicable Signals

- 主观焦虑量表（SUDS）评分≥40
- 能自主调用放松技术
- 对暴露无急性解离或惊恐发作

## Contraindications

- 存在未稳定的精神病性症状
- 近期有自伤/自杀意念未完成安全评估
- 无法耐受中度焦虑（SUDS>60）

## Intervention Moves

- 引导想象暴露
- 同步放松引导
- SUDS即时校准
- 等级间暂停与确认

## Workflow Steps

- 1. 确认当前可用焦虑等级表；2. 选择最低未耐受等级启动；3. 引导想象+放松同步进行；4. 每级停留至SUDS下降≥50%；5. 记录耐受等级与残留反应；6. 商定家庭暴露练习

## Constraints

- 必须严格遵循等级顺序
- 单次最多完成3个等级
- 每次暴露后须完成放松归零

## Cautions

- 避免跳级或加速进程
- 若SUDS上升或停滞超2分钟，立即退回上一级并强化放松

## Output Contract

- {'SUDS_change_per_level': '≥50%下降', 'completed_levels_per_session': '1–3', 'safety_check_completed': 'true'}

## Example Therapist Responses

### Example 1

- Client/Input: 来访者SUDS=50，进入等级3（后台候场）想象
- Therapist/Output: 引导其闭眼想象候场场景，同步指导腹式呼吸（4-7-8法），每30秒询问SUDS；当降至≤25时，确认后进入等级4
- Notes: 需实时监测生理指标（如呼吸频率、手心出汗）作为辅助判断

## Files

- `references/evidence.md`
- `references/evidence_manifest.json`

## Triggers

- 已完成焦虑等级量表构建
- 来访者已掌握基础放松技术
- 当前咨询阶段为暴露干预期

## Examples

### Example 1

Input:

  来访者SUDS=50，进入等级3（后台候场）想象

Output:

  引导其闭眼想象候场场景，同步指导腹式呼吸（4-7-8法），每30秒询问SUDS；当降至≤25时，确认后进入等级4

Notes:

  需实时监测生理指标（如呼吸频率、手心出汗）作为辅助判断
