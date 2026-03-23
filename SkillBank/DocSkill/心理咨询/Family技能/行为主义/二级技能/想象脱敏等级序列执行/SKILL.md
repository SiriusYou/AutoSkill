---
id: "cce111ac-77d7-5baf-bf50-73c1d0285aaa"
name: "想象脱敏等级序列执行"
description: "在行为主义框架下，按焦虑等级由低到高引导来访者进行想象暴露，并配合放松技术以降低生理唤醒水平。适用于已建立焦虑等级表且无急性危机的来访者。"
version: "0.1.0"
tags:
  - "行为主义"
  - "想象暴露"
  - "系统脱敏"
  - "SUDS"
  - "profile:psychology::行为主义"
  - "axis:疗法"
  - "class:行为主义"
  - "kind:child"
  - "document_merge_state:active"
  - "canonical:true"
triggers:
  - "来访者已完成个性化焦虑等级表构建"
  - "当前无自杀/自伤/暴力风险"
  - "来访者能自主启动并维持放松状态"
examples:
  - input: "来访者想象‘走进教室准备交作业’，报告SUDS=5"
    output: "指导腹式呼吸6轮后，SUDS降至1；来访者说：‘胸口不发紧了’"
    notes: "成功完成第一等级"
  - input: "来访者想象‘被老师点名回答问题’，SUDS=7"
    output: "放松后SUDS=3 → 未达标，暂停推进，巩固放松反应"
    notes: "触发谨慎推进规则"
---

# 想象脱敏等级序列执行

在行为主义框架下，按焦虑等级由低到高引导来访者进行想象暴露，并配合放松技术以降低生理唤醒水平。适用于已建立焦虑等级表且无急性危机的来访者。

## Prompt

1. 确认来访者已掌握基础放松技术（如渐进式肌肉放松或腹式呼吸）；
2. 从焦虑等级表中最轻情境开始，引导其闭眼想象该中性-低焦虑情境；
3. 评估主观焦虑单位量表（SUDS, 0–10）得分；
4. 若SUDS ≥ 3，指导其运用已习得放松技术，持续至SUDS ≤ 2；
5. 每次会话推进1–3个等级，依耐受度动态调整；
6. 每等级结束时明确确认SUDS达标并记录。

## Objective

降低特定情境下的条件性焦虑反应
## Applicable Signals

- 来访者报告特定社交/考试情境下可预测的条件性焦虑
- 生理唤醒明显（如心悸、出汗）但意识清晰、现实检验完整
- 对想象暴露有基本信任与合作意愿

## Contraindications

- 存在解离体验或现实检验受损
- 处于急性应激反应期（如考试前24小时内）
- 未完成基线放松训练或无法自主调用放松反应

## Intervention Moves

- 引导性想象启动
- SUDS即时锚定与反馈
- 放松技术嵌入式应用
- 等级间暂停与再评估

## Workflow Steps

- 确认放松能力与等级表就绪
- 引导想象最轻等级情境
- 获取初始SUDS评分
- 如SUDS ≥ 3，嵌入放松技术直至SUDS ≤ 2
- 确认达标并记录，决定是否推进下一等级

## Constraints

- 必须使用来访者本人参与构建的等级表
- 每次仅处理一个等级情境，不得跳级
- SUDS需由来访者自主报告，不代述、不修正

## Cautions

- 避免在疲劳、低血糖或躯体不适状态下开展
- 若单等级SUDS反复≥4且放松无效，暂停并评估是否需调整等级或引入支持性干预

## Output Contract

- 来访者对当前处理等级情境的主观焦虑评分（SUDS）稳定≤2（0–10分制），并可口头确认‘此刻感到平静/可控’。

## Example Therapist Responses

### Example 1

- Client/Input: 来访者想象‘走进教室准备交作业’，报告SUDS=5
- Therapist/Output: 指导腹式呼吸6轮后，SUDS降至1；来访者说：‘胸口不发紧了’
- Notes: 成功完成第一等级

### Example 2

- Client/Input: 来访者想象‘被老师点名回答问题’，SUDS=7
- Therapist/Output: 放松后SUDS=3 → 未达标，暂停推进，巩固放松反应
- Notes: 触发谨慎推进规则

## Objective

降低特定情境下的条件性焦虑反应
## Applicable Signals

- 来访者报告特定社交/考试情境下可预测的条件性焦虑
- 生理唤醒明显（如心悸、出汗）但意识清晰、现实检验完整
- 对想象暴露有基本信任与合作意愿

## Contraindications

- 存在解离体验或现实检验受损
- 处于急性应激反应期（如考试前24小时内）
- 未完成基线放松训练或无法自主调用放松反应

## Intervention Moves

- 引导性想象启动
- SUDS即时锚定与反馈
- 放松技术嵌入式应用
- 等级间暂停与再评估

## Workflow Steps

- 确认放松能力与等级表就绪
- 引导想象最轻等级情境
- 获取初始SUDS评分
- 如SUDS ≥ 3，嵌入放松技术直至SUDS ≤ 2
- 确认达标并记录，决定是否推进下一等级

## Constraints

- 必须使用来访者本人参与构建的等级表
- 每次仅处理一个等级情境，不得跳级
- SUDS需由来访者自主报告，不代述、不修正

## Cautions

- 避免在疲劳、低血糖或躯体不适状态下开展
- 若单等级SUDS反复≥4且放松无效，暂停并评估是否需调整等级或引入支持性干预

## Output Contract

- 来访者对当前处理等级情境的主观焦虑评分（SUDS）稳定≤2（0–10分制），并可口头确认‘此刻感到平静/可控’。

## Example Therapist Responses

### Example 1

- Client/Input: 来访者想象‘走进教室准备交作业’，报告SUDS=5
- Therapist/Output: 指导腹式呼吸6轮后，SUDS降至1；来访者说：‘胸口不发紧了’
- Notes: 成功完成第一等级

### Example 2

- Client/Input: 来访者想象‘被老师点名回答问题’，SUDS=7
- Therapist/Output: 放松后SUDS=3 → 未达标，暂停推进，巩固放松反应
- Notes: 触发谨慎推进规则

## Files

- `references/evidence.md`
- `references/evidence_manifest.json`

## Triggers

- 来访者已完成个性化焦虑等级表构建
- 当前无自杀/自伤/暴力风险
- 来访者能自主启动并维持放松状态

## Examples

### Example 1

Input:

  来访者想象‘走进教室准备交作业’，报告SUDS=5

Output:

  指导腹式呼吸6轮后，SUDS降至1；来访者说：‘胸口不发紧了’

Notes:

  成功完成第一等级

### Example 2

Input:

  来访者想象‘被老师点名回答问题’，SUDS=7

Output:

  放松后SUDS=3 → 未达标，暂停推进，巩固放松反应

Notes:

  触发谨慎推进规则
