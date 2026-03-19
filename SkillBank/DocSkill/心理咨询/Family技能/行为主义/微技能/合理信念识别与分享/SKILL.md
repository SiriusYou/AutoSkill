---
id: "879fa120-7492-5040-910d-124383e7d5ce"
name: "合理信念识别与分享"
description: "在CBT咨询中，引导求助者识别、命名并主动陈述其具适应性、符合现实的合理认知信念，作为认知重构的建设性起点。"
version: "0.1.0"
tags:
  - "CBT"
  - "认知重构"
  - "信念识别"
  - "adaptive_belief"
  - "行为主义"
  - "profile:psychology::行为主义"
  - "axis:疗法"
triggers:
  - "求助者已初步建立咨询关系"
  - "已完成情绪与行为问题评估"
  - "存在可观察的非适应性自动思维"
examples:
  - input: "上次排练出错了，我觉得自己太差劲了，根本不配站上舞台。"
    output: "你刚才说‘根本不配’——这个想法让你很痛苦。我们先不急着判断它对不对，你能试着想一想：有没有另一个更温和、更贴近现实的想法？比如，关于‘努力’或‘学习过程’的想法？"
---

# 合理信念识别与分享

在CBT咨询中，引导求助者识别、命名并主动陈述其具适应性、符合现实的合理认知信念，作为认知重构的建设性起点。

## Prompt

请分享一个你最近遇到类似情境时，自己觉得比较合理、有帮助的想法或信念。

## Objective

促进求助者对自身认知系统的觉察，区分合理与不合理信念，为后续辩论与重构提供清晰、可操作的适应性靶点
## Applicable Signals

- 语言中出现绝对化用语（如‘必须’‘应该’）
- 情绪反应强度明显高于事件本身
- 行为回避或过度补偿

## Contraindications

- 求助者处于急性危机状态（如自杀意念活跃）
- 存在严重现实检验能力受损

## Intervention Moves

- 开放式提问引导自我报告
- 正常化认知多样性
- 标注信念内容并复述确认

## Workflow Steps

- 1. 确认当前情境与情绪反应；2. 邀请描述头脑中浮现的具体想法；3. 区分该想法是否符合事实、是否具适应性；4. 共同命名其为‘合理信念’并记录

## Constraints

- 必须在建立信任与安全感后进行
- 不可替代共情性倾听而直接进入认知分析

## Cautions

- 避免评判性语言（如‘这显然不对’）
- 不急于纠正，优先接纳表达

## Output Contract

- {'type': 'object', 'required_fields': ['belief_content', 'context', 'self_assessment_rating'], 'examples': [{'belief_content': '我尽力了，结果如何不是我能完全控制的', 'context': '舞蹈汇报演出前', 'self_assessment_rating': 7}]}

## Example Therapist Responses

### Example 1

- Client/Input: 上次排练出错了，我觉得自己太差劲了，根本不配站上舞台。
- Therapist/Output: 你刚才说‘根本不配’——这个想法让你很痛苦。我们先不急着判断它对不对，你能试着想一想：有没有另一个更温和、更贴近现实的想法？比如，关于‘努力’或‘学习过程’的想法？

## Objective

促进求助者对自身认知系统的觉察，区分合理与不合理信念，为后续辩论与重构提供清晰、可操作的适应性靶点
## Applicable Signals

- 语言中出现绝对化用语（如‘必须’‘应该’）
- 情绪反应强度明显高于事件本身
- 行为回避或过度补偿

## Contraindications

- 求助者处于急性危机状态（如自杀意念活跃）
- 存在严重现实检验能力受损

## Intervention Moves

- 开放式提问引导自我报告
- 正常化认知多样性
- 标注信念内容并复述确认

## Workflow Steps

- 1. 确认当前情境与情绪反应
- 2. 邀请描述头脑中浮现的具体想法
- 3. 区分该想法是否符合事实、是否具适应性
- 4. 共同命名其为‘合理信念’并记录

## Constraints

- 必须在建立信任与安全感后进行
- 不可替代共情性倾听而直接进入认知分析

## Cautions

- 避免评判性语言（如‘这显然不对’）
- 不急于纠正，优先接纳表达

## Output Contract

- {'type': 'object', 'required_fields': ['belief_content', 'context', 'self_assessment_rating'], 'examples': [{'belief_content': '我尽力了，结果如何不是我能完全控制的', 'context': '舞蹈汇报演出前', 'self_assessment_rating': 7}]}

## Example Therapist Responses

### Example 1

- Client/Input: 上次排练出错了，我觉得自己太差劲了，根本不配站上舞台。
- Therapist/Output: 你刚才说‘根本不配’——这个想法让你很痛苦。我们先不急着判断它对不对，你能试着想一想：有没有另一个更温和、更贴近现实的想法？比如，关于‘努力’或‘学习过程’的想法？

## Files

- `references/evidence.md`
- `references/evidence_manifest.json`

## Triggers

- 求助者已初步建立咨询关系
- 已完成情绪与行为问题评估
- 存在可观察的非适应性自动思维

## Examples

### Example 1

Input:

  上次排练出错了，我觉得自己太差劲了，根本不配站上舞台。

Output:

  你刚才说‘根本不配’——这个想法让你很痛苦。我们先不急着判断它对不对，你能试着想一想：有没有另一个更温和、更贴近现实的想法？比如，关于‘努力’或‘学习过程’的想法？
