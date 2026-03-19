---
id: "9de564ce-5aa8-5109-a5d7-1ebd0c997868"
name: "自杀意念结构化评估话术"
description: "一套简明、非威胁、临床有效的自杀风险递进式提问序列，用于精准识别意念强度、计划性与即时风险。"
version: "0.1.0"
tags:
  - "CBT"
  - "风险评估"
  - "结构化提问"
  - "认知行为疗法"
  - "profile:psychology::认知行为疗法"
  - "axis:疗法"
triggers:
  - "来访者提及情绪低落、无价值感、疲惫感"
  - "观察到言语/行为退缩迹象"
examples:
  - input: "来访者点头说：‘嗯…有时候觉得睡过去就不用醒了。’"
    output: "‘谢谢你这么说。那如果这种想法来了，你心里有没有想过，万一真要那样，会怎么安排？’"
    notes: "承接情绪，自然过渡到计划性评估"
---

# 自杀意念结构化评估话术

一套简明、非威胁、临床有效的自杀风险递进式提问序列，用于精准识别意念强度、计划性与即时风险。

## Prompt

依次使用以下四句提问（每句后停顿倾听，不打断）：1）‘最近几周，有没有过希望不再醒来的想法？’；2）‘如果这种想法出现，你心里有没有想过具体怎么做？’；3）‘有没有定下时间，或者准备过相关的东西？’；4）‘过去有没有试过类似的做法？现在身边有没有人知道你的情况、能帮你撑住？’

## Objective

快速、安全、准确识别自杀风险等级
## Applicable Signals

- 语速缓慢、目光回避、叹气频繁
- ‘活着没意思’‘拖累别人’等表达

## Contraindications

- 来访者处于惊恐发作中
- 语言障碍致理解困难

## Intervention Moves

- 递进式封闭-开放式混合提问
- 中性语气陈述
- 停顿留白

## Workflow Steps

- 提问1→等待回应→提问2→等待回应→提问3→等待回应→提问4→整合判断

## Constraints

- 必须按顺序提问，不可跳步
- 每次提问后至少等待5秒
- 不记录答案前不进入下一题

## Cautions

- 禁用‘你不会真的去做吧？’等质疑性反问
- 不使用‘自杀’一词开头，首问用‘不再醒来’等缓释表达

## Output Contract

- {'ideation': 'present|absent', 'plan': 'present|absent', 'means': 'present|absent', 'intent': 'present|absent', 'protective_factors': 'list'}

## Example Therapist Responses

### Example 1

- Client/Input: 来访者点头说：‘嗯…有时候觉得睡过去就不用醒了。’
- Therapist/Output: ‘谢谢你这么说。那如果这种想法来了，你心里有没有想过，万一真要那样，会怎么安排？’
- Notes: 承接情绪，自然过渡到计划性评估

## Objective

快速、安全、准确识别自杀风险等级
## Applicable Signals

- 语速缓慢、目光回避、叹气频繁
- ‘活着没意思’‘拖累别人’等表达

## Contraindications

- 来访者处于惊恐发作中
- 语言障碍致理解困难

## Intervention Moves

- 递进式封闭-开放式混合提问
- 中性语气陈述
- 停顿留白

## Workflow Steps

- 提问1→等待回应→提问2→等待回应→提问3→等待回应→提问4→整合判断

## Constraints

- 必须按顺序提问，不可跳步
- 每次提问后至少等待5秒
- 不记录答案前不进入下一题

## Cautions

- 禁用‘你不会真的去做吧？’等质疑性反问
- 不使用‘自杀’一词开头，首问用‘不再醒来’等缓释表达

## Output Contract

- {'ideation': 'present|absent', 'plan': 'present|absent', 'means': 'present|absent', 'intent': 'present|absent', 'protective_factors': 'list'}

## Example Therapist Responses

### Example 1

- Client/Input: 来访者点头说：‘嗯…有时候觉得睡过去就不用醒了。’
- Therapist/Output: ‘谢谢你这么说。那如果这种想法来了，你心里有没有想过，万一真要那样，会怎么安排？’
- Notes: 承接情绪，自然过渡到计划性评估

## Files

- `references/evidence.md`
- `references/evidence_manifest.json`

## Triggers

- 来访者提及情绪低落、无价值感、疲惫感
- 观察到言语/行为退缩迹象

## Examples

### Example 1

Input:

  来访者点头说：‘嗯…有时候觉得睡过去就不用醒了。’

Output:

  ‘谢谢你这么说。那如果这种想法来了，你心里有没有想过，万一真要那样，会怎么安排？’

Notes:

  承接情绪，自然过渡到计划性评估
