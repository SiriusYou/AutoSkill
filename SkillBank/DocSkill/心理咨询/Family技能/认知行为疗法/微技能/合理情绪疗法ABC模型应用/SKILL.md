---
id: "c1b9da6b-a720-5c5a-9b54-e987cad656e4"
name: "合理情绪疗法ABC模型应用"
description: "在咨询中识别来访者非理性信念（B），并将其与诱发事件（A）和情绪行为后果（C）建立结构化联结，为后续认知重构奠定基础。"
version: "0.1.0"
tags:
  - "CBT"
  - "合理情绪疗法"
  - "ABC模型"
  - "认知评估"
  - "认知行为疗法"
  - "profile:psychology::认知行为疗法"
  - "axis:疗法"
triggers:
  - "来访者表达持续低落、自我否定、灾难化预期；评估确认存在明显认知扭曲；咨询目标聚焦于情绪调节与信念调整"
examples:
  - input: "我实习没被留下，我觉得自己彻底失败了，以后肯定找不到工作。"
    output: "{'A': '实习未被留用', 'B': '我没被留下=我彻底失败；找不到工作是必然结果', 'C': '羞愧、失眠、回避投简历', 'distortion_type': ['absolute_demand', 'overgeneralization', 'catastrophizing']}"
    notes: "识别出三类典型扭曲，为后续作业布置提供靶点"
---

# 合理情绪疗法ABC模型应用

在咨询中识别来访者非理性信念（B），并将其与诱发事件（A）和情绪行为后果（C）建立结构化联结，为后续认知重构奠定基础。

## Prompt

请协助来访者识别：①最近一次引发强烈负面情绪的具体事件（A）；②当时自动浮现的想法或内心独白（B）；③随之出现的情绪反应、身体感受及行为倾向（C）。特别注意是否存在绝对化要求、过度概括或糟糕至极等典型非理性特征。

## Objective

完成单次会谈中的ABC结构化识别与初步归因澄清
## Applicable Signals

- 言语中高频使用‘必须’‘应该’‘永远不行’‘全完了’等绝对化/泛化表述
- 情绪强度与事件客观严重性明显不匹配

## Contraindications

- 急性危机状态（如自杀意念活跃）未稳定前
- 严重现实检验能力受损（如精神病性症状）

## Intervention Moves

- 开放式提问引导事件还原
- 重述+镜映确认信念内容
- 标注认知扭曲类型并简要命名

## Workflow Steps

- 1. 锚定具体情境（A）→ 2. 提取即时想法（B）→ 3. 记录情绪/行为反应（C）→ 4. 共同标注扭曲类型

## Constraints

- 需在来访者情绪可耐受范围内进行；避免直接否定或辩论信念

## Cautions

- 不急于挑战B，优先建立共情性理解；命名扭曲时使用中性、教育性语言（如‘这属于心理学中常见的‘以偏概全’模式’）

## Output Contract

- {'abc_triplet': {'A': 'string', 'B': 'string', 'C': 'string', 'distortion_type': ['absolute_demand', 'overgeneralization', 'catastrophizing', 'other']}}

## Example Therapist Responses

### Example 1

- Client/Input: 我实习没被留下，我觉得自己彻底失败了，以后肯定找不到工作。
- Therapist/Output: {'A': '实习未被留用', 'B': '我没被留下=我彻底失败；找不到工作是必然结果', 'C': '羞愧、失眠、回避投简历', 'distortion_type': ['absolute_demand', 'overgeneralization', 'catastrophizing']}
- Notes: 识别出三类典型扭曲，为后续作业布置提供靶点

## Objective

完成单次会谈中的ABC结构化识别与初步归因澄清
## Applicable Signals

- 言语中高频使用‘必须’‘应该’‘永远不行’‘全完了’等绝对化/泛化表述
- 情绪强度与事件客观严重性明显不匹配

## Contraindications

- 急性危机状态（如自杀意念活跃）未稳定前
- 严重现实检验能力受损（如精神病性症状）

## Intervention Moves

- 开放式提问引导事件还原
- 重述+镜映确认信念内容
- 标注认知扭曲类型并简要命名

## Workflow Steps

- 1. 锚定具体情境（A）→ 2. 提取即时想法（B）→ 3. 记录情绪/行为反应（C）→ 4. 共同标注扭曲类型

## Constraints

- 需在来访者情绪可耐受范围内进行；避免直接否定或辩论信念

## Cautions

- 不急于挑战B，优先建立共情性理解；命名扭曲时使用中性、教育性语言（如‘这属于心理学中常见的‘以偏概全’模式’）

## Output Contract

- {'abc_triplet': {'A': 'string', 'B': 'string', 'C': 'string', 'distortion_type': ['absolute_demand', 'overgeneralization', 'catastrophizing', 'other']}}

## Example Therapist Responses

### Example 1

- Client/Input: 我实习没被留下，我觉得自己彻底失败了，以后肯定找不到工作。
- Therapist/Output: {'A': '实习未被留用', 'B': '我没被留下=我彻底失败；找不到工作是必然结果', 'C': '羞愧、失眠、回避投简历', 'distortion_type': ['absolute_demand', 'overgeneralization', 'catastrophizing']}
- Notes: 识别出三类典型扭曲，为后续作业布置提供靶点

## Files

- `references/evidence.md`
- `references/evidence_manifest.json`

## Triggers

- 来访者表达持续低落、自我否定、灾难化预期；评估确认存在明显认知扭曲；咨询目标聚焦于情绪调节与信念调整

## Examples

### Example 1

Input:

  我实习没被留下，我觉得自己彻底失败了，以后肯定找不到工作。

Output:

  {'A': '实习未被留用', 'B': '我没被留下=我彻底失败；找不到工作是必然结果', 'C': '羞愧、失眠、回避投简历', 'distortion_type': ['absolute_demand', 'overgeneralization', 'catastrophizing']}

Notes:

  识别出三类典型扭曲，为后续作业布置提供靶点
