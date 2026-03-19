---
id: "388fe4cb-8b67-5fa6-874f-06477dfbcd73"
name: "RET自助表辩论与合理信念替换"
description: "引导求助者使用理性情绪疗法（RET）自助表识别不合理信念，并通过苏格拉底式提问进行自我辩论，最终用合理信念替代原有非适应性认知。"
version: "0.1.0"
tags:
  - "RET"
  - "认知重构"
  - "家庭作业反馈"
  - "CBT"
  - "认知行为疗法"
  - "profile:psychology::认知行为疗法"
  - "axis:疗法"
triggers:
  - "求助者完成RET自助表作业"
  - "出现情绪波动后主动提及认知困扰"
  - "咨询进入巩固阶段且已有基础认知重构经验"
examples:
  - input: "我必须被所有人认可，否则我就毫无价值。"
    output: "我希望能被尊重，但不被某个人认可，并不等于我没有价值——我的价值不取决于他人评价。"
    notes: "采用‘希望…但…’句式软化绝对化要求"
  - input: "这次汇报搞砸了，说明我根本不适合这份工作。"
    output: "这次表现未达预期，但过去三个月成功完成5个项目，说明我具备胜任力；可聚焦改进具体环节。"
    notes: "引入行为证据对抗以偏概全"
---

# RET自助表辩论与合理信念替换

引导求助者使用理性情绪疗法（RET）自助表识别不合理信念，并通过苏格拉底式提问进行自我辩论，最终用合理信念替代原有非适应性认知。

## Prompt

请回顾你刚才记录的自动思维和情绪反应。这个想法背后隐含了什么绝对化要求或灾难化预测？有没有更灵活、更符合现实的另一种解释？

## Objective

促进求助者内化认知辩论能力，实现自动化不合理信念的觉察与替代
## Applicable Signals

- 能准确填写ABC表格
- 情绪强度下降但仍有残留不适
- 表达‘我知道这样想不对，但还是忍不住’

## Contraindications

- 急性危机状态
- 严重注意力障碍未稳定
- 否认问题存在且无改变动机

## Intervention Moves

- 引导复述不合理信念
- 提问检验证据/替代解释/后果评估
- 协同生成合理信念陈述

## Constraints

- 必须建立在前几次已开展ABC模型教学和至少一次RET表练习基础上
- 避免直接否定求助者信念，须以协作探索方式推进

## Cautions

- 防止过度追求逻辑完美而忽略情绪体验；需同步验证情绪缓解效果

## Output Contract

- {'has_reasonable_belief_substitution': True, 'includes_personalized_language': True, 'links_to_behavioral_outcome': True}

## Example Therapist Responses

### Example 1

- Client/Input: 我必须被所有人认可，否则我就毫无价值。
- Therapist/Output: 我希望能被尊重，但不被某个人认可，并不等于我没有价值——我的价值不取决于他人评价。
- Notes: 采用‘希望…但…’句式软化绝对化要求

### Example 2

- Client/Input: 这次汇报搞砸了，说明我根本不适合这份工作。
- Therapist/Output: 这次表现未达预期，但过去三个月成功完成5个项目，说明我具备胜任力；可聚焦改进具体环节。
- Notes: 引入行为证据对抗以偏概全

## Objective

促进求助者内化认知辩论能力，实现自动化不合理信念的觉察与替代
## Applicable Signals

- 能准确填写ABC表格
- 情绪强度下降但仍有残留不适
- 表达‘我知道这样想不对，但还是忍不住’

## Contraindications

- 急性危机状态
- 严重注意力障碍未稳定
- 否认问题存在且无改变动机

## Intervention Moves

- 引导复述不合理信念
- 提问检验证据/替代解释/后果评估
- 协同生成合理信念陈述

## Constraints

- 必须建立在前几次已开展ABC模型教学和至少一次RET表练习基础上
- 避免直接否定求助者信念，须以协作探索方式推进

## Cautions

- 防止过度追求逻辑完美而忽略情绪体验；需同步验证情绪缓解效果

## Output Contract

- {'has_reasonable_belief_substitution': True, 'includes_personalized_language': True, 'links_to_behavioral_outcome': True}

## Example Therapist Responses

### Example 1

- Client/Input: 我必须被所有人认可，否则我就毫无价值。
- Therapist/Output: 我希望能被尊重，但不被某个人认可，并不等于我没有价值——我的价值不取决于他人评价。
- Notes: 采用‘希望…但…’句式软化绝对化要求

### Example 2

- Client/Input: 这次汇报搞砸了，说明我根本不适合这份工作。
- Therapist/Output: 这次表现未达预期，但过去三个月成功完成5个项目，说明我具备胜任力；可聚焦改进具体环节。
- Notes: 引入行为证据对抗以偏概全

## Files

- `references/evidence.md`
- `references/evidence_manifest.json`

## Triggers

- 求助者完成RET自助表作业
- 出现情绪波动后主动提及认知困扰
- 咨询进入巩固阶段且已有基础认知重构经验

## Examples

### Example 1

Input:

  我必须被所有人认可，否则我就毫无价值。

Output:

  我希望能被尊重，但不被某个人认可，并不等于我没有价值——我的价值不取决于他人评价。

Notes:

  采用‘希望…但…’句式软化绝对化要求

### Example 2

Input:

  这次汇报搞砸了，说明我根本不适合这份工作。

Output:

  这次表现未达预期，但过去三个月成功完成5个项目，说明我具备胜任力；可聚焦改进具体环节。

Notes:

  引入行为证据对抗以偏概全
